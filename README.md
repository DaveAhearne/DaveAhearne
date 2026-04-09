# 👋 Hi, I'm David A'Hearne

ML Engineer and founder with 13 years building production systems. The last two have been deep in applied ML: NLP scoring pipelines, RAG systems, LLM integration, and the MLOps tooling that makes them actually run in production. I'm also completing a BSc in Mathematics at the Open University and a Cambridge Data Science Career Accelerator, because the theory matters when the work gets hard.

---

## 🔧 Core Engineering Experience

My background is in senior and lead engineering roles with long-term ownership of production systems across fintech, energy, defence, and SaaS.

- Distributed systems and microservice architecture, designed and evolved under real operational pressure
- Cloud-native development on AWS and Azure, including infrastructure automation and CI/CD pipelines
- Strong emphasis on reliability through TDD and BDD: unit, integration, contract, and end-to-end testing
- Production API design with strict separation between domain, application logic, and infrastructure concerns
- Languages across production systems: Python, Go, C#, SQL, JavaScript

---

## 🧠 Applied ML and NLP

Recent production ML work:

**Gradia** (Keenu.io, via Turing Innovation Catalyst) — automated IELTS writing assessment API. NLP scoring pipeline using spaCy word vectors and cosine similarity across eight subscores covering paragraph cohesion, sentence-to-document similarity, lexical richness, vocabulary sophistication, and punctuation analysis. HuggingFace BERT-based punctuation restoration model for grammatical analysis. LLM-integrated scoring with a routed client supporting OpenAI and Ollama as interchangeable backends. After applying linear regression calibration to raw LLM scores, 94% of marks landed within +/- one band and 86% within +/- half a band. Full MLOps stack: MLflow, FastAPI, Docker, AWS ECR/ECS, GitHub Actions CI/CD.

**Nightshift** (Cambridge Data Science Career Accelerator, employer project for NICE) — RAG pipeline for clinical code retrieval. Given a free-text clinical research question, the system parses it into typed clinical entities using Stanza biomedical NER (bc5cdr and i2b2 models), then retrieves and ranks relevant codes across SNOMED CT, ICD-10, QOF, and NHS reference sets using hybrid semantic and TF-IDF retrieval backed by SapBERT/BioBERT embeddings in sqlite-vec. MLflow evaluation against gold-standard code sets tracking F1, precision, and recall.

**MarkVerify** (Keenu.io) — evaluation scoring platform built in Go for collecting and human-scoring inbound IELTS test submissions, producing the ground-truth labels Gradia's MLflow experiments ran against.

Alongside production work, I've applied a broader set of ML techniques through the Cambridge programme: scikit-learn, XGBoost, Keras, TensorFlow, PyTorch, statsmodels, BERTopic, LSTM, ARIMA, anomaly detection, clustering, dimensionality reduction.

---

## 👥 Leadership

I've hired and led cross-functional engineering teams of up to 15, owned products end to end from ideation through live operation, and mentored engineers across multiple levels through pairing, code review, structured 1:1s, and company-wide talks. Most recently as Delivery Lead at BrightHR, responsible for the BrightSafe product across five countries.

---

## 🚀 What I'm Building

**Covet** is a two-sided recruitment platform for the UK senior tech market. Under the hood it's an NLP and recommender system: a two-stage matching pipeline combining hard constraint filtering with embedding-based scoring using sentence transformers (BAAI/bge-large-en-v1.5) across structured candidate and role profiles.

The longer-term architecture extends the pipeline with agent-to-agent communication, where candidate and company agents negotiate constraints and conduct structured evaluation autonomously. The outputs are visible to both sides.

The stack: FastAPI, HTMX, SQLite, AWS (EC2, ECR, Cognito, CloudWatch), Docker, GitHub Actions. A standalone Scout service pulls and normalises job listings via ATS adapters (Greenhouse, Lever, Workable, Ashby).

[blog.covet.digital](https://blog.covet.digital) · [linkedin.com/in/david-ahearne-767614b3](https://linkedin.com/in/david-ahearne-767614b3)

---

## 🗂️ Employment Timeline

| Years | Company | Role |
|---|---|---|
| 2026 – | Keenu.io | ML Engineer (Turing Innovation Catalyst) |
| 2024 – | Open University / Cambridge PACE | BSc Mathematics + Data Science Accelerator |
| 2023 – 2024 | BrightHR | Delivery Lead |
| 2023 | Schneider Electric | Contract Engineer |
| 2020 – 2023 | OpenMoney | Tech Lead |
| 2018 – 2020 | Raytheon | Senior Software Engineer |
| 2016 – 2018 | Zen Internet | Systems Developer |
| 2013 – 2016 | Swinton Insurance | Junior C# Developer |
| 2012 – 2013 | Parker Sandfords | Junior Developer |
