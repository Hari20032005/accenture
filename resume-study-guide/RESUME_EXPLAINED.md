# Hariharan S: Resume Explained
### Study guide for the Accenture final interview (HR + projects + basics)

*Written 9 Oct 2026. Every line of your resume is explained here in simple words, with the questions an interviewer can ask and honest answers. Project facts come from your three study guides, your two patent documents and your three open-source PRs. Basics (DSA, OOP, DBMS, OS, networks) are standard fresher-level knowledge.*

---

## 0. How to use this tonight

**How each section works:** (1) **30-second version**: what to say. (2) **Explained simply**: so you truly understand. (3) **Questions + answers**. (4) **Careful!**: things not to overclaim.

**What Accenture actually asks (from 54 written accounts + 20 Reddit reports):**
- Almost every interview = **"Introduce yourself" + "Explain your project"** (they cross-question).
- Then HR: teamwork, failure/conflict, strengths/weaknesses, why Accenture, goals, relocation.
- Technical is **small and basic**: OOP, DBMS/SQL, OS, DSA, cloud, maybe one easy coding/SQL question.
- 15–30 minutes, usually one interviewer, online. **Always ask 1–2 questions at the end. Never say "no".**
- What impresses: **your exact role, why you chose X over Y, and honest limits.** Not buzzwords.

**Suggested plan for tonight (about 6 hours):**

| Time | What | Sections |
|---|---|---|
| 45 min | Profile, education, your introduction | 1–2 |
| 90 min | The three projects, say each aloud 3 times | 3 |
| 90 min | CS basics (top questions only) | 4 |
| 30 min | Skills and certifications | 5 |
| 30 min | Patents and open source | 6 |
| 30 min | Risky claims, fill-in facts, HR answers | 7–8 |
| 15 min | Last-hour cheat sheet | 9 |
| Sleep | Do not study new things after this | |

**Three golden rules for tomorrow**
1. **Say "I" only for what you really did, "we" for team work.** If unsure, say "my part was ___, and I also studied the rest."
2. **Admit a limit first, then give the fix.** Interviewers trust people who know their own weaknesses.
3. **Never invent a number.** No made-up accuracy, users or percentages. "I haven't measured that, here is how I would" is a strong answer.

---

## 1. Your profile summary, phrase by phrase

> *"Integrated M.Tech Software Engineering student with hands-on experience designing and deploying full-stack web applications backed by REST APIs. Comfortable programming in Java and Python, with a solid foundation in data structures, algorithms, OOP, and computer networks. Currently building backend skills with Node.js. Co-inventor on two published patent applications, including one on cryptographic authentication and secure transaction sequencing."*

**30-second version:** "I'm a final-year Integrated M.Tech student. I build full-stack web apps, I'm strongest in Java and Python and in core CS, I'm learning Node.js for backend, and I'm a co-inventor on two patent applications."

### Explained simply

| Phrase | What it means in plain words |
|---|---|
| **Integrated M.Tech (UG + PG)** | A 5-year program where the bachelor's and master's levels are combined. You finish with an M.Tech degree. Yours is in Software Engineering at VIT Vellore, expected 2027. |
| **Full-stack web application** | An app with all three parts: the **frontend** (what the user sees, e.g. React), the **backend** (server logic, e.g. FastAPI/Express) and the **database** (where data is stored). You built all three parts across your projects. |
| **REST API** | A way for the frontend to talk to the backend using normal web requests (GET to read, POST to create, PUT/PATCH to update, DELETE to remove) and JSON data. Like a waiter carrying orders between the dining room and the kitchen. |
| **Designing and deploying** | Designing = deciding the structure (what talks to what). Deploying = putting it on the internet so others can use it (e.g. frontend on Vercel). **Careful:** your RAG backend deployment was reported down on 27 Sep, so say "frontend deployed on Vercel, backend config for Railway" unless you have checked it works today. |
| **Data structures, algorithms, OOP, networks** | Core computer science: how to store data efficiently, solve problems step by step, model things as objects, and how computers talk over networks. Section 4 covers all of them. |
| **Node.js (learning)** | JavaScript running on a server (outside the browser). You used it (with Express) in WasteZero. "Learning" is honest and fine. |
| **Co-inventor on two patent applications** | You are one of the named inventors on two filed applications (May 2026). Not granted. Details in section 6. |

### Questions and answers

**Q: What does "full stack" mean for you?**
"It means I can build the frontend, the backend API and the database layer of an app. For example, in my RAG project the frontend is React with TypeScript, the backend is FastAPI in Python, and the data lives in ChromaDB and SQLite."

**Q: Why Java and Python both?**
"Java is my main language for data structures, OOP and strong typing, which is what many enterprise systems use. Python is what I use for AI and for quick APIs with FastAPI. I choose by the job."

**Q: Are your patents granted?**
"No. They are patent applications filed in May 2026, so they are under process, not granted." *(Say "published" only if you have checked that they appear in the patent journal.)*

---

## 2. Education

| Level | Institute | Board / University | Year | Score |
|---|---|---|---|---|
| Integrated M.Tech (UG+PG) Software Engineering | VIT, Vellore | VIT (Deemed University) | 2027 (expected) | **8.07 / 10 CGPA** |
| 12th (Higher Secondary) | Sunbeam Matriculation School, Vellore | Tamil Nadu State Board | 2022 | 84.8% |
| 10th (SSLC) | Sunbeam Matriculation School, Vellore | Tamil Nadu State Board | 2020 | 84.8% |

### Explained simply
- **CGPA** = Cumulative Grade Point Average, your average grade across all semesters on a 10-point scale. 8.07 is a good, solid score. Do not convert it to a percentage yourself; if asked, say "8.07 out of 10 CGPA".
- **SSLC** = Secondary School Leaving Certificate (class 10). **HSC / Higher Secondary** = class 12. **Matriculation school** = a school in Tamil Nadu following the matriculation system.
- **Deemed University** = an institute with university status (VIT).
- **Careful:** your resume shows **84.8% for both 10th and 12th**. Check your marksheets tonight so what you say matches. HR verifies marks later.

**Q: Tell me about your academics.**
"I'm in the final stretch of an Integrated M.Tech in Software Engineering at VIT Vellore with a CGPA of 8.07. Before that I studied at Sunbeam Matriculation School in Vellore under the Tamil Nadu State Board, 84.8% in both 10th and 12th."

**Q: Why Software Engineering? Why an integrated program?**
Your honest reason, in 2–3 sentences. Safe structure: "I liked building things with code; the integrated program let me go deeper into software engineering, projects, research and patents, not just coursework." *(Replace with your real reason if different.)*

**Q: Favourite subject?** "Data structures and algorithms, because they train problem solving that I use in every project."

---

## 2b. Your 60-second introduction (learn this)

"Good morning. I'm **Hariharan S**, from Vellore in Tamil Nadu. I'm finishing an **Integrated M.Tech in Software Engineering at VIT Vellore**, CGPA 8.07, graduating in 2027. I'm strongest in **data structures, OOP, DBMS, operating systems and networks**, and I code mainly in **Java and Python**. I like building **complete products**: a **RAG-based academic document explainer** with FastAPI, ChromaDB and React; a **sugarcane pest-detection system** with Team Deepcrop that won **first prize at the DBT-sponsored Agrithon 2.0**; and **WasteZero**, a MERN platform I worked on in my **Infosys Springboard virtual internship**. I also have **three merged open-source pull requests**, I'm a **co-inventor on two patent applications**, and I hold **AWS Cloud Practitioner** and **Azure AI Fundamentals** certifications. I'd like to start my career at Accenture, learning on real client projects."

**Tips:** smile, slow down, pause after each project name. If they want one to dig into, they will say "tell me about X." Don't add anything not on your resume (no new claims).

---
## 3. Your projects, explained from zero

> The interviewer will spend most of the time here. For each project learn: **(a) one-line pitch, (b) how it works in order, (c) why you chose each tool, (d) what is weak and how you'd fix it, (e) your exact part.**

---

### 3.1 RAG-Based Academic Document Explainer ("StructRAG")

> **Resume:** *Built and deployed a full-stack Retrieval-Augmented Generation (RAG) app that answers questions over academic papers using text embeddings and vector search. Implemented a REST API backend for document chunking, indexing, retrieval, and multi-turn LLM-based Q&A.*

**30-second version:** "I built a web app where you upload a research paper as a PDF and ask questions about it. The backend splits the paper into chunks, converts them into embeddings and stores them in a vector database, ChromaDB. For each question it finds the most relevant chunks, gives them to an LLM, and returns the answer with page-level sources. FastAPI and Python on the backend, React with TypeScript on the front, Docker and GitHub Actions CI. I also added an experimental section-aware ranking layer that I haven't formally evaluated."

#### The idea in plain words
Reading a 15-page paper to find one answer is slow. Think of an **open-book exam with a helpful librarian**. The librarian (retrieval) finds the right pages first. The student (the LLM) answers using only those pages. That is RAG.

#### Words you must know (simple)
| Word | Meaning |
|---|---|
| **LLM** | Large Language Model, a program (GPT, Gemini…) that writes text from a prompt. |
| **Prompt** | The text you send to the LLM (instructions + question + context). |
| **Token** | A piece of a word; LLMs read and charge by tokens (about ¾ of a word). |
| **Context window** | How much text an LLM can read at once. Too long a paper may not fit. |
| **Hallucination** | The LLM confidently says something false or not in the source. |
| **Temperature** | Randomness setting. Low (0.2, mine) = stable and factual; high = creative. |
| **Embedding** | A list of numbers (384 in my model) that represents the *meaning* of a text. Similar meaning → similar numbers. |
| **Cosine similarity** | A score for how similar two embeddings are (compares their direction). 1 = very similar. |
| **Vector database** | A database that stores embeddings and quickly finds the nearest ones to a query (ChromaDB). |
| **Chunk** | A piece of the document (mine: up to 3000 characters). |
| **Overlap** | Chunks share some text (mine: 800 characters) so a sentence at the border isn't lost. |
| **RAG** | Retrieve relevant text first, then let the LLM answer from it. |
| **Background task / 202 / polling** | Do slow work after replying; reply "202 Accepted" with a job id; the browser keeps asking "done yet?" |

#### How it works, step by step
**A) Upload**
1. User uploads a PDF → `POST /api/v1/upload`.
2. Server saves the file, creates a **job** row (SQLite), replies **202** with a job id immediately.
3. A **background task** then: reads the PDF page by page (**pypdf**) → finds headings and builds a **section tree** → cuts each page into **chunks (3000 chars, 800 overlap)** → converts chunks to **384-number embeddings** (sentence-transformers `all-MiniLM-L6-v2`) → stores vectors (with page number) in **ChromaDB** and the tree in **SQLite**.
4. The browser polls `GET /status/{job_id}` every second; progress goes 25 → 50 → 60 → 80 → 100%.

**B) Ask**
1. User types a question. Server turns it into an embedding.
2. ChromaDB returns the **nearest chunks** of that document (fetches 2×top_k).
3. **StructRAG layer** re-ranks (below).
4. Server builds a prompt: "Answer only from this context; if not found say *I don't know*" + chunks + question. Calls the LLM (OpenAI / Gemini / Hugging Face / **mock**).
5. Response = answer + **sources** (page, snippet, chunk id, score).

#### What "StructRAG" adds (your own idea)
A research paper has predictable sections (Introduction, Methods, Results…). A question like "what accuracy did they get?" is probably answered in *Results*. So:
- During upload I detect **headings** (an LLM table of contents if a real provider is set, else regex rules), make a **flat list of sections** with page ranges and one of **13 section types**.
- At question time I pick up to **3 sections** that match the question, and multiply the rank score of chunks on those pages by a **boost between 1.0 and 2.0** (smaller when few of the vector hits agree).
- Base score is **reciprocal rank**: `1/(60 + rank)`. (k = 60 is the usual default from the RRF paper; example: rank 1 → 1/61 ≈ 0.0164; rank 2 with boost 1.5 → 1.5/62 ≈ 0.0242, so a boosted rank-2 chunk can beat an un-boosted rank-1 chunk.)
- **Honest label:** it's an *experimental idea; I haven't evaluated it.* It is a structure-aware re-rank, not a real two-list fusion.

