# Karthik T

AI Engineer building GenAI systems — RAG pipelines, agentic workflows, and LLM evaluation. Final-year CS student at IIIT Manipur.

## About

I build retrieval and agent systems end to end — ingestion, retrieval, evaluation, and deployment — not notebook demos. Recent work includes a multi-agent pricing engine built on raw function calling, an LLM-as-judge evaluation harness for a RAG Q&A system, a hybrid dense+sparse search engine, and an LLM-based digital forensics pipeline built during an internship at RV University.

Finishing a B.Tech in Computer Science at IIIT Manipur (2027), GATE 2026 qualified in CS. Open to GenAI Engineer, LLM Engineer, and AI Agent Developer roles.

## Experience

**AI Engineering Intern — RV University, Bengaluru** (Jun–Jul 2026, remote)
LLM-based digital forensics pipeline, supervised by Dr. Manish Kumar.

- Built a data-ingestion pipeline parsing EVTX logs, PCAP captures, and CSV/syslog exports into a unified event schema.
- Fused Qdrant dense retrieval with BM25 sparse retrieval via Reciprocal Rank Fusion, gated by a relevance filter that rejects off-topic queries before they reach the LLM.
- Built a citation-enforced LLM layer (Ollama, Llama-3-8B) that checks every citation against retrieved evidence and caps confidence to what retrieval supports, shipped through a Streamlit investigator UI.

## Projects

**[DealArbiter](https://github.com/SudeepKarthik30/DealArbiter)** — Multi-agent pricing engine
*Python, PyTorch, ChromaDB, Modal, OpenAI*
Orchestration agent built on raw OpenAI function calling (no framework) that plans and sequences its own tool calls for deal scanning, pricing, and alerting. Pricing comes from a three-model ensemble — a fine-tuned Llama-3.2-3B (QLoRA, trained on Modal), a RAG agent over ChromaDB, and a custom PyTorch network.

**[PolicyPilot](https://github.com/SudeepKarthik30/insurellm-copilot)** — Insurance Q&A system
*Python, LangChain, ChromaDB, Groq, Gradio*
Dual-query retrieval pipeline: an LLM rewrites the question, both versions are searched in parallel, and a local cross-encoder reranks the results, replacing an LLM-based reranker that hit rate limits and hallucinated chunks. Evaluated with an LLM-as-judge harness across 150 questions in 7 categories — MRR 0.87, nDCG 0.85, answer quality 4.31/5.

**[ResearchRAG](https://github.com/SudeepKarthik30/Research-assistant-rag)** — Hybrid search assistant
*Python, Flask, ChromaDB, Groq, BM25*
Hybrid retrieval engine combining dense search (ChromaDB) with sparse BM25 via Reciprocal Rank Fusion, deployed with a section-aware PDF parser (PyMuPDF) that extracts page-level citation metadata. Evaluated with Precision@3 and keyword hit rate against a dense-only baseline.

**[ServiceDesk Copilot](https://github.com/SudeepKarthik30/ServiceDesk-Copilot)** — AI IT helpdesk
*Django, React, Qdrant, Groq, Celery*
IT helpdesk where an AI pipeline classifies, retrieves, and answers tickets directly when confident, or routes them to the right team with a suggested fix otherwise.

## Skills

**Languages:** Python, C/C++, SQL
**GenAI:** RAG, agentic workflows, tool-calling, LLM fine-tuning (QLoRA), prompt engineering, LangChain, PyTorch, Hugging Face (Transformers, PEFT, Accelerate)
**Retrieval & evaluation:** ChromaDB, Qdrant, BM25, hybrid retrieval (dense + sparse + RRF), cross-encoder reranking, LLM-as-judge evaluation (MRR, nDCG, Precision@K)
**Deployment:** Docker, Flask, Streamlit, Gradio, REST APIs, OpenAI, Groq, Modal, Ollama

## Education

B.Tech, Computer Science and Engineering — IIIT Manipur, 2023–2027
GATE 2026 qualified — Computer Science and Engineering

## Contact

Email: thirkarthik30@gmail.com
LinkedIn: [linkedin.com/in/karthik-profile-](https://www.linkedin.com/in/karthik-profile-/)
