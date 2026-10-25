# Ankit Kumar

I'm a Data Science and Engineering undergraduate at IISER Bhopal, a research intern at IIT Indore, and someone who doesn't close the laptop until the thing I started actually works.

I build applied AI systems end to end — from multimodal models and speech pipelines to async backends, real-time interfaces, and production deployment. My main interests are speech and emotion AI, multimodal learning, NLP, and the engineering required to make ML systems reliable outside a notebook.

[Email](mailto:ankitk24@iiserb.ac.in) · [LinkedIn](https://www.linkedin.com/in/ankit-kumar-476b35378/) · [GitHub](https://github.com/AnkitKumarIISERB)

---

## Currently

- Research Intern at **IIT Indore**, working on NLP and multimodal AI.
- Building systems around audio, language, emotion, retrieval, and real-time inference.
- Looking for **remote contract work in ML engineering or applied AI**.

---

## Things I've shipped

**[Voice Journal AI](https://voicejournal-app.vercel.app)** — full-stack voice journaling with multimodal emotion analysis. It combines WavLM acoustic emotion features with Whisper transcription and Llama-3.1 semantic analysis, then presents a continuous valence score on a live dashboard. The backend uses FastAPI, Redis, Celery, WebSockets, encrypted storage, JWT authentication, Prometheus metrics, pytest, GitHub Actions, and Docker Compose.

`WavLM` `Whisper` `Llama-3.1` `FastAPI` `Celery` `Redis` `WebSocket` `React` `Docker`

**[Aria](https://aria-multimodal-analyzer.vercel.app/)** — real-time multimodal conflict detection between facial and vocal emotion. MediaPipe FaceMesh 468-landmark geometry and WavLM embeddings are processed over dual WebSocket streams and fused every 500 ms, with graceful degradation when either modality becomes stale or unavailable.

`WavLM` `MediaPipe` `scikit-learn` `FastAPI` `WebSockets` `React` `Framer Motion`

**[PaperMind](https://papermind-lemon.vercel.app)** — semantic search and RAG Q&A over 200+ research papers. It uses sentence-transformers and pgvector for retrieval, grounded Llama-3.1 answers through Groq, and a paper-similarity knowledge graph generated with a single in-database cosine-similarity query.

`sentence-transformers` `pgvector` `Groq` `Llama-3.1` `FastAPI` `SQLAlchemy` `Neon`

---

## Open source

### [aeon](https://github.com/aeon-toolkit/aeon)

Contributor to **aeon**, a JMLR-published Python library for time-series machine learning. I have **3 merged documentation and example-notebook pull requests**, all reviewed and accepted by maintainers:

- **[PR #3736](https://github.com/aeon-toolkit/aeon/pull/3736)** — standardized NumPy terminology by replacing remaining “indexes” references with “indices” in docstrings and comments across 13 files, covering segmentation, benchmarking, shapelet, transformations, and utility modules.
- **[PR #3748](https://github.com/aeon-toolkit/aeon/pull/3748)** — cleared stale `ImportError` output from the `data_unequal` documentation notebook after identifying that it came from an incompatible previous sklearn environment.
- **[PR #3813](https://github.com/aeon-toolkit/aeon/pull/3813)** — reran the SAST and forecasting notebooks in a current Python 3.12 environment and removed stale `NameError` outputs from the rendered documentation.

These contributions focus on documentation quality, reproducible examples, terminology consistency, and keeping generated notebook output trustworthy.

---

## How I work

I figure things out alone when I have to, and talk it through when that's faster. I work on problems until they're done — not “done for tonight.”

I'm equally comfortable reading a paper and implementing it from scratch, designing an async service around a model, or debugging why a Celery worker is blocking the event loop at 1am.

---

## Stack

```text
ML/AI       PyTorch · TensorFlow · HuggingFace · WavLM · RoBERTa · sentence-transformers · scikit-learn · XGBoost
Domains     Multimodal Fusion · NLP · Speech Processing · Affective Computing · RAG · Semantic Search
Backend     FastAPI · REST APIs · Celery · Redis · WebSockets · PostgreSQL · pgvector · SQLAlchemy · asyncpg · JWT
Frontend    React · TypeScript · JavaScript · Vite · Recharts · Framer Motion · Web Audio API · MediaRecorder API
Engineering Docker · Docker Compose · pytest · Git · GitHub Actions · Prometheus · Render · Vercel
Languages   Python · C++ · C · SQL · JavaScript · TypeScript · HTML/CSS · LaTeX
```

---

## What I'm looking for

Remote contract work in **ML engineering, applied AI, backend systems, or full-stack products with an ML core**. If you're building something in audio AI, multimodal systems, NLP, RAG, or real-time inference and need someone who ships, let's talk.

[ankitk24@iiserb.ac.in](mailto:ankitk24@iiserb.ac.in) · [LinkedIn](https://www.linkedin.com/in/ankit-kumar-476b35378/)