#### Why each tool (say "the usual reason is…" and name an alternative)
| Choice | Reason | Alternative (and when better) |
|---|---|---|
| **FastAPI** | Type hints → automatic validation + docs; background tasks; ML libraries are Python | Spring Boot (Java shops), Flask |
| **ChromaDB** | Runs embedded, no extra server, metadata filter by document | pgvector / FAISS / Qdrant at larger scale (not benchmarked) |
| **MiniLM embeddings** | Small, free, runs on CPU, no API key | Hosted/larger model if retrieval quality matters more than cost |
| **3000 / 800 chunking** | Roughly an 800-token chunk with overlap; **chosen by judgement, not tuned** | Tune on a question set |
| **202 + polling + BackgroundTasks** | No extra infrastructure | Celery/Redis queue + server-sent events when jobs must survive restarts |
| **SQLite** | Zero setup | PostgreSQL with many users |
| **Mock LLM provider** | Whole pipeline (even CI) runs without an API key | — |
| **Docker + GitHub Actions** | Same environment everywhere; tests run on every push | — |

**Numbers you may quote (all true):** 9 endpoints under `/api/v1`, 13 section types, 384 dimensions, chunk 3000 / overlap 800, k = 60, boost 1.0–2.0, top_k 1–10 (default 5), temperature 0.2, 4 LLM providers, 3 SQLite tables, 4 backend + 2 frontend tests, 3 CI jobs, 9 commits (6 Mar–13 Aug 2026).

**Real engineering problems you solved (great "challenge" stories, all from your commit history):**
- *Broken-pipe errors* from forked processes inside uvicorn workers → switched multiprocessing to `spawn` and turned off tokenizer parallelism.
- Answer quality: sent the **full chunk text** to the LLM instead of a short snippet.
- Answers were cut off → raised Gemini's output-token limit.
- A configured **Gemini model was retired (404)** → added **model fallback**.
- **CORS** made to accept several origins so the Vercel frontend can call the backend.

#### Weaknesses: say these first, then the fix
1. **No evaluation.** I can't prove StructRAG helps. Fix: 30–50 questions with correct pages; compare **recall@5** and **MRR** with/without the boost.
2. **Not truly multi-turn.** The chat screen shows several questions, but each is sent alone (no history), so "what about its limitations?" fails. Fix: send last N messages, or have the LLM rewrite the follow-up into a standalone question before retrieval.
3. **Not production-ready:** no authentication; ingestion runs inside the web process (a restart mid-job strands it as "processing"); local SQLite/Chroma storage can vanish on redeploy; tests don't cover ranking.
4. Tree is **flat**; regex headings can mistake titles/authors for sections; no keyword/BM25 search; scanned PDFs fail (no OCR); tables/equations lose structure.
5. **UI shows wrong percentage** in boosted mode (scores are tiny rank scores like 0.02, shown as "2%").
6. **Silent fallback**: if the embedding model fails to load, a hash-based fake embedding takes over and retrieval becomes meaningless.
7. LLM errors come back as normal chat text (HTTP 200); global in-memory rate limit.

**Do NOT claim:** multi-turn memory · any accuracy/recall number · "proven", "novel", "patent-pending" · production-ready / scalable / secure · "it is live" (unless you checked today) · "always grounded / no hallucination" · hybrid keyword + vector search · handles scanned PDFs, tables, equations · Redis (the compose file has an unused one).

#### Questions and answers
**Q: What is RAG and why not just ask the LLM?**
"RAG means retrieve first, then generate. The LLM has never seen my PDF, and pasting a whole paper can exceed its context window and cost more. RAG fetches only the relevant passages, so the prompt stays small and I can show source pages. It reduces made-up answers but doesn't remove them."

**Q: Walk me through upload to answer.** → Use steps A and B above in 8–10 sentences.

**Q: Why return 202?**
"Parsing and embedding a paper takes time, so I reply immediately with a job id and process in the background; the browser polls status. The limit is that the task lives in the web process, so a restart can strand a job; a queue like Celery would fix that."

**Q: What is an embedding / how do you compare?** "A vector of numbers that captures meaning; I use cosine similarity, and since my vectors are normalized it's just a dot product."

**Q: Why those chunk sizes?** "I aimed for about 800-token chunks with overlap; I picked the values by judgement and haven't tuned them. I'd test several sizes on a question set and check the embedding model's input limit."

**Q: How do you evaluate it?** "I don't have a quantitative evaluation yet and I won't make up numbers. I'd build a gold set of questions with correct pages and measure recall@5, MRR and groundedness, with and without my section boost."

**Q: Does RAG stop hallucination?** "No. My prompt says answer only from context and say 'I don't know', and temperature is 0.2, but I don't verify the answer against the chunks. I'd measure groundedness on a test set."

**Q: Is it multi-turn (your resume says so)?** "Honestly, it lets you ask several questions in a row, but each question is answered independently with no history, so it isn't multi-turn in the strict sense. I'd add history or rewrite follow-ups into standalone queries."

**Q: How would you scale it?** "Move ingestion to a queue with workers (Celery + Redis), PostgreSQL for metadata, a shared vector DB (Chroma server, pgvector or Qdrant), S3 for PDFs, add authentication with per-user documents and per-user rate limits, and OCR for scanned PDFs."

**Q: Is your demo live?** Say the truth after checking today: "The frontend is on Vercel; my Railway backend was not running when I last checked, so I can show it running locally with Docker."

**Q: Is StructRAG patented / novel?** "No. I haven't filed anything or done a prior-art search. It's an experimental ranking idea. My two patent applications are different projects."

**Your exact part:** solo project, all 9 commits yours. Be ready to open the code and explain any file.

---

### 3.2 CaneGuard: Sugarcane Pest Detection (Team Deepcrop)

> **Resume:** *Developed a multi-modal pest-detection system combining YOLOv8 (image) and TabNet (tabular) models. Served predictions through a REST API backend running in Docker containers; won First Prize at the Department of Biotechnology (DBT)-sponsored Agrithon 2.0 hackathon.*

**30-second version:** "CaneGuard is a sugarcane pest detector we built as Team Deepcrop at a hackathon. A farmer picks Dead Heart or Tiller, uploads a photo and answers 15 yes/no symptom questions. A YOLOv8 model reads the photo, a TabNet model reads the answers, and the backend combines the two scores to say whether that pest is likely. It's a FastAPI service in Docker with a React frontend in four languages. My part was ___." *(fill in)*

**Team:** Hariharan S, Naresh R, Arfath, Yusuf. **Hackathon:** Agrithon at VIT (resume: DBT-sponsored Agrithon 2.0, First Prize). **Keep the certificate handy. Don't add details like prize amounts or number of teams.**

#### The idea in plain words
A sugarcane farmer sees a sick plant and can't tell which pest is damaging it. A **doctor** looks at the patient (the **photo**) and also asks questions (the **15 yes/no answers**), then combines both opinions. CaneGuard does the same: two "experts", one verdict.

#### Words you must know
| Word | Meaning |
|---|---|
| **Pest** | An insect or organism that damages crops. Here: **Dead Heart** (the central shoot of a young plant dies; commonly linked to early shoot borer) and **Tiller** (stunted/abnormal side shoots). |
| **Multi-modal** | Using more than one *kind* of input: here a picture + a table of answers. |
| **YOLOv8** | "You Only Look Once": a fast neural network that finds objects in an image in one pass. |
| **Detection vs segmentation** | Detection draws **boxes** around things. Segmentation draws the **exact outline (mask)**. Dead Heart uses segmentation, Tiller uses detection (per README). |
| **Confidence** | The model's score (0–1) for how sure it is about a detection. |
| **TabNet** | A deep-learning model designed for **tabular** (rows and columns) data; here, one row of 15 answers. |
| **Fusion** | Combining two model outputs into one final score. **Late fusion** = each model decides separately, then you combine. |
| **IoU / NMS** | IoU = overlap area ÷ combined area of two boxes. NMS (non-max suppression) keeps the best box and removes overlapping duplicates. The library does both; I pass `iou=0.45`, `conf=0.25`. |
| **Precision / recall / F1** | Precision = of my "pest" alarms, how many were right. Recall = of the real pests, how many I caught. F1 balances both. |
| **Docker** | Packs the app + everything it needs into one runnable image so it works the same everywhere. |

#### How it works, step by step
1. The farmer picks a **location** (weather panel) → picks the **pest** → uploads **one photo** → answers **15 yes/no questions** (each shows a reference photo).
2. The React app sends one request to `POST /predict/deadheart` or `/predict/tiller` (photo + answers as JSON + language).
3. Backend (class `DiseasePredictor`, models loaded once at start-up):
   - Saves the photo to a temp file and runs **YOLOv8** (conf 0.25, IoU 0.45, size 640).
   - **Image score = the highest detection confidence.**
   - Draws masks/boxes on the photo and returns it as **base64**.
   - Turns the 15 answers into **ones and zeros** (yes = 1) in a fixed order and runs **TabNet** → a probability.
4. **Fusion:** `final = 0.6 × image_score + 0.4 × tabnet_probability`. If **final ≥ 0.5 → pest likely**. (Weights/threshold are environment variables; **never tuned**.)
5. Optional extras: **weather risk** (OpenWeather + hand-written rules, shown separately; it does *not* change the verdict) and **Gemini advice** (4–8 farmer-friendly bullets, no pesticide brands or doses, only if an API key exists).

**Worked fusion examples (memorize 2–3):**
| Image score | TabNet | Final | Result |
|---|---|---|---|
| 0.80 | 0.70 | 0.6×0.80 + 0.4×0.70 = **0.76** | Pest likely |
| 0.30 | 0.40 | 0.18 + 0.16 = **0.34** | Not likely |
| **0.00 (nothing detected)** | 1.00 (all yes) | 0 + 0.40 = **0.40** | **Not likely (the 0.4 ceiling flaw)** |
| 0.25 (weak false hit) | 1.00 | 0.15 + 0.40 = **0.55** | Pest likely |

**Stack:** Python 3.10, FastAPI + Uvicorn, Ultralytics (YOLOv8), PyTorch **CPU-only** (smaller image; free hosts have no GPU), pytorch-tabnet + joblib, OpenCV + Pillow, httpx; React 18 + Vite in **English, Hindi, Tamil, Telugu** (input flow + weather panel); Docker + docker-compose; stateless (no database); about 30 MB of model files in the repo. **7 routes:** `/health`, 4 weather routes, 2 predict routes.

**Why these choices:**
- **Late fusion:** the two models can be built, replaced and debugged separately; you don't need a dataset where every photo has matching answers. Cost: the two scores aren't on the same scale, and the weights are fixed. Better: learn the weights on a validation set (logistic regression) and pick the threshold from a precision-recall curve.
- **YOLOv8:** fast on CPU, one library for detection + segmentation. **TabNet:** the model the team trained; tree models (XGBoost, random forest) are a strong simple alternative for 15 binary features, **I didn't benchmark: don't say TabNet is better.**
- **CPU-only PyTorch + Docker:** small image, works on free hosts.
- **Stateless:** nothing to store (alternative: save confirmed cases to retrain).

#### The hardest bug (your best challenge story)
The Dead Heart **segmentation** model crashed at prediction time with `'Segment' object has no attribute 'detect'`. To find whether the fault was the **model file** or **my app code**, you wrote small scripts (`test_segmentation.py`, `fix_segmentation_model.py`, `fix_model_properly.py`): load the model and predict on a dummy image, read the checkpoint to find which YOLOv8 size it is, try moving the weights into a clean model. The history shows the model file was replaced and **Ultralytics upgraded from 8.0.206 to 8.3.176** right after, and a fallback was added so the API doesn't crash. **How it truly ended = your memory (fill in).** Lesson: test the model in isolation first; pin library versions. *(Don't say the scripts "proved" the cause.)*

#### Weaknesses: say these first, then the fix
1. **No accuracy/precision/recall/F1 anywhere in the repo.** I won't quote a number. Fix: a labelled test set; precision/recall/F1 per pest; compare fusion vs image-only vs questionnaire-only. **Recall matters most** (a missed pest costs more than a false alarm).
2. **The 0.4 ceiling:** if YOLO finds nothing, the image score is 0, so the best possible final score is 0.4, which is below 0.5, so the answer is *always* "no pest", even if the farmer answered yes to everything. Fix: treat "no image evidence" separately: re-weight, or return **"inconclusive"** and ask for a better photo.
3. **Placeholder probabilities** hide failures (TabNet missing → 0.65, error → 0.5).
4. **An API key was committed** in an example file/script (still in git history): rotate it, use placeholders and environment variables, add secret scanning. *(Say "I'd rotate it" unless you did.)*
5. A bad upload returns 500 instead of 400; no authentication, rate limit or size limit; blocking model inference inside `async` routes; not load-tested.
6. One unit test fails (5 pass, 1 fails), no API tests, no CI; weather thresholds have no cited source; result and landing pages are English-only; location is required but not used.

