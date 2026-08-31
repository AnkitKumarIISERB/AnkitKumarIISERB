# Ankit Kumar

I'm a 3rd-year Data Science and Engineering undergrad at IISER Bhopal, research intern at IIT Indore, and someone who doesn't close the laptop until the thing I started actually works.

Most of what I build sits at the intersection of speech, emotion, and ML systems — not just the models, but the full stack around them. Redis queues, WebSocket pipelines, async inference workers, the works. I care about architecture tradeoffs as much as accuracy numbers.

Currently: first-author paper under review at Springer Nature (multimodal depression detection, CGFM fusion method, state-of-the-art Macro F1 across 3 corpora).

---

## Things I've shipped

**[Voice Journal AI](https://voicejournal-app.vercel.app)** — voice journaling with 60/40 acoustic-semantic emotion fusion. WavLM on your voice, Llama-3.1 on your words, fused into a single valence score. Celery + Redis + WebSockets. Crisis anomaly detection. Runs at $0/month.
`WavLM` `FastAPI` `Celery` `Redis` `WebSocket` `React` `Docker`

**[Aria](https://aria-multimodal.vercel.app)** — real-time conflict detection between what your face and voice are saying. MediaPipe FaceMesh 468-landmark geometry fused with WavLM embeddings over dual WebSocket streams, 500ms fusion loop. 4 graceful degradation modes so it doesn't break when a signal drops.
`WavLM` `MediaPipe` `scikit-learn` `FastAPI` `Framer Motion`

**[PaperMind](https://papermind-lemon.vercel.app)** — semantic search + RAG Q&A over 200+ research papers. Knowledge graph built entirely in-database with a single pgvector SQL query. Zero hallucination by design — only cites papers that actually exist.
`sentence-transformers` `pgvector` `Groq` `Llama-3.1` `FastAPI` `Neon`

---

## How I work

I figure things out alone when I have to, and talk it through when that's faster. I work on problems until they're done — not "done for tonight."

I'm equally comfortable reading a paper and implementing it from scratch or debugging why a Celery worker is blocking the event loop at 1am.

---

## Stack

```
ML/AI     PyTorch · HuggingFace · WavLM · RoBERTa · sentence-transformers · scikit-learn
Backend   FastAPI · Celery · Redis · WebSockets · PostgreSQL · pgvector · Docker
Frontend  React · Vite · Recharts · Framer Motion
Infra     Render · Vercel · GitHub Actions · Prometheus
```

---

## What I'm looking for

Remote contract work in ML engineering or applied AI. If you're building something in audio AI, multimodal systems, or NLP and need someone who ships, let's talk.

[ankitk24@iiserb.ac.in](mailto:ankitk24@iiserb.ac.in) · [LinkedIn](https://www.linkedin.com/in/ankit-yadav-476b35378)

