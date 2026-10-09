# 03 · PROJECT: RAG-Based Academic Document Explainer ("StructRAG")

**Solo project, all 9 commits mine (6 Mar to 13 Aug 2026). Frontend on Vercel; backend config for Railway (live status = F8 in file 2).**

## Resume lines vs truth (know this before any question)
- "Built and deployed a full-stack RAG app… embeddings and vector search" → ✓ built. "Deployed" = partly: frontend on Vercel; backend was reported down on 27 Sep 2026 (see F8). Don't say "it's live" unless F8 says so; offer to run it locally with Docker.
- "REST API for chunking, indexing, retrieval, **multi-turn** Q&A" → ✓ REST, chunking, indexing, retrieval. **✗ Multi-turn is NOT true in the strict sense:** the chat screen shows several questions in a row, but each question is sent alone, with no history, so "what about its limitations?" has no referent. If asked, say this first, then the fix (send last N messages, or have the LLM rewrite follow-ups into standalone queries before retrieval).

## 30-second pitch
"I built a web app where you upload a research paper as a PDF and ask questions about it. The backend splits it into chunks, turns them into embeddings and stores them in ChromaDB. For each question it finds the most relevant chunks, gives them to an LLM, and returns the answer with page-level sources. FastAPI and Python on the backend, React with TypeScript on the front, Docker and GitHub Actions CI. I also added an experimental section-aware ranking layer, which I haven't formally evaluated."

## How it works
- **Stack:** FastAPI 0.115 + Pydantic, gunicorn with 1 uvicorn worker, Python 3.11 · pypdf (plus `unstructured` fallback) · LangChain text splitter · sentence-transformers `all-MiniLM-L6-v2` (384-dim, normalized) · ChromaDB 0.5 · SQLite (tables: jobs, documents, document_trees) · LLM providers OpenAI / Gemini / Hugging Face / **mock (default)** · React 18 + TypeScript + Vite + Tailwind + Axios · Docker Compose (backend + Chroma server + frontend) · GitHub Actions (3 jobs: backend pytest; frontend lint/test/build; Docker builds).
- **Upload flow:** `POST /api/v1/upload` saves the PDF, creates a job row, returns **202** + job id at once. A FastAPI background task then: parse pages (pypdf) → build section tree → chunk each page (**3000 chars, 800 overlap**, per page so every chunk has a page number) → embed in batches → write vectors to Chroma and tree to SQLite. Progress 25/50/60/80/100 stored in `jobs`; the browser polls `GET /status/{job_id}` every second.
- **Ask flow:** embed the question → Chroma nearest chunks (filtered by `doc_id`, fetch 2×top_k) → StructRAG boost → prompt (answer only from context, say "I don't know" otherwise, temperature 0.2) → LLM → answer + sources (page, snippet, chunk id, score). top_k 1–10, default 5.
- **StructRAG layer:** ingestion detects headings (LLM table of contents if a real provider is set, else regex rules), makes a **flat** list of sections with page ranges and one of 13 section types (methodology, results…). At query time up to 3 sections that match the question get chosen and chunks on their pages get score `1/(60+rank)` × a boost between 1.0 and 2.0, shrunk when few vector hits agree (confidence rule), plus a +0.1 bonus for chunks of the top 2 sections. k=60 is the usual RRF default.
- **API:** 9 endpoints under `/api/v1`: upload, status, docs list, docs delete, ask, explain-section, summarize, tree, tree/navigate (+ `/` and `/health`). The website itself only uses upload, status, list, delete, ask.
- **Real engineering fixes from my commits (good "challenge" stories, all true):** broken-pipe errors from forked processes inside uvicorn workers → switched multiprocessing start method to `spawn` and turned off tokenizer parallelism; answer quality improved by sending full chunk text in the prompt instead of a short snippet; raised Gemini output limit so answers weren't cut off; a configured Gemini model was retired (404) → added model fallback; CORS made to accept several origins so the Vercel frontend can call the backend; workers reduced from 2 to 1 (I believe because of in-process state and memory, but I didn't write the reason down).

## Why these choices (say "the usual reason is…"; one alternative each)
FastAPI: type hints give validation and docs, ML libraries are in Python (alt: Spring Boot/Flask). ChromaDB: embedded, no extra server, metadata filter (alt: pgvector, FAISS, Qdrant; not benchmarked). MiniLM: small, free, CPU, no API key (alt: hosted/larger model; not compared). 3000/800: chosen by judgement to approximate ~800-token chunks, **not tuned**. 202 + polling + background task: no extra infra (alt: Celery/Redis queue + SSE/WebSockets). SQLite: zero setup (alt: PostgreSQL). Mock provider: runs the whole pipeline with no key, so CI needs none.