**Do NOT claim:** any accuracy number · "I trained the YOLO/TabNet models" (unless true) · "we tuned the weights" · "TabNet is better than XGBoost" · weather affects the prediction · hosting details you can't prove (Hugging Face, 16 GB, cold start times) · production-ready / secure / authenticated · "works offline" · "fully multilingual" · "handles bad photos" · "I built it alone".

#### Questions and answers
**Q: Walk me through a prediction.** Steps 1–5 above.
**Q: Why combine image and questionnaire? Why 0.6/0.4?** "A photo can be blurry; a checklist depends on what the farmer notices. Two different signals cover each other's weaknesses. The weights are hand-set defaults that never changed since the first commit; I'd fit them on validation data."
**Q: What accuracy did you get?** "I don't have a held-out number in the repo, so I won't quote one. Here's how I'd measure it…" *(precision/recall/F1 plan)*. If you personally know training metrics, say only those and say they are training-time, not end-to-end.
**Q: What if the image model detects nothing?** The 0.4 ceiling answer.
**Q: What's YOLO? IoU? NMS?** See the table above.
**Q: Why TabNet and not XGBoost?** "TabNet was the model the team trained. I didn't benchmark tree models; for 15 binary features XGBoost is a strong simple baseline, and I'd compare them with cross-validation."
**Q: What was your part?** Your 30-second answer (fill in).
**Q: Hardest bug?** The segmentation story.
**Q: Deployment / cold start?** "Containerized with Docker (CPU PyTorch). A cold start is the delay on the first request after the app slept: the container boots, Python imports PyTorch and Ultralytics, and the model files load. A keep-alive ping to `/health` helps." Name the host only if you're sure.
**Q: Security issues?** Committed key; no auth/rate/size limits; `.pt`/`.joblib` files can run code when loaded, so only load trusted ones.
**Q: What is CORS?** "A browser rule: a page can read responses from another site only if that server allows it. FastAPI's CORSMiddleware lists the allowed origins. It protects browsers, not direct callers, so it isn't authentication."
**Q: How would you improve it?** Measure → fix fusion → remove placeholders and fix status codes → Pydantic schemas, API tests, CI → compare with XGBoost, agronomist review → store confirmed cases (with consent) to retrain.
**Q: The prize?** "We won First Prize at the DBT-sponsored Agrithon 2.0 at VIT. I have the certificate." Stop there.

---

### 3.3 WasteZero (Infosys Springboard Virtual Internship 6.0, Feb–Apr 2026)

> **Resume:** *Developed a smart waste pickup and recycling web platform as part of Infosys Springboard's project-based virtual internship.*

**What the internship was:** a **virtual, project-based, mentor-led program** done online with a team. Not an on-site job. **Team size, mentor and your exact modules = your facts (fill in).**

**30-second version:** "WasteZero is a MERN web platform where NGOs post volunteering and recycling-drive opportunities, volunteers apply, and an admin moderates. I worked on it in a team during the Infosys Springboard virtual internship, and my part was ___. The backend is Node, Express and MongoDB with JWT authentication and role-based access; the frontend is React. The core flow of posting, applying and reviewing works end to end."

**Careful!** The project's commit history shows other author names. **Never say "I built the whole platform."** And nothing in it is truly "smart" (no AI/route optimisation): the only "smart" bit is a **"Match" badge** when a volunteer's skills overlap an opportunity's required skills. Safe line: *"My direct contribution was ___. For the rest I studied the code end to end, so I can explain the architecture and the main flows, and I can tell you where I found problems."*

#### MERN in plain words
**M**ongoDB (database of JSON-like documents), **E**xpress (web framework on the server), **R**eact (frontend), **N**ode.js (runs JavaScript on the server). JavaScript + JSON everywhere, so data flows from the database to the screen with little conversion.

*Restaurant analogy:* React = dining room, Express = kitchen (takes orders, checks who you are, cooks), MongoDB = pantry, HTTP+JSON = the waiter.

#### The three roles
- **Volunteer** (default): browse opportunities, apply, see own applications.
- **NGO** (needs a secret code at sign-up): create/edit/delete its own opportunities (with an image), review applicants, accept/reject.
- **Admin** (needs a secret key): see stats, list users, suspend/activate users, review reports.
(The README mentions an "Agent" role that does **not** exist in the code.)

#### Key flows (learn these, they are the standard questions)
**1) Login, from click to dashboard**
1. Login page trims email/password, calls `login()` in AuthContext → `POST /api/auth/login` (cookies enabled).
2. Server finds the user by email (password field explicitly selected), runs **`bcrypt.compare`**.
3. If it matches, it signs a **JWT** `{id, role}` valid for **30 minutes** and sets it as an **httpOnly cookie** (`secure` + `SameSite=None` in production).
4. Client then calls `GET /api/auth/profile`; the **`protect` middleware** verifies the cookie (then a Bearer header as fallback) and returns the user.
5. User is stored in React context; an effect redirects to `/ngo-dashboard`, `/user-dashboard` or `/admin-dashboard` by role.

**2) Apply (and stopping double applications)** `POST /api/applications/:id/apply` → protect + role check → opportunity must be open → **check for existing application (409)** → create (status pending). Three layers stop duplicates: **disabled button in React**, **controller check**, and a **compound unique index** on (opportunity_id, volunteer_id) in MongoDB, the real guarantee even if two clicks race.

**3) OTP login** A 6-digit code is emailed (Nodemailer) and saved in an `Otp` document with `expiresAt = now + 10 min`. On verify the server looks for a record with that email+code where `expiresAt > now`, then **deletes it (single use)**. A **TTL index** lets MongoDB auto-delete expired records (it checks about once a minute, so the query check is what makes expiry exact).

#### Concepts these flows use (explained)
| Concept | Plain words |
|---|---|
| **JWT** | A signed token with three parts (header, payload, signature). The payload holds id + role. Anyone can *read* it; nobody can *change* it without breaking the signature. No server-side session storage needed. Downside: can't be revoked before it expires. |
| **httpOnly cookie** | A cookie JavaScript cannot read, so an XSS attack can't steal the token. Browser sends it automatically. |
| **localStorage** | Browser storage any script can read (less safe for tokens). **Your frontend also keeps a copy of the token here: a weakness.** |
| **bcrypt** | Password hashing: one-way, **salted** (random extra data per password, so same password → different hash), and deliberately slow. Cost factor 10. |
| **Middleware** | A function between the request and the controller `(req, res, next)`; it ends the request or calls `next()`. e.g. `protect` (is the token valid?) then `ngoOnly` (role check) then `multer` (file upload) then the controller. |
| **Authentication vs authorisation** | Who are you? vs what may you do? |
| **Mongoose / populate** | Mongoose = schemas and validation on top of MongoDB. `populate` replaces a stored id with the actual referenced document (like a JOIN). |
| **Index / unique index / TTL index** | An index speeds lookups (like a book index). Unique = no duplicates. TTL = auto-delete after time. |
| **CORS** | Browser rule for cross-site requests; server must allow your frontend's origin (with `credentials: true` for cookies). |
| **CSRF vs XSS** | CSRF: another site makes your browser send your cookie. XSS: attacker's script runs in your page. |
| **Rate limiting** | Limits requests per IP (10/hour on `/api/auth`, 120/min on `/api`, **production only**). |
| **Multer** | Express middleware for file uploads (limit 5 MB; jpeg/png/webp). |

**Why these choices:** MERN = one language, JSON everywhere. **MongoDB, but my data is quite relational (users ↔ opportunities ↔ applications), so PostgreSQL would also fit**, especially for joins, reports and transactions. **JWT** = stateless, scales across servers; cost: can't revoke before expiry, so suspension needs a database check. **httpOnly cookie** over localStorage = safer against XSS; cost: needs CSRF care.

#### What works vs what is broken (be honest and confident about this)
**Works:** public opportunity list/detail; NGO create/edit/delete with an image; volunteer apply and "my applications"; NGO accept/reject through `PATCH /api/applications/:id/status`; admin read views; password register/login/logout.

**Broken or partial (and you know exactly why):**
1. **`req.user.id` vs `req.user._id` (biggest bug):** the `protect` middleware sets only `{id, role}`, but about 38 places in controllers read `req.user._id`. So **chat sending, pickups, profile endpoints, NGO accept on the routed page and admin logging fail** (500) or return empty data. **Fix:** load the user once in `protect` and set `id`, `_id`, `role`, `name`, `isSuspended`.
2. **Suspension isn't enforced:** the flag is set, but `protect` never reads it, and login doesn't check it. A JWT is stateless, so blocking a logged-in user needs a database lookup in `protect`.
3. **Route order bug:** `GET /:id` is declared **before** `/pickups`, `/notifications`, `/statistics`, so Express matches `/:id` first ("Invalid user ID"). Fix: put `/:id` last. This also breaks the volunteer dashboard load.
4. **Token also stored in localStorage**, no refresh token, logout doesn't remove it.
5. **OTP is weak:** `Math.random` (not cryptographic), stored plain-text, no attempt limit; and new-email OTP sign-up fails (password required). Fix: `crypto.randomInt`, hash the code, count attempts.
6. **Production CORS list is localhost-only** (move to an environment variable); **uploads are on local disk** (use cloud storage); admin/NGO guarded by shared secret codes; no CSRF protection; some authorization gaps; global error handler turns some 400s into 500s.
7. **README overstates:** Socket.io real-time chat (chat is plain REST), Agent role, rewards system and live map (static placeholder pages).
8. **No tests, no CI, no start script.**

**Do NOT claim:** "I built the whole platform" · smart/AI/route optimisation · real-time chat or Socket.io · "live in production" · OWASP-secure · "OTP sign-up works" · "suspended users are blocked" · unit tests/CI · cloud image storage.

#### Questions and answers
**Q: Was it an industry internship? Your part?** "It was a virtual, project-based program, Infosys Springboard Internship 6.0, February to April 2026, in a mentor-led team. My part was ___. I also studied the rest so I can explain the whole flow."
**Q: What does MERN mean? How do the parts talk?** "React in the browser sends HTTP requests with JSON to the Express API on Node; middleware checks the user; a controller uses Mongoose to read/write MongoDB and returns JSON."
**Q: What is middleware? Show me one.** "A function that runs between the request and the controller; it either ends the request or calls `next()`. `adminOnly` returns 403 unless the role is admin."
**Q: Why JWT instead of sessions?** "It's stateless, so any server instance can verify it and scaling is easy. The cost is you can't revoke it before expiry, so I'd check the user in `protect` for suspension; sessions in Redis revoke instantly."
**Q: Why an httpOnly cookie not localStorage?** "JavaScript can't read it, so XSS can't steal the token. The trade-off is CSRF, handled with SameSite or a token. I should say our frontend also keeps a fallback copy in localStorage, which weakens it; I'd remove it."
**Q: How do you stop double apply?** The three layers.
**Q: How does OTP expiry work? Is it secure?** Expiry query + TTL index; honest: `Math.random`, plain text, no attempt limit.
**Q: What is REST? PUT vs PATCH? Status codes?** "REST: URLs are resources, the HTTP method is the action. PUT replaces the whole resource; PATCH changes some fields. I used 201 create, 400 bad input, 401 not logged in, 403 not allowed, 404 not found, 409 conflict (duplicate application)."
**Q: How would you make chat real-time?** "Add Socket.io: authenticate the socket with the JWT, put each user in a private room, save the message first then emit it to the receiver's room, and use a Redis adapter so multiple servers share events."
**Q: How would you scale it?** "Stateless API behind a load balancer, uploads to cloud storage, pagination and missing indexes, Redis for rate limiting, queue the email sending."
**Q: What would you improve in another month?** Fix `protect` first (one change repairs many features), then CORS/OTP/localStorage, then tests + CI, then Socket.io and cloud uploads.
**Q: Is it production-ready? Is anything smart?** "No. The core post-apply-review flow works; some secondary features are partly wired because of a user-id bug I found. Nothing is smart in the AI sense; it's a volunteering platform with a skill-match badge."
**Q: What did you learn?** "I came from Java and DSA and was new to MERN. I learned the request flow, JWT/cookies/CORS across two origins, Mongoose, and to review code critically and find real bugs."

---
## 4. "Strong subjects" on your resume: DSA, OOP, DBMS, OS, Networks

> Your resume says these are *strong*, so expect basic-to-medium questions. Answer in the pattern **definition → tiny example → when to use**. Keep answers under 40 seconds.

---

### 4.1 Data Structures & Algorithms (DSA)

**30-second version:** "Data structures are ways to organize data (array, linked list, stack, queue, hash map, tree, graph); algorithms are step-by-step ways to solve problems on them. I judge a solution by its time and space complexity in Big-O."

