<div align="center">

# Karthik T

### AI Engineer — RAG Systems, Agentic Workflows, LLM Evaluation

Final-year CS student at IIIT Manipur · GATE 2026 qualified · Open to GenAI / LLM / AI Agent roles

[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:thirkarthik30@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/karthik-profile-/)

</div>

---

### Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**GenAI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square&logo=groq&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)

**Retrieval & Data**

![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-1E1E2E?style=flat-square)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**Deployment & Web**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-FF7C00?style=flat-square&logo=gradio&logoColor=white)

---

### About

I build retrieval and agent systems end to end — ingestion, retrieval, evaluation, and deployment — not notebook demos. Recent work includes a multi-agent pricing engine built on raw function calling, an LLM-as-judge evaluation harness for a RAG Q&A system, a hybrid dense+sparse search engine, and an LLM-based digital forensics pipeline built during an internship at RV University.

---

### Experience

**AI Engineering Intern — RV University, Bengaluru**
*Jun–Jul 2026 · Remote · LLM-Based Digital Forensics, supervised by Dr. Manish Kumar*

- Built a data-ingestion pipeline parsing EVTX logs, PCAP captures, and CSV/syslog exports into a unified event schema.
- Fused Qdrant dense retrieval with BM25 sparse retrieval via Reciprocal Rank Fusion, gated by a relevance filter that rejects off-topic queries before they reach the LLM.
- Built a citation-enforced LLM layer (Ollama, Llama-3-8B) that checks every citation against retrieved evidence and caps confidence to what retrieval supports, shipped through a Streamlit investigator UI.

---

### Projects

**[DealArbiter](https://github.com/SudeepKarthik30/DealArbiter) — Multi-Agent Pricing Engine**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-1E1E2E?style=flat-square)
![Modal](https://img.shields.io/badge/Modal-000000?style=flat-square)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)

Orchestration agent built on raw OpenAI function calling (no framework) that plans and sequences its own tool calls for deal scanning, pricing, and alerting. Pricing comes from a three-model ensemble — a fine-tuned Llama-3.2-3B (QLoRA, trained on Modal), a RAG agent over ChromaDB, and a custom PyTorch network.

**[PolicyPilot](https://github.com/SudeepKarthik30/insurellm-copilot) — Insurance Q&A System**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-1E1E2E?style=flat-square)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square&logo=groq&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-FF7C00?style=flat-square&logo=gradio&logoColor=white)

Dual-query retrieval pipeline: an LLM rewrites the question, both versions are searched in parallel, and a local cross-encoder reranks the results, replacing an LLM-based reranker that hit rate limits and hallucinated chunks. Evaluated with an LLM-as-judge harness across 150 questions in 7 categories — MRR 0.87, nDCG 0.85, answer quality 4.31/5.

**[ResearchRAG](https://github.com/SudeepKarthik30/Research-assistant-rag) — Hybrid Search Assistant**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-1E1E2E?style=flat-square)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square&logo=groq&logoColor=white)
![BM25](https://img.shields.io/badge/BM25-4B4B4B?style=flat-square)

Hybrid retrieval engine combining dense search (ChromaDB) with sparse BM25 via Reciprocal Rank Fusion, deployed with a section-aware PDF parser (PyMuPDF) that extracts page-level citation metadata. Evaluated with Precision@3 and keyword hit rate against a dense-only baseline.

**[ServiceDesk Copilot](https://github.com/SudeepKarthik30/ServiceDesk-Copilot) — AI IT Helpdesk**

![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square&logo=groq&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)

IT helpdesk where an AI pipeline classifies, retrieves, and answers tickets directly when confident, or routes them to the right team with a suggested fix otherwise.

---

### Education

| Degree | Institution | Duration |
|---|---|---|
| B.Tech, Computer Science and Engineering | IIIT Manipur | 2023 – 2027 |
| Matriculation & Intermediate (MPC) | JNV Krishnapuram | 2016 – 2023 |

GATE 2026 qualified — Computer Science and Engineering

---

<div align="center">

thirkarthik30@gmail.com · [LinkedIn](https://www.linkedin.com/in/karthik-profile-/) · Nellore, AP, India

</div>