## Weaknesses: say these first, then the fix
1. **No retrieval evaluation.** Fix: gold set of 30–50 questions with correct pages; compare recall@5 and MRR for plain vector vs boosted; score groundedness.
2. **Not multi-turn** (above).
3. Tree is **flat** (depth bonus never applies); heading detection by regex mistakes titles/authors for sections; `classify_query` result is reported but not used in ranking; "hybrid" means vector + section boost, **no BM25/keyword search**; ATB-RRF has one ranked list, so it is a structure-aware re-rank, not a true fusion.
4. **Not production-ready:** no authentication (anyone can list/delete any document); ingestion runs inside the web process, so a restart mid-job leaves the job stuck in "processing"; storage is local SQLite/Chroma (lost on redeploy on typical free hosts); tests don't cover tree or ranking.
5. **UI bug:** in boosted mode the score is a fused rank score (max about 0.033), so the UI's "percentage" shows ~2% and the confidence badge reads "Low".
6. **Silent hash-embedding fallback** if the MiniLM model fails to load: pipeline keeps running but retrieval becomes meaningless. Should fail loudly.
7. LLM errors are returned as normal 200 chat text (should be 502/429); rate limiter (60/min per IP; 5 LLM calls/min global) is in-memory and global; weak upload validation (no size limit/`%PDF` check); scanned PDFs would fail (no OCR); tables/equations lose structure; keyword safety filter blocks some normal research questions; summary uses only 5 chunks; prompt-injection risk from PDF text; 3000-char chunks may exceed MiniLM's input limit (to verify).

## ✗ NOT CLAIM
Multi-turn/conversation memory · any accuracy/recall/"X% better" number · "StructRAG is proven/novel/patented/patent-pending/no prior art" · production-ready, scalable, secure, multi-user · "it is live and working" · "answers are always grounded / no hallucination / 100% cited" · hierarchical or depth-weighted tree · "query intent drives retrieval" · hybrid keyword+vector · handles scanned PDFs, tables, equations · 3000/800 are tuned or optimal · Redis/caching (Redis in compose is unused) · CI deploys or tests cover retrieval · UI has section explorer/summary · any user count or feedback · "I used Gemini free tier in production" · "sources prove each statement" (they are the retrieved chunks).

## Q&A (adapt wording; stay true)
**What is RAG and why use it?** Retrieve relevant text first, then ask the LLM to answer using it. The LLM never saw my PDF, and pasting the whole paper wastes context. RAG keeps prompts small and lets me show source pages. It reduces made-up answers but doesn't remove them.
**What is an embedding? How do you compare them?** A list of numbers (384 here) that represents meaning; similar meaning gives similar vectors. I use cosine similarity; vectors are normalized so it's a dot product.
**Why chunk? Why overlap?** One vector for a whole paper blurs meaning and the LLM has a limit; small chunks give precise page citations. Overlap keeps a sentence at a boundary whole, but only within a page because I chunk per page.
**Walk me through upload to cited answer.** (use Upload flow + Ask flow above, in order, 6–8 sentences.)
**Why 202, not 200?** The work isn't finished when I reply; parsing and embedding can take time, so I return a job id and the client polls status. Limitation: the task lives in the web process, so a restart strands the job; a queue fixes that.
**Why Chroma, MiniLM, 3000/800?** (see "Why these choices"); I didn't benchmark; I'd test on a question set and check MiniLM's input limit.
**Does RAG stop hallucination?** No. The prompt says answer only from context and say "I don't know", temperature is 0.2, but I don't verify answers against chunks. Measure with groundedness checks on a test set.
**What's temperature?** Controls randomness; low is more stable. 0.2 default; not fully deterministic.
**What is reciprocal rank fusion? What did you change?** RRF adds `1/(k+rank)` across ranked lists; k=60 is the common default. I have one list (vector), so I multiply by a 1–2 boost for chunks on likely sections. It is an experiment I haven't proven.
**How do you evaluate it?** I don't have a quantitative evaluation yet and won't invent numbers; plan = gold set, recall@5, MRR, groundedness, with/without boost.
**How would you scale it / scanned PDFs?** Queue (Celery + Redis) and workers, PostgreSQL, shared vector DB (Chroma server/pgvector/Qdrant), S3 for PDFs, auth with per-user documents and per-user rate limits; OCR (Tesseract) for scans.
**Is it production-ready?** No (weakness 4). It's a solid demo; order of fixes: evaluation, persistence, queue, auth, tests.
**Hardest bug?** Pick one real story from "Real engineering fixes" (broken-pipe/`spawn` or the retired Gemini model fallback).
**How do you handle secrets/config?** Pydantic Settings from environment variables; `.env` git-ignored; `.env.example` placeholders only; I found no real secret in repo or history.
**Prompt injection?** A malicious PDF could contain instructions for the model; my app has no tools to abuse, which limits damage; I'd add prompt delimiters and output filtering.
**Is "StructRAG" patent-pending/novel?** No; I haven't filed or searched prior art; it's an experimental ranking idea (my two actual patent applications are different, in file 2).
**Which part are you least proud of?** The silent hash fallback, errors hidden in 200 responses, and that some documented features (depth weighting) aren't active and nothing is evaluated.
**Docker and CI?** Dockerfile (python 3.11 slim, gunicorn + uvicorn worker, one worker), Compose runs backend + Chroma + frontend; GitHub Actions runs pytest, frontend lint/test/build, Docker builds; no deploy step; tests: 4 backend + 2 frontend.