#### Big-O in plain words
How the work grows when the input size *n* grows. Ignore constants.
| Big-O | Name | Example |
|---|---|---|
| O(1) | Constant | Array index, HashMap get (average) |
| O(log n) | Logarithmic | Binary search |
| O(n) | Linear | Loop once through an array |
| O(n log n) | Linearithmic | Merge sort, heap sort |
| O(n²) | Quadratic | Two nested loops, bubble sort |
| O(2ⁿ) | Exponential | Naive recursive Fibonacci |

*Space complexity* = extra memory used. *Best / average / worst case* = how it behaves on lucky / typical / unlucky inputs.

#### The data structures (what, when, cost)
| Structure | What it is | Strong at | Weak at |
|---|---|---|---|
| **Array** | Items in contiguous memory, accessed by index | Access O(1) | Insert/delete in the middle O(n); fixed size |
| **ArrayList** (Java) | Resizable array | Random access O(1), append O(1) amortized | Middle insert/delete O(n) |
| **Linked list** | Nodes, each pointing to the next (doubly: also previous) | Insert/delete at a known node O(1) | Access/search O(n); extra memory for pointers |
| **Stack** | LIFO (last in, first out): push/pop on top | Undo, brackets matching, recursion, DFS | No random access |
| **Queue** | FIFO (first in, first out): enqueue at rear, dequeue at front | Scheduling, BFS | No random access |
| **Deque / PriorityQueue** | Double-ended queue / heap-based queue giving min or max first | Sliding window / top-K, scheduling | PQ search O(n) |
| **HashMap / HashSet** | Key → value by hashing; set = unique keys | Insert/get/delete **O(1) average** | Unordered; collisions can degrade to O(n) (Java 8 trees buckets to O(log n)) |
| **Binary tree / BST** | Each node has ≤2 children; BST: left < node < right | Search/insert O(log n) if balanced | Unbalanced tree degrades to O(n) |
| **Heap** | Complete binary tree where parent ≥ (max-heap) or ≤ (min-heap) children | Get min/max O(1), insert O(log n) | Not good for arbitrary search |
| **Graph** | Nodes (vertices) + edges; stored as adjacency list/matrix | Networks, maps, dependencies | More complex algorithms |

**Array vs linked list (most-asked):** array = fast access by index, slow insert/delete in the middle, contiguous memory; linked list = fast insert/delete, slow access, extra pointer memory.
**Stack vs queue:** LIFO vs FIFO. Real life: stack of plates vs queue at a ticket counter.
**HashMap internally:** an array of "buckets"; key's `hashCode()` decides the bucket; collisions chain in a linked list (tree after 8 items in Java 8+); default load factor 0.75 → resize (doubling) when 75% full.

#### Core algorithms
- **Searching:** linear O(n); **binary search O(log n)** on a *sorted* array (halve the range each step).
- **Sorting:**
| Algorithm | Best | Average | Worst | Space | Notes |
|---|---|---|---|---|---|
| Bubble / Selection / Insertion | O(n) (bubble opt., insertion) / O(n²) | O(n²) | O(n²) | O(1) | Simple; insertion good for small/nearly sorted |
| **Merge sort** | O(n log n) | O(n log n) | O(n log n) | O(n) | Stable, divide & conquer |
| **Quick sort** | O(n log n) | O(n log n) | O(n²) | O(log n) | Fast in practice; bad pivot → worst case |
| Heap sort | O(n log n) | O(n log n) | O(n log n) | O(1) | Not stable |
- **Recursion:** a function calling itself with a smaller problem + a **base case**. Danger: no base case → stack overflow.
- **BFS vs DFS (graphs/trees):** BFS explores level by level using a **queue** (shortest path in unweighted graphs). DFS goes deep first using a **stack/recursion**. Both O(V+E).
- **Tree traversals:** inorder (left, node, right: gives sorted order for a BST), preorder (node, left, right), postorder (left, right, node), level-order (BFS).
- **Dynamic programming (DP):** break a problem into overlapping subproblems and store results (memoization/tabulation), e.g. Fibonacci in O(n) instead of O(2ⁿ).
- **Two pointers / sliding window / hashing:** common tricks to turn O(n²) into O(n).
- **Greedy vs DP:** greedy picks the best local choice (e.g. coin change with standard coins); DP checks all subproblems.

#### Classic interview coding questions (Java), practise typing these once
*State approach and complexity first, then code, then test with one example.*

**1. Reverse a string**: O(n)
```java
String rev = new StringBuilder(s).reverse().toString();
```

**2. Palindrome check**: two pointers, O(n)
```java
boolean isPalin(String s){
  int i=0,j=s.length()-1;
  while(i<j){ if(s.charAt(i++)!=s.charAt(j--)) return false; }
  return true;
}
```

**3. First non-repeating character**: count with a LinkedHashMap (keeps insertion order), O(n)
```java
char firstUnique(String s){
  Map<Character,Integer> m = new LinkedHashMap<>();
  for(char c: s.toCharArray()) m.put(c, m.getOrDefault(c,0)+1);
  for(var e: m.entrySet()) if(e.getValue()==1) return e.getKey();
  return '_'; // none
}
```

**4. Two sum**: HashMap of value→index, O(n) time, O(n) space (brute force is O(n²))
```java
int[] twoSum(int[] a, int target){
  Map<Integer,Integer> seen = new HashMap<>();
  for(int i=0;i<a.length;i++){
    int need = target - a[i];
    if(seen.containsKey(need)) return new int[]{seen.get(need), i};
    seen.put(a[i], i);
  }
  return new int[]{};
}
```

**5. Valid parentheses**: stack, O(n)
```java
boolean valid(String s){
  Deque<Character> st = new ArrayDeque<>();
  for(char c: s.toCharArray()){
    if("([{".indexOf(c)>=0) st.push(c);
    else {
      if(st.isEmpty()) return false;
      char o = st.pop();
      if((c==')'&&o!='(')||(c==']'&&o!='[')||(c=='}'&&o!='{')) return false;
    }
  }
  return st.isEmpty();
}
```

**6. Reverse a linked list**: three pointers, O(n), O(1) space
```java
Node reverse(Node head){
  Node prev=null, cur=head;
  while(cur!=null){ Node next=cur.next; cur.next=prev; prev=cur; cur=next; }
  return prev;
}
```

**7. Detect a cycle in a linked list**: Floyd's slow/fast pointers, O(n), O(1) space
```java
boolean hasCycle(Node head){
  Node slow=head, fast=head;
  while(fast!=null && fast.next!=null){
    slow=slow.next; fast=fast.next.next;
    if(slow==fast) return true;
  }
  return false;
}
```

**8. Binary search**: O(log n)
```java
int bs(int[] a, int x){
  int lo=0, hi=a.length-1;
  while(lo<=hi){
    int mid = lo + (hi-lo)/2;           // avoids overflow
    if(a[mid]==x) return mid;
    else if(a[mid]<x) lo=mid+1; else hi=mid-1;
  }
  return -1;
}
```

**9. Implement a queue using two stacks**: amortized O(1)
```java
class MyQueue {
  Deque<Integer> in=new ArrayDeque<>(), out=new ArrayDeque<>();
  void enqueue(int x){ in.push(x); }
  int dequeue(){ if(out.isEmpty()) while(!in.isEmpty()) out.push(in.pop()); return out.pop(); }
}
```

**10. Kth largest element**: min-heap of size k, O(n log k)
```java
int kthLargest(int[] a, int k){
  PriorityQueue<Integer> pq = new PriorityQueue<>();
  for(int x: a){ pq.add(x); if(pq.size()>k) pq.poll(); }
  return pq.peek();
}
```

**11. Fibonacci with DP**: O(n) time, O(1) space
```java
int fib(int n){ if(n<2) return n; int a=0,b=1; for(int i=2;i<=n;i++){ int c=a+b; a=b; b=c; } return b; }
```

**12. BFS on a graph (adjacency list)**: O(V+E)
```java
void bfs(Map<Integer,List<Integer>> g, int start){
  Set<Integer> vis = new HashSet<>(); Queue<Integer> q = new LinkedList<>();
  q.add(start); vis.add(start);
  while(!q.isEmpty()){
    int u=q.poll(); System.out.print(u+" ");
    for(int v: g.getOrDefault(u, List.of())) if(vis.add(v)) q.add(v);
  }
}
```

**13. Find duplicates / check anagram** (idea): use a HashSet (seen-before check) or a count array of 26 letters / sort both strings.

**Real-life example of DSA (they ask this!):** "BFS with a queue finds the shortest route in a map/network; a stack gives the browser's back button; a HashMap gives instant lookups (e.g. user by email); a min-heap picks the next task by priority."

#### DSA questions and short answers
- **Array vs linked list?** (above)
- **Stack vs queue?** LIFO vs FIFO, uses above.
- **Why is HashMap lookup O(1)?** Hashing jumps straight to the bucket; collisions are few if the hash spreads keys well.
- **Difference between a doubly and a circular linked list?** Doubly: each node has next *and* previous. Circular: the last node points back to the first (no null end).
- **Binary search requirement?** The array must be sorted.
- **Which sort is best?** Depends: merge sort for guaranteed O(n log n)/stability; quick sort is fastest on average; insertion for tiny/nearly-sorted data.
- **What is recursion? Risk?** Function calls itself; needs a base case; deep recursion → stack overflow.
- **Rate yourself in DSA.** "About 7/10: I'm comfortable with arrays, strings, hashing, stacks/queues, linked lists, trees and BFS/DFS; I'm still improving on advanced DP and graph problems." *(Honest, not 10/10.)*

---

### 4.2 Object-Oriented Programming (OOP), with Java

**30-second version:** "OOP models software as objects that combine data and behaviour. Its four pillars are encapsulation, abstraction, inheritance and polymorphism."

#### Class and object
A **class** is the blueprint (e.g. `Car` with fields `color`, `speed` and methods `drive()`). An **object** is one real instance of it (`new Car()`). A **constructor** initializes the object when created.

#### The four pillars (with a real-life example each)
| Pillar | Meaning | Real-life example | Java |
|---|---|---|---|
| **Encapsulation** | Bundle data + methods together and hide the data; access only via methods | A capsule/medicine; ATM: you can't touch the cash directly | `private` fields + public getters/setters |
| **Abstraction** | Show *what* it does, hide *how* | Driving a car: pedals/steering, not the engine internals | `abstract` classes, `interface` |
| **Inheritance** | A child class reuses and extends a parent class | `Dog` and `Cat` extend `Animal` | `class Dog extends Animal` |
| **Polymorphism** | One name, many forms | `draw()` behaves differently for `Circle` and `Square` | Overloading (compile-time), overriding (runtime) |

```java
abstract class Shape { abstract double area(); }
class Circle extends Shape { double r; Circle(double r){this.r=r;} double area(){ return Math.PI*r*r; } }
class Rect extends Shape { double w,h; Rect(double w,double h){this.w=w;this.h=h;} double area(){ return w*h; } }
Shape s = new Circle(2);        // reference of parent type
System.out.println(s.area());   // calls Circle's area at runtime = runtime polymorphism
```

#### The questions that come up again and again
- **Overloading vs overriding:** *Overloading* = same method name, **different parameters**, same class, decided at **compile time**. *Overriding* = child class gives its own version of a parent method with the **same signature**, decided at **runtime**.
- **Abstract class vs interface:** abstract class can have fields, constructors and both implemented/unimplemented methods; a class can extend only **one**. An interface defines a contract (methods, constants; Java 8+ also `default`/`static` methods); a class can **implement many**. Use an abstract class for "is-a with shared state/code", an interface for "can-do" capability.
- **Does Java support multiple inheritance?** Not with classes (diamond problem), but yes through interfaces.
- **`this` vs `super`:** `this` = current object; `super` = parent class (constructor/method).
- **`static`:** belongs to the class, not an object (shared). **`final`:** variable can't change, method can't be overridden, class can't be extended.
- **Access modifiers:** `private` (same class), default/package-private (same package), `protected` (package + subclasses), `public` (everywhere). *Real-life private vs protected:* private = your own diary; protected = family can read it.
- **Constructor vs method:** constructor has the class name, no return type, runs on object creation.
- **Data abstraction vs encapsulation:** abstraction = hiding complexity (design level); encapsulation = hiding data and protecting it with access control (implementation level).
- **Composition vs inheritance:** "has-a" vs "is-a"; prefer composition when you can.
- **SOLID (know the names):** Single responsibility, Open/closed, Liskov substitution, Interface segregation, Dependency inversion.

#### Java essentials interviewers like
- **JDK / JRE / JVM:** JVM runs bytecode; JRE = JVM + libraries; JDK = JRE + compiler/tools. Java is "write once, run anywhere" because source → bytecode → any JVM.
- **String is immutable** (stored in the String pool); use `StringBuilder` for lots of changes. **`==` vs `equals()`:** `==` compares references; `equals()` compares contents.
- **ArrayList vs LinkedList:** ArrayList = fast random access; LinkedList = fast insert/delete at ends/known node.
- **HashMap vs HashSet vs TreeMap:** key-value; unique values; sorted by key.
- **Exceptions:** *checked* (must handle, e.g. `IOException`) vs *unchecked* (`RuntimeException`, e.g. `NullPointerException`); `try/catch/finally`.
- **Garbage collection:** the JVM automatically frees memory of unreachable objects.
- **Multithreading:** `Thread`/`Runnable`; `synchronized` stops two threads corrupting shared data.
- **Java vs Python:** Java is statically typed, compiled to bytecode, faster, verbose; Python is dynamically typed, interpreted, concise, popular for AI. (You use both.)

---
### 4.3 DBMS (Databases) and SQL

**30-second version:** "A DBMS stores, organizes and retrieves data. A relational DBMS stores it in tables with rows and columns, linked by keys, and I query it with SQL."

#### The basics
- **DBMS** = software to manage a database (MySQL, PostgreSQL, MongoDB). **RDBMS** = relational DBMS: data in **tables** (relations) with **keys** and relationships. All RDBMS are DBMS, not all DBMS are relational (MongoDB stores documents).
- **Keys:** 
  - **Primary key**: uniquely identifies a row; not null; one per table.
  - **Foreign key**: a column that references another table's primary key (creates relationships and enforces integrity).
  - **Candidate key**: any column(s) that *could* be the primary key. **Super key**: any set that uniquely identifies a row. **Composite key**: primary key made of 2+ columns. **Unique key**: unique but may allow one NULL.
- **Normalization** = organizing tables to reduce duplication and anomalies.
  - **1NF**: each cell holds one atomic value (no lists in a cell), rows unique.
  - **2NF**: 1NF + no *partial dependency* (a non-key column depending on only part of a composite key).
  - **3NF**: 2NF + no *transitive dependency* (non-key column depending on another non-key column).
  - **BCNF**: stricter 3NF (every determinant is a candidate key).
  - *Trade-off:* more normalization = less duplication but more JOINs (slower reads); **denormalization** speeds reads.
- **ACID (transactions):** **A**tomicity (all or nothing), **C**onsistency (data stays valid), **I**solation (concurrent transactions don't interfere), **D**urability (committed data survives crashes). Example: bank transfer, debit and credit both happen or neither.
- **Transaction** = a group of operations treated as one unit (`BEGIN … COMMIT / ROLLBACK`).
- **Index** = an extra structure (usually a B-tree) that makes searching fast, like a book index. Speeds `SELECT`, slows `INSERT/UPDATE` slightly and uses space.
- **SQL vs NoSQL (e.g. MongoDB):** SQL = fixed schema, tables, joins, strong ACID, good for relational data. NoSQL = flexible documents, scales horizontally, good for changing or hierarchical data. *Your answer:* "I used MongoDB in WasteZero for flexible documents, but my data was relational, so PostgreSQL would also fit."
- **DELETE vs TRUNCATE vs DROP:** DELETE removes rows (can have WHERE, can roll back); TRUNCATE removes all rows quickly, keeps the table; DROP removes the whole table.
- **WHERE vs HAVING:** WHERE filters rows *before* grouping; HAVING filters groups *after* `GROUP BY`.
- **Views** = saved queries acting as virtual tables. **Stored procedure** = saved SQL code you can call. **Trigger** = code that runs automatically on an event (insert/update/delete).
- **Isolation problems:** dirty read, non-repeatable read, phantom read (higher isolation levels prevent more).
- **Deadlock (DB):** two transactions each wait for a lock the other holds; the DBMS aborts one.

#### SQL JOINs, with a tiny example
`Employees(id, name, dept_id)` and `Departments(id, dept_name)`.
| Join | Returns |
|---|---|
| **INNER JOIN** | Only rows that match in both tables |
| **LEFT JOIN** | All rows from the left table + matching right rows (NULL if none) |
| **RIGHT JOIN** | All rows from the right table + matching left rows |
| **FULL OUTER JOIN** | All rows from both; NULL where no match |
| **CROSS JOIN** | Every combination (m × n rows) |
| **SELF JOIN** | A table joined with itself (e.g. employee → manager) |
```sql
SELECT e.name, d.dept_name
FROM Employees e
INNER JOIN Departments d ON e.dept_id = d.id;
```

#### SQL queries you should be able to write
```sql
-- Highest salary
SELECT MAX(salary) FROM Employee;

-- Second highest salary (classic)
SELECT MAX(salary) FROM Employee
WHERE salary < (SELECT MAX(salary) FROM Employee);
-- or:  SELECT DISTINCT salary FROM Employee ORDER BY salary DESC LIMIT 1 OFFSET 1;

-- Count employees per department, only departments with more than 5
SELECT dept_id, COUNT(*) AS cnt
FROM Employee
GROUP BY dept_id
HAVING COUNT(*) > 5;

-- Find duplicate emails
SELECT email, COUNT(*) FROM Users GROUP BY email HAVING COUNT(*) > 1;

-- Top 3 salaries
SELECT * FROM Employee ORDER BY salary DESC LIMIT 3;

-- Employees with no department (LEFT JOIN + NULL check)
SELECT e.name FROM Employee e LEFT JOIN Department d ON e.dept_id = d.id WHERE d.id IS NULL;
```
Also know: `COALESCE(a, b)` returns the first non-NULL; `NULL` never equals anything (use `IS NULL`); `COUNT(*)` counts rows, `COUNT(col)` ignores NULLs; aggregate functions: `COUNT, SUM, AVG, MIN, MAX`.

---

### 4.4 Operating Systems (OS)

**30-second version:** "An OS manages hardware and gives programs a safe, fair way to use it. It handles processes, memory, files and devices."

- **Main jobs:** process management, CPU scheduling, memory management, file system, I/O/device management, security.
- **Kernel** = core of the OS. **User mode vs kernel mode:** user programs run with limited power; they ask the kernel to do privileged work through **system calls** (e.g. read a file).
- **Process vs thread**
  - **Process** = a running program with its own memory space (code, data, heap, stack). Heavy to create; processes are isolated.
  - **Thread** = a lightweight unit of execution *inside* a process; threads share the process's memory (heap, code) but have their own stack/registers. Faster to create/switch; but sharing memory causes **race conditions**.
  - *Example:* a browser = process; each tab or the UI/network tasks = threads.
- **Process states:** New → Ready → Running → Waiting (blocked) → Terminated. **PCB** (Process Control Block) stores a process's info (state, registers, program counter). **Context switch** = saving one process's state and loading another's (costs time).
- **CPU scheduling algorithms:** 
  - **FCFS** (first come first served): simple; long jobs delay short ones (convoy effect).
  - **SJF** (shortest job first): smallest average wait; needs to know job length; can starve long jobs.
  - **Round Robin**: each process gets a fixed **time quantum**, then goes to the back of the queue; fair, good for interactive systems.
  - **Priority scheduling**: highest priority first; **starvation** possible, fixed by **aging**.
  - *Example (Round Robin, quantum 2):* P1(5), P2(3), P3(1) → P1 runs 2, P2 runs 2, P3 runs 1 (finishes), P1 2, P2 1 (finishes), P1 1 (finishes).
- **Deadlock**: processes wait forever for each other's resources. **Four necessary conditions (all must hold):** 1) **Mutual exclusion**, 2) **Hold and wait**, 3) **No preemption**, 4) **Circular wait**. *Real-life:* two cars on a narrow bridge facing each other. **Handling:** prevention (break one condition), avoidance (Banker's algorithm), detection and recovery, or ignore (ostrich).
- **Race condition / critical section:** several threads change shared data at once and the result depends on timing. The **critical section** is the code touching shared data; protect it with a **mutex/lock** or **semaphore**.
- **Mutex vs semaphore:** mutex = a lock with an owner (one thread at a time, only the owner unlocks). Semaphore = a counter allowing N concurrent accesses (binary semaphore ≈ mutex but no ownership); used for signaling.
- **Memory management:**
  - **Paging:** memory divided into fixed-size **frames**; processes into **pages**; a page table maps pages to frames. No external fragmentation (some internal).
  - **Segmentation:** memory divided into variable-size logical **segments** (code, stack, heap); can have external fragmentation.
  - **Virtual memory:** programs can use more memory than physical RAM by keeping some pages on disk; a **page fault** happens when a needed page isn't in RAM (OS loads it).
  - **Page replacement:** FIFO, **LRU** (replace the least recently used), Optimal. FIFO can show **Belady's anomaly** (more frames → more faults).
  - **Thrashing:** the system spends more time swapping pages than executing; caused by too little memory for too many processes.
  - **Fragmentation:** internal (wasted space inside an allocated block) vs external (free space broken into small pieces).
- **Interprocess communication (IPC):** pipes, message queues, shared memory, sockets.
- **Multitasking vs multiprocessing vs multithreading:** many tasks switching on one CPU; many CPUs; many threads in one process.

---

### 4.5 Computer Networks (TCP/IP, HTTP/HTTPS)

**30-second version:** "A network lets devices exchange data. The Internet works in layers: each layer does one job, so applications like a browser don't worry about cables or routing."

#### OSI (7 layers) vs TCP/IP (4 layers)
| OSI layer | What it does | Unit (PDU) | Example / device |
|---|---|---|---|
| 7 Application | User-facing protocols | Data | HTTP, HTTPS, FTP, SMTP, DNS |
| 6 Presentation | Format, encryption, compression | Data | TLS/SSL, JPEG |
| 5 Session | Start/keep/end sessions | Data | |
| 4 Transport | End-to-end delivery, ports | Segment | **TCP, UDP** |
| 3 Network | Addressing and routing | Packet | **IP, router** |
| 2 Data Link | Delivery between neighbouring devices, MAC addresses | Frame | **Switch**, Ethernet, Wi-Fi |
| 1 Physical | Bits on the wire/air | Bits | Cables, hubs |

*TCP/IP model:* **Application** (HTTP, DNS…) → **Transport** (TCP/UDP) → **Internet** (IP) → **Link** (Ethernet/Wi-Fi). Memory trick for OSI (7→1): "All People Seem To Need Data Processing" (Application, Presentation, Session, Transport, Network, Data link, Physical).

**Hub vs switch vs router:** hub = repeats data to all ports (dumb, L1); switch = sends to the right device by MAC address (L2); router = connects different networks and routes by IP (L3).

#### TCP vs UDP (very common)
| | **TCP** | **UDP** |
|---|---|---|
| Connection | Connection-oriented (handshake first) | Connectionless |
| Reliability | Reliable: acknowledgements, retransmission, ordered | No guarantee, may lose/reorder |
| Speed | Slower (more overhead) | Faster, lightweight |
| Use | Web (HTTP/HTTPS), email, file transfer | DNS, video/voice calls, online games, streaming |
*Analogy:* TCP = registered post with delivery confirmation; UDP = dropping postcards in a letterbox.
**TCP three-way handshake:** client sends **SYN** → server replies **SYN-ACK** → client sends **ACK** → connection established. (Closing uses FIN/ACK.) TCP also has **flow control** (don't overwhelm the receiver) and **congestion control**.

#### HTTP and HTTPS
- **HTTP** = HyperText Transfer Protocol, the request/response protocol of the web (port **80**). It is **stateless** (each request is independent; cookies/sessions/JWT add state). **HTTPS** = HTTP over **TLS** (port **443**): encrypts data, proves the server's identity with a **certificate**, and protects integrity.
- **How HTTPS works (simple):** browser connects → server sends its **certificate** (public key, signed by a trusted CA) → they agree on a **symmetric session key** using asymmetric cryptography → all data is encrypted with the fast symmetric key. (Asymmetric = public/private key pair; symmetric = one shared key.)
- **Methods:** GET (read), POST (create), PUT (replace), PATCH (partial update), DELETE. **GET vs POST:** GET puts parameters in the URL, is idempotent and cacheable, for reading; POST puts data in the body, not idempotent, for creating/sending.
- **Status codes:** 1xx info, **2xx success** (200 OK, 201 Created, 204 No Content), **3xx redirect** (301 permanent, 302 temporary), **4xx client error** (400 bad request, 401 unauthenticated, 403 forbidden, 404 not found, 409 conflict, 429 too many requests), **5xx server error** (500, 502, 503).
- **Cookies vs sessions vs JWT:** cookie = small data stored in the browser; session = server remembers you (cookie holds a session id); JWT = a signed token you carry (server remembers nothing).

#### Other must-know items
- **IP address:** IPv4 = 32-bit (e.g. 192.168.1.1), IPv6 = 128-bit. **Public vs private IP** (private ranges like 192.168.x.x, 10.x.x.x). **NAT** lets many private devices share one public IP.
- **Subnet mask** splits an IP into network and host parts (e.g. /24 = 255.255.255.0 = 254 usable hosts).
- **DNS** = the internet's phonebook: turns `www.example.com` into an IP address. **DHCP** = automatically gives devices IP addresses. **ARP** = finds a MAC address from an IP on a local network.
- **Port** = a number identifying an application on a machine (80 HTTP, 443 HTTPS, 22 SSH, 25 SMTP, 53 DNS, 3306 MySQL).
- **Firewall** = filters traffic by rules. **Proxy / load balancer / CDN** = middlemen that forward, balance, or cache content closer to users.
- **Latency vs bandwidth:** delay for one message vs how much data per second.
- **LAN / WAN / MAN:** local / wide / metropolitan networks.

**"What happens when you type a URL and press Enter?" (tell this story in order):**
1. The browser checks its cache, then **DNS** turns the domain into an IP address.
2. It opens a **TCP connection** (three-way handshake) to that IP on port 443.
3. For HTTPS, a **TLS handshake** sets up encryption using the server's certificate.
4. The browser sends an **HTTP GET request**.
5. The server (maybe behind a load balancer) processes it and returns an **HTTP response** (status + HTML).
6. The browser renders the HTML, then fetches CSS/JS/images (more requests), and builds the page.

*(Link it to your work: in WasteZero, my React app on one origin calls the Express API on another, which is why CORS and cookie settings mattered.)*

---
## 5. Technical skills, one by one

> Rule: for every skill on your resume, be ready with **(a) what it is, (b) where you used it, (c) one thing you know about it.** Anything you can't explain, don't claim.

| Skill | Where you used it |
|---|---|
| Java | DSA practice, OOP, coursework |
| Python | FastAPI backends (RAG, CaneGuard), ML, Learning Unlimited (Django) PRs |
| SQL | Coursework; SQLite in RAG; know joins/GROUP BY |
| HTML, CSS, JavaScript | Frontends (React/TypeScript projects); Zulip TypeScript fix |
| REST APIs | All three projects |
| Node.js (learning) | WasteZero (Express) |
| Scikit-learn, RAG pipelines, LLM integration | RAG project (RAG, LLM); **Scikit-learn: see careful note below** |
| Docker (basics), Git, GitHub, Vercel | RAG + CaneGuard (Docker), all repos (Git/GitHub), RAG frontend (Vercel) |

---

### 5.1 Java, Python, SQL (languages)
- **Java:** statically typed, compiled to bytecode, runs on the JVM. Strong OOP, huge enterprise use (Accenture projects often use it). *Where:* DSA, OOP.
- **Python:** dynamically typed, interpreted, short code, huge AI/data ecosystem. *Where:* FastAPI services, ML. Know: lists, dicts, tuples, sets; list vs tuple (mutable vs immutable); decorators; virtual environments; `pip`.
- **SQL:** language to query relational databases (section 4.3).
- **If asked "which is your best language?"** → "Java for DSA and OOP; Python for building APIs and AI projects."

### 5.2 HTML, CSS, JavaScript (and React, since your projects use it)
- **HTML** = structure of a page (headings, forms, links). **CSS** = styling (colors, layout: Flexbox/Grid). **JavaScript** = behaviour (clicks, fetching data).
- *In a nutshell:* HTML is the skeleton, CSS is the clothes, JavaScript is the muscles.
- **JS basics:** `var` vs `let` vs `const` (function-scoped vs block-scoped vs block-scoped and not reassignable); `==` (loose, converts types) vs `===` (strict); **DOM** = the page as a tree of objects JS can change; **Promises / async-await** = handling slow tasks (like network calls) without freezing; **event loop** = how JS does many things on one thread; arrow functions; closures.
- **React:** a JavaScript library for building UIs from **components**. **Props** = inputs to a component; **state** = data that changes (`useState`); **`useEffect`** = run code after render (like fetching data); **Virtual DOM** = React updates only what changed; **Context API** = share data (like logged-in user) without passing props down every level; **React Router** = pages/URLs. **TypeScript** = JavaScript + types (catches mistakes early). **Vite** = fast build/dev tool. **Tailwind** = utility CSS classes.
- *Your uses:* React + TypeScript + Vite + Tailwind in StructRAG; React + Vite in CaneGuard (4-language UI with a small Context-based translation helper); React 19 in WasteZero; a TypeScript fix in Zulip.

### 5.3 REST APIs
- **API** = a contract that lets one program use another. **REST** = style where URLs name **resources** and HTTP methods are the **actions**; data usually **JSON**; **stateless** (each request carries what the server needs).
- Example: `GET /api/opportunities` (list), `POST /api/opportunities` (create), `PATCH /api/applications/:id/status` (update status), `DELETE /api/opportunities/:id`.
- **PUT vs PATCH:** PUT replaces the whole resource; PATCH changes part. **Idempotent** = repeating the call gives the same final state (GET, PUT, DELETE are; POST isn't).
- **Status codes you used:** 200, 201, 202 (accepted; async work), 400, 401, 403, 404, 409, 429, 500.
- **Auth for APIs:** API keys, **JWT**, sessions/cookies, OAuth (log in with Google). **CORS**, **rate limiting**, **validation** (Pydantic in FastAPI; schemas in Mongoose) are the usual protections.
- **API versioning:** `/api/v1/...` so breaking changes go to `/v2`.
- *Your uses:* FastAPI (RAG: 9 endpoints; CaneGuard: 7 routes), Express (WasteZero: 9 route files).

### 5.4 Node.js (learning)
- **Node.js** = runs JavaScript on the server using Chrome's V8 engine. **Non-blocking, event-driven:** one thread handles many connections by not waiting on slow I/O (files, DB, network). Great for I/O-heavy apps (APIs, chat), not for heavy CPU work.
- **npm** = package manager. **Express** = minimal web framework (routes + middleware). **`async/await`** = readable asynchronous code.
- **Express request flow (WasteZero):** request → helmet → cors → body parser → cookie parser → rate limiter → route → middleware (`protect`, role) → controller → Mongoose → response.
- **Say:** "I'm still learning Node; I used it with Express and MongoDB in WasteZero and I understand middleware, routing, JWT auth and async handling."

### 5.5 Scikit-learn, ML basics and **a careful note**
- **Machine learning** = programs that learn patterns from data instead of being hand-coded.
  - **Supervised** (labelled data): *classification* (is it spam? pest/no pest) and *regression* (predict a number). **Unsupervised:** *clustering* (group similar items), dimensionality reduction. **Reinforcement:** learn by reward.
  - **Workflow:** collect data → clean → split into **train / validation / test** → train → evaluate → tune → deploy.
  - **Overfitting** = memorizes training data, fails on new data; **underfitting** = too simple. Fix with more data, regularization, simpler/other model, **cross-validation**.
  - **Metrics:** accuracy = (TP+TN)/all; **precision** = TP/(TP+FP); **recall** = TP/(TP+FN); **F1** = 2·P·R/(P+R); **confusion matrix** shows TP, FP, FN, TN. Accuracy misleads with imbalanced classes.
  - **Common algorithms:** linear/logistic regression, decision tree, random forest, k-NN, SVM, k-means, naive Bayes.
- **Scikit-learn** = Python library with ready-made ML algorithms, preprocessing, `train_test_split`, metrics and pipelines.
- **Careful:** in the CaneGuard code, scikit-learn is listed in `requirements.txt` but **never imported**. So **don't say you used scikit-learn in CaneGuard.** Be ready to say *where* you really used it (coursework / practice projects): `___` *(fill in tonight)*. If you can't, say "I know the basics, e.g. train/test split, logistic regression and metrics, from coursework and practice."
- **Deep learning basics (for YOLO/TabNet):** neural networks = layers of connected "neurons" that learn weights; **CNN** (convolutional) is used for images (YOLO); **LSTM** is a neural network for sequences (used in your PINN patent).

### 5.6 RAG pipelines and LLM integration (your strongest modern skill)
- **LLM** = model trained on huge text that predicts the next token. Not a database of facts; can **hallucinate**.
- **Prompt engineering** = giving clear instructions, context and format (e.g. "answer only from the context; say *I don't know* otherwise").
- **RAG** vs **fine-tuning:** RAG fetches fresh/private knowledge at question time (cheaper, updatable, shows sources). Fine-tuning changes the model's weights (good for style/skills, not great for fast-changing facts).
- **RAG pipeline:** *ingest* (parse → chunk → embed → store in a vector DB) + *query* (embed question → retrieve nearest chunks → optional re-rank → build prompt → LLM answer + citations).
- **Evaluate RAG:** retrieval (recall@k, MRR) and answer (faithfulness/groundedness, relevance).
- **LLM integration** = calling LLM APIs (OpenAI, Gemini, Hugging Face) from your backend: handle **keys (env variables), retries, rate limits, fallbacks, errors, cost/latency**. You built a provider layer with a mock for tests, Gemini model fallback, and retries.
- **Risks to mention:** hallucination; **prompt injection** (malicious text in the document telling the model what to do); privacy (don't send sensitive data to third-party APIs without consent); cost.
- **Agents** (if asked): an LLM that can call tools and decide steps. You didn't build one; don't claim it.

### 5.7 Docker (basics)
- **Docker** packages an app with its dependencies so it runs the same everywhere ("works on my machine" solved).
- **Image** = read-only blueprint; **container** = a running instance of an image. **Dockerfile** = recipe (`FROM`, `COPY`, `RUN`, `CMD`). **Docker Compose** = run several containers together (RAG: backend + Chroma + frontend). **Volume** = storage that survives container restarts. **Port mapping** = connect container port to your machine.
- **Container vs VM:** containers share the host OS kernel, so they're lighter/faster; VMs include a full guest OS.
- *Your uses:* RAG Dockerfile (Python 3.11 slim, gunicorn + uvicorn) + Compose; CaneGuard Dockerfile (Python 3.10 slim, CPU-only PyTorch to keep the image small).
- **Honest scope:** "basics": you can write a Dockerfile and a Compose file; you haven't run Kubernetes.

### 5.8 Git and GitHub
- **Git** = version control (history of changes, branches). **GitHub** = hosting + collaboration (pull requests, issues, Actions).
- **Commands:** `clone`, `status`, `add`, `commit`, `push`, `pull`, `branch`, `checkout/switch`, `merge`, `rebase`, `stash`, `log`, `diff`.
- **Workflow:** create a branch → commit → push → open a **pull request (PR)** → review → merge. **Fork** = your own copy of someone else's repo (how you contributed to Zulip/Learning Unlimited).
- **Merge vs rebase:** merge keeps history with a merge commit; rebase replays your commits on top of another branch for a linear history. **Merge conflict** = two changes to the same lines; you resolve manually.
- **`git revert` vs `git reset`:** revert adds a new commit that undoes a change (safe for shared branches); reset moves the branch pointer (rewrites history).
- **GitHub Actions** = CI/CD automation; your RAG project runs tests, lint and Docker builds on every push.
- **Good habit:** meaningful commit messages and never commit secrets (`.env`, API keys). *(You found a committed key in CaneGuard: mention it as a lesson.)*

### 5.9 Vercel
- A platform to **deploy frontends** (React/Next.js) from GitHub with automatic builds and a public URL; supports **environment variables** (e.g. `VITE_API_BASE_URL`) and serverless functions. Your RAG frontend runs there; the backend was configured for **Railway** (a platform that builds Docker/Python backends).

---

## 5b. Certifications

### AWS Certified Cloud Practitioner (CLF-C02/C01 level, foundational)
**30-second version:** "It validates foundational AWS cloud knowledge: what the cloud is, core services, security, pricing and support."
- **Cloud computing** = renting computing (servers, storage, databases) over the internet, pay-as-you-go, instead of owning data centres.
- **Service models:** **IaaS** (rent servers: EC2), **PaaS** (platform to run code: Elastic Beanstalk), **SaaS** (finished software: Gmail). **Deployment models:** public, private, **hybrid** (mix of on-premises + cloud).
- **Benefits of cloud:** trade fixed cost for variable cost; economies of scale; stop guessing capacity (**elasticity/scalability**); speed and agility; no data-centre maintenance; go global in minutes.
- **Global infrastructure:** **Regions** (geographic areas), **Availability Zones** (isolated data centres inside a region; deploy across 2+ for high availability), **edge locations** (CDN, CloudFront).
- **Shared responsibility model:** AWS secures the cloud *itself* (hardware, facilities, hypervisor); **you** secure what you put *in* it (data, IAM, OS patches on EC2, configuration).
- **Core services:** **EC2** (virtual servers), **S3** (object storage), **EBS** (disk for EC2), **RDS** (managed relational DB), **DynamoDB** (NoSQL), **Lambda** (run code without servers: serverless), **VPC** (private network), **IAM** (users, roles, permissions: least privilege), **CloudWatch** (monitoring), **CloudFormation** (infrastructure as code), **Route 53** (DNS), **CloudFront** (CDN), **SNS/SQS** (messaging/queues), **Elastic Load Balancer + Auto Scaling**.
- **Pricing:** on-demand, **reserved/savings plans** (commit for discount), **spot** (spare capacity, cheapest, can be interrupted), free tier; tools: Cost Explorer, Budgets, TCO calculator.
- **Well-Architected Framework, 6 pillars:** operational excellence, security, reliability, performance efficiency, cost optimization, sustainability.
- **How it connects to your work:** "I deployed frontends on Vercel; for the RAG backend on AWS I'd use S3 for PDFs, RDS/PostgreSQL for metadata, ECS/EC2 or Lambda for the API." *(Say "I'd use", not "I used".)*
- Don't quote exam score/date unless you remember them.

### Microsoft Azure AI Fundamentals (AI-900)
**30-second version:** "It covers the basics of AI and machine learning and the Azure AI services, plus responsible AI."
- **AI workloads:** computer vision (image classification, object detection, OCR), **natural language processing** (sentiment, entity extraction, translation, speech), document intelligence, knowledge mining, **generative AI** (create text/images/code).
- **Machine learning basics:** regression (predict a number), classification (predict a category), clustering (group items); features and labels; training vs validation; **Azure Machine Learning** (platform to build/deploy models; automated ML).
- **Azure AI services:** Azure AI Vision, Language, Speech, Translator, Document Intelligence, **Azure OpenAI Service** (GPT models, embeddings, DALL·E on Azure), Azure AI Search.
- **Generative AI concepts:** LLMs, prompts, **copilots**, RAG, content filters.
- **Six responsible-AI principles:** **fairness, reliability and safety, privacy and security, inclusiveness, transparency, accountability.** (Memory trick: **F R P I T A**.)
- **How it connects to your work:** CaneGuard (computer vision + tabular ML), StructRAG (NLP + generative AI + RAG).

---
## 6. Patents, open source and achievements

### 6.1 Your two patent applications

**30-second version:** "I'm a co-inventor on two patent applications filed in May 2026: one for a secure toll management system that authenticates toll readers and keeps transactions tamper-evident, and one for a federated physics-informed neural network system for semiconductor quality control. My contribution was ___."

#### What is a patent? (so you can explain it simply)
A **patent** is a legal right, given by the government (in India: the Indian Patent Office), that stops others from making/using/selling your **invention** without permission, usually for **20 years from filing**, in return for you disclosing how it works publicly. Steps in India (simplified): **file the application** (Form 1 + specification with description, **claims**, abstract) → **publication** (normally after about 18 months, earlier on request) → **examination** → **grant** (or objections). **The claims are the legal heart**: they define exactly what is protected.
- **Patent application ≠ granted patent.** Yours are *applications*, not granted. **Never say "patented", "I hold a patent" or "granted".**
- **Careful:** your resume says "published". Both filings are dated **May 2026**; whether they've actually been published in the patent journal is for you to confirm (check the application status on the IPO site tonight). If you can't confirm, say **"filed in May 2026"**.
- **Co-inventors** = the people who contributed to the inventive idea; the applicant for both is **Vellore Institute of Technology**.
- **Your own contribution** (what you designed/built/wrote) is the #1 follow-up question: write 2 lines and rehearse them. `___`

---

#### Patent 1: Secure Toll Management System with Cryptographic Authentication and Transaction Sequencing
*App. No. 202641056093 · with Dr. Priya V, N Sakthivel, C Edward · May 2026.* (The invention-disclosure form calls it "Hybrid Toll Management System (HTMS) with Self-Healing Trust Governance and Tamper-Evident Transaction Sequencing".)

**The problem in plain words:** Toll booths (FASTag/RFID) send vehicle data to a central system. Weaknesses: someone can **replay** an old valid message, a **fake or hacked reader** can send bad data, and records can be **tampered with** later. We wanted a system that proves who sent each transaction, distrusts misbehaving readers, and makes tampering detectable.

**How it works, as a story:**
1. **At the toll gate** an RFID reader (ESP8266/ESP32 + MFRC522 module) reads the vehicle tag's ID (UID). To protect privacy it **hashes the UID with SHA-256** (a one-way scramble). It builds an event: `{hashed UID, reader ID, timestamp, nonce}`. A **nonce** = a number used once (stops replays). It **signs** the event with **HMAC-SHA256** using a secret key unique to that reader (HMAC = a keyed hash proving the message came from someone who has the key and wasn't changed). If the network is down, it **buffers up to 10 events** and sends them later.
2. **The backend** (FastAPI) checks the **signature** (recompute HMAC and compare), the **nonce** (has it been used? then it's a replay), the **timestamp** (too old/far from server time?), and the **request rate** (too many requests?).
3. **Trust governance:** every reader has a **trust score 0–100**. Bad behaviour reduces it: authentication failure −40, balance manipulation −30, replay attempt −15, abnormal volume −12, rate-limit breach −10. If it falls below a threshold (example: 35) the reader is **quarantined** (blocked). Think: "a security guard who loses trust after suspicious acts."
4. **Self-healing recovery** (how a quarantined reader can come back): **Stage 1, time decay:** trust slowly rises with time, `recovery = 2.0 × ln(1 + hours)` (a logarithmic curve, capped, e.g. at 80). **Stage 2, probation:** the reader must pass challenges (scan a known test tag, respond in time, compute a hash correctly). **Stage 3, peer consensus:** other healthy readers vote (at least 2 voters, at least 60% approval, a reader can't vote for itself). **Cross-reader suspicion:** tags that a quarantined reader recently scanned get **stricter fraud checks** for a while.
5. **Fraud detection:** rules (invalid toll amounts, repeated scans, vehicle-type mismatch) + a **supervised ML model** (tree-based) + an **anomaly detector** (spots unusual patterns) → combined into one **fraud score** (features such as amount, speed, time between transactions, hour-of-day as sin/cos) → **approve / flag / reject**.
6. **Tamper-evident sequencing:** each approved transaction is chained to the previous one: `vdf_input = SHA256(previous_output + event_id + tx_hash + reader_id + timestamp)` then `vdf_output = SHA256` applied **1000 times** to that input. Like pages of a notebook sewn together where each page carries a fingerprint of the previous page: if someone changes, inserts, deletes or reorders a record, the chain **breaks** and is detected.
7. **Audit anchoring:** batches of transactions are summarised using a **Merkle tree** (hash pairs of hashes upward until one **Merkle root** remains); **only the root** is stored on a **blockchain**, so integrity can be verified later without storing all data on-chain (tested on a local Ethereum network, Ganache).

**Evidence in the document (all simulation/prototype: say so):** 48 automated tests passed in 2.95 s; simulated dataset of 10,000+ transactions, 5 test tags, 3 simulated readers; the 1000-hash step takes under 50 ms; example recovery 60 → 73.8 after 24 hours; on the simulated data the **hybrid ensemble** had accuracy 0.95, precision 0.92, recall 0.89, F1 0.90 versus 0.92/0.88/0.85/0.86 for the supervised model alone; a **hardware prototype** (ESP8266 + RFID + LCD showing "Access Granted/Denied") was built.

**Likely questions:**
- *What is HMAC? Why a nonce? Why hash the UID?* → HMAC = keyed hash proving authenticity + integrity; nonce prevents replay; hashing hides the real tag ID.
- *What is a Merkle tree? Why store only the root?* → A tree of hashes; the root represents all the data; storing just the root keeps on-chain storage tiny but lets you prove any transaction belongs to the batch.
- *What is a VDF?* → A Verifiable Delay Function: a function that takes a set amount of **sequential** time to compute but can be checked. **Honest note:** ours is **1000 sequential SHA-256 hashes**, i.e. a sequential hash chain; a true VDF verifies much faster than it computes, and ours is verified by recomputing. It still gives ordered, tamper-evident records.
- *Why blockchain?* → An append-only, shared ledger that no single party can quietly edit; we anchor only hashes.
- *Is it deployed in real toll plazas?* → **No.** It's a prototype tested on simulated data and a small hardware setup.
- *Real-life limits?* → Simulated data; one prototype; real-world scale, key management and integration with existing FASTag systems would be future work.

---

#### Patent 2: Federated Physics-Informed Neural Network System for Semiconductor Quality Control
*App. No. 202641065392 · with Dr. E.P. Ephzibah · specification dated 5 May 2026 · 10 claims.*

**The problem in plain words:** Chip factories ("fabs") make wafers with thousands of steps; small defects ruin yield. We want to **spot anomalies early**, **explain why** (which physical law is violated), let **many fabs learn together without sharing secret raw data**, and **auto-generate compliance reports**. The design targets India's PLI-scheme fabs and Indian conditions (monsoon humidity, power-grid dips, supplier variation).

**Key terms, simply:**
| Term | Meaning |
|---|---|
| **Digital twin** | A live software copy of the real fab line, updated from sensors (here every 100 ms). The "India-Adapted Digital Twin Schema" also stores monsoon humidity, grid voltage sag/swell and supplier quality variation. |
| **Autoencoder** | A neural network that learns to compress and then rebuild normal data. If new data is rebuilt badly (**high reconstruction error**), it's probably abnormal → anomaly detector. |
| **LSTM** | A neural network good at **sequences/time series** (sensor readings over time). |
| **Physics-Informed Neural Network (PINN)** | A network whose training also penalises **physics violations**. Here the loss is `L_total = L_recon + 0.1·L_Rayleigh + 0.1·L_Electromigration + 0.1·L_Diffusion`. |
| **Rayleigh resolution** | Optics limit on the smallest feature lithography can print: `CD = k1·λ/NA = 0.40 × 193 nm / 0.93 ≈ 83 nm`. |
| **Black's equation (electromigration)** | Current density wears metal wires over time; limits safe current density (max 2.5×10⁶ A/cm²). |
| **Fick's diffusion** | How dopant atoms spread into silicon over time and temperature. |
| **Federated learning** | Each fab trains on its **own local data** and shares only **model updates**, not raw data; a coordinator averages them. |
| **FedProx** | A federated method with a **proximal term** (μ = 0.01) that stops local models from drifting too far from the global model. |
| **Differential privacy (DP)** | Adds calibrated **noise** to updates so individual data can't be reverse-engineered (ε = 1.0, δ = 10⁻⁵, σ = 1.08). |
| **INT4 quantization** | Compress updates from 32-bit numbers to 4-bit → about **8× less bandwidth**. |
| **SEMI E10 / E35 / E116** | Industry standards for equipment reliability, cost of ownership, and equipment performance/OEE; the system maps each anomaly to them and **auto-writes an audit XML**. |

**How it works, as a story:** sensors → digital twin → LSTM-autoencoder with physics-aware loss on an edge device (Jetson Orin NX, under 100 ms) → **anomaly score** + **tags saying which physics law was violated** → classified against SEMI standards (updates MTBF, cost-of-ownership, OEE) → alert (Grafana dashboard + PagerDuty) or log (InfluxDB). Every 4 hours each fab sends **DP-noised, INT4-compressed** updates to a coordinator (Flower/FedProx) which aggregates and sends back an improved global model.

**Why physics in the loss?** It stops physically impossible predictions, reduces the data needed (important for new fabs), and makes alerts **explainable** ("electromigration limit exceeded").

**Figures in the specification (from defect-injection validation, worded "may", so simulation):** average detection time 6.6 h vs 17.8 h with periodic inspection (about 63% faster); physics constraints may reduce training data needs by at least 33%. **Never claim real-fab deployment or real-world accuracy.**

**Likely questions:** *What is federated learning/PINN/autoencoder? Why add noise? Is it implemented/deployed? What was your part?* → Answer from the table; "this is a patent specification with simulated validation, not a deployed system"; your part = `___`.

---

### 6.2 Open-source contributions (3 merged PRs: verified on the projects' main branches)

#### What open source and a pull request are (simple)
**Open source** = software whose code is public and anyone can propose improvements. To contribute: **fork** (your copy) → create a **branch** → fix → **commit** → open a **pull request (PR)** → maintainers (and bots) **review** → you fix feedback → they **merge**. A merged PR means the maintainers accepted your change into the real project.

**30-second version:** "I have three merged open-source PRs: a TypeScript bug fix with tests in Zulip, and two Python/Django PRs in Learning Unlimited: tests for the student-lottery module and a config change that centralizes a Google Maps key."

#### Zulip PR #38394: "compose: Preserve indentation when continuing lists" (fixes issue #37737)
- **Zulip** = an open-source team chat app (Python/Django backend, TypeScript web app).
- **The bug:** In the message box, if you type a **sub-bullet** like `  - nested` and press **Shift+Return**, Zulip should start a new indented bullet. Instead it gave a plain new line.
- **Root cause:** helper functions `is_bulleted()` and `is_numbered()` checked that the line **starts** with `- ` or `1.`. With leading spaces (indent) the check **silently failed**.
- **My fix:** added `get_indent()` (a small regex helper); strip the indent before checking bullet/number; **re-add the indent** to the new marker; and when you press Enter on an *empty* indented bullet to end the list, remove the indent too (adjust the selection range).
- **Tests:** 4 new unit tests (indented bullet continues; empty indented bullet is removed; indented numbering continues "2."; empty indented number removed). 3 files changed, +67/−13 lines. Co-authored with another contributor.
- **What you can say you learned:** reading a big unfamiliar codebase, TypeScript, writing tests for edge cases, following project guidelines (Zulip is strict about commit messages and tests).

#### Learning Unlimited (ESP-Website): two PRs
*ESP-Website = Django web software that volunteer-run student education programs use for class registration.*
- **PR #4957: "Add unit tests for LotteryFrontendModule" (fixes issue #4953).** The "lottery" assigns students to classes. I wrote **6 tests** for the three admin web views: the lottery page loads (HTTP 200) for admins; **execute** works, handles errors (`LotteryException`) and converts form options (True/False/numbers) correctly; **save** reports missing data and succeeds with good data. I used **mocks** (fake stand-ins for the real lottery engine) so the tests check only the views. After an automated **Copilot review**, I removed an unused import, asserted number conversion and asserted the exact payload passed on. Merged 29 Jul 2026.
- **PR #4997: "Add Google Maps Embed API key to local_settings.py" (closes issue #3818).** Each program chapter had to create its own Google Cloud account and set a key in a database tag, even though the **Maps Embed API is free**. I moved it to **one central setting** `GOOGLE_MAPS_EMBED_KEY` (empty default in `django_settings.py`, placeholders in the deploy and Docker settings so the real key stays **off GitHub**); the student and teacher "onsite" pages now read the setting; docs updated; the old tag marked deprecated. 7 files, +23/−9 lines. A maintainer later pushed follow-up commits onto my branch. Merged 18 Jul 2026.
- **Concepts to know:** **unit test** = checks one small piece in isolation; **mock** = fake dependency; **config management** = keep settings/secrets out of code and in one place; **code review** = others check your change.
- **Don't claim:** more than these three PRs, how many review rounds, or being a maintainer.

**Likely questions:** *Tell me about your open-source contribution. How did you find the issue? How did you test it? What feedback did you get? What did you learn?* → Pick Zulip as the main story (bug → cause → fix → tests → merged).

---

### 6.3 Achievement: First Prize, DBT-sponsored Agrithon 2.0, VIT Vellore
- **Hackathon** = a time-boxed event where teams build a working prototype to solve a problem. **DBT** = Department of Biotechnology (Government of India). **Agrithon** = an agriculture-focused hackathon. You built **CaneGuard** with Team Deepcrop.
- **Say:** "We won first prize at the DBT-sponsored Agrithon 2.0 at VIT with CaneGuard." **Stop there** unless asked. Don't add the prize amount, the number of teams or jury names. Keep the certificate link ready.
- **Likely follow-ups:** What was your role? How long did you have? What would you change with another weekend? *(Answer: fill from your memory; "I'd start with an evaluation set and clean up the repo" is a good true improvement.)*

---

## 7. Resume vs reality: the claims an interviewer could challenge

| Resume claim | Reality (from your study guides) | What to say |
|---|---|---|
| "…**multi-turn** LLM-based Q&A" (RAG) | Each question is sent alone; no history | "It's a multi-question chat; each question is independent. I'd add history or rewrite follow-ups." |
| "Built and **deployed**" (RAG) | Frontend on Vercel; backend reported down 27 Sep | Check today. "Frontend is on Vercel; I'll show the backend locally with Docker." |
| "**smart** waste pickup" (WasteZero) | Nothing is AI/optimised | "A volunteering platform with a skill-match badge." |
| "**Developed**" WasteZero | Commit history shows other authors | "My direct contribution was ___; I studied the rest." |
| "**published** patent applications" | Filed May 2026; publication unconfirmed; not granted | "Filed May 2026, not granted." |
| "Scikit-learn" | Not imported in CaneGuard | Say where you really used it (`___`). |
| "YOLOv8 + TabNet" (CaneGuard) | Training code/data not in repo | Say who trained them (`___`); you integrated/served them. |
| "Docker containers" (CaneGuard) | Dockerfile/compose exist; live host not proven | "I containerised the backend (CPU PyTorch)." |
| "First Prize … Agrithon 2.0" | Resume claim; not in README | Have the certificate; no extra details. |
| 10th and 12th both 84.8% | Resume says so | Check marksheets. |
| "Docker (basics)", "Node.js (learning)" | Honest | Keep it that way. |

**Click-test tonight:** every "Live Demo", "GitHub" and "Credential" link on your resume. A dead demo link in the interview is avoidable.

### Fill these in tonight (two lines each)
1. **CaneGuard:** what I built ___ · what I debugged ___ · who trained the models and on what ___ · how the segmentation bug ended ___
2. **WasteZero:** team size ___ · my files/modules ___ · hardest thing I handled ___
3. **Patents:** my contribution to the toll patent ___ · to the federated-PINN patent ___ · published? ___
4. **Where I used scikit-learn:** ___
5. **One real teamwork conflict (S-T-A-R):** ___
6. **Personal:** family ___ · hobbies ___ · least-favourite subject ___
7. **Live status today:** RAG frontend ___ · RAG backend ___ · demo plan ___

---

## 8. HR answers you need (short and true)

- **Why Accenture?** "Accenture works across industries on real technology problems at huge scale, with strong training and certification culture and heavy investment in cloud and AI. That matches my AWS/Azure certifications and my GenAI project, and I want to learn in real delivery teams."
- **Why should we hire you?** "I can build end to end (full stack, ML, basic deployment), I learn fast by shipping, I work well in teams (three merged open-source PRs after review), and I review my own work honestly."
- **Strengths:** end-to-end building · fast self-learning · ownership and honest self-review (each with a project example).
- **Weakness (true):** "I tend to build first and measure later. In my RAG project I never built an evaluation set, so I can't prove my ranking idea helps. Now I plan evaluation and tests earlier."
- **Failure / challenge:** the segmentation bug (isolate the model from the app; pin versions) or the unmeasured RAG idea.
- **Teamwork:** CaneGuard (4 people), WasteZero (internship team), patents (co-inventors): split work by component, use Git, sync often.
- **Conflict:** "Talk to the person privately, listen, agree the goal and a split, escalate to a mentor only if needed." (Use a real example if you have one.)
- **Learning a new technology in a month:** docs + quickstart → one small real project → tests → read/contribute to others' code. (You did this with MERN, FastAPI/RAG and TypeScript for Zulip.)
- **5 years:** a solid engineer delivering client projects end to end, deeper in cloud and applied AI, growing toward tech lead.
- **Relocation / shifts / any technology:** your honest answer (default: yes, open to relocate and to shifts).
- **Questions to ask them:** (1) What does fresher onboarding/training look like in the first 3–6 months? (2) What projects and technologies do new joiners usually start on, e.g. cloud or GenAI? (3) What are the expectations from a fresher in year one? (4) What helps a fresher stand out in your team?
- **Accenture facts (checked 9 Oct 2026):** CEO **Julie Sweet** (Chair & CEO); global HQ **Dublin, Ireland**; about **814,000 employees** at end of FY2026; clients in **120+ countries**; offices in 49 countries and 200+ cities. Don't name an Indian HQ.

---

## 9. Last-hour cheat sheet (read this in the morning)

**Your 4 numbers:** CGPA **8.07** · **3** projects · **3** merged PRs · **2** patent applications (+ 2 certifications).

**RAG in one breath:** upload PDF → chunk (3000/800) → embed (MiniLM 384-dim) → ChromaDB → question → nearest chunks → boost by section → LLM answers with page sources. Honest: **no evaluation, not multi-turn, no auth, demo status check.**

**CaneGuard in one breath:** photo → YOLOv8 → image score (max confidence); 15 yes/no → TabNet → probability; **0.6·image + 0.4·tabnet ≥ 0.5**. Honest: **no accuracy number, weights never tuned, 0.4 ceiling when nothing detected, key was committed.**

**WasteZero in one breath:** MERN; JWT in httpOnly cookie (30 min); roles volunteer/ngo/admin; apply protected by a unique index. Honest: **`req.user._id` bug, suspension not enforced, route-order bug, OTP weak, localhost-only CORS, not smart, my part = ___.**

**Toll patent in one breath:** signed RFID events (HMAC + nonce) → trust scores + quarantine/self-healing → hybrid fraud detection → VDF hash chain → Merkle root on blockchain. **Simulation/prototype; not granted.**

**PINN patent in one breath:** LSTM-autoencoder + physics losses (Rayleigh, Black, Fick) + federated learning (FedProx, DP noise, INT4) + SEMI compliance reports. **Specification with simulated validation; not granted.**

**Open source in one breath:** Zulip indent fix with 4 tests; Learning Unlimited lottery tests (6) and a central Maps-key setting.

**The 8 words that save you:** *"I haven't measured that, but here is how I would."*

**Delivery tips:** speak slowly; 4–6 sentences per answer; give the answer first, then the example; mention a limit before they find it; say "we" for teamwork; ask 1–2 questions at the end; never say "no questions"; never invent a number.

**Do not claim:** accuracy/percentages · "production-ready" · "patented/granted" · "multi-turn" (RAG) · "smart/AI" (WasteZero) · "I built the whole WasteZero" · real deployment of either patent.

**Good luck tomorrow, you know this material, and you know where its edges are. That honesty is your strength.**

---

## Glossary (A–Z of terms on your resume)

**ACID** database transaction properties · **Agrithon** agriculture hackathon · **API** contract for programs to talk · **Autoencoder** network that compresses/rebuilds data; high error = anomaly · **AWS CCP** foundational AWS cert · **Azure AI-900** foundational Azure AI cert · **base64** way to write binary (an image) as text · **bcrypt** salted slow password hashing · **Big-O** growth of work with input size · **BFS/DFS** breadth-first/depth-first search · **CI** continuous integration (auto test on push) · **CGPA** cumulative grade point average · **chunk** piece of a document · **ChromaDB** vector database · **container** running instance of a Docker image · **CORS** browser cross-origin rule · **cosine similarity** vector similarity measure · **CSRF/XSS** cross-site request forgery / scripting attacks · **digital twin** live software copy of a physical system · **Docker** packaging into containers · **DP** differential privacy · **embedding** meaning as numbers · **Express** Node web framework · **FastAPI** Python web framework · **federated learning** train locally, share only updates · **FedProx** federated algorithm with proximal term · **fork** your copy of a repo · **fusion** combining model outputs · **GitHub Actions** CI/CD automation · **hackathon** timed build event · **hallucination** LLM inventing facts · **HMAC** keyed hash for authenticity · **httpOnly cookie** cookie hidden from JavaScript · **IDOR** accessing others' data by changing an id · **index** structure that speeds queries · **JWT** signed login token · **LLM** large language model · **LSTM** sequence neural network · **Merkle tree/root** tree of hashes / single summary hash · **middleware** function between request and controller · **mock** fake test stand-in · **MERN** MongoDB, Express, React, Node · **Mongoose** MongoDB schema library · **multi-modal** multiple input types · **nonce** number used once · **NMS** removes duplicate boxes · **OTP** one-time password · **PINN** physics-informed neural network · **polling** repeatedly asking for status · **PR** pull request · **precision/recall/F1** classification metrics · **prompt injection** malicious text steering an LLM · **RAG** retrieval-augmented generation · **REST** resource-based API style · **RRF** reciprocal rank fusion · **salt** random extra data for hashing · **segmentation** pixel-level outline of objects · **TabNet** deep model for tabular data · **TTL index** auto-delete after time · **TLS** encryption layer of HTTPS · **Vercel** frontend hosting · **VDF** verifiable delay function · **Vite** frontend build tool · **YOLO** one-pass object detector.
