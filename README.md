# Karthik T

**GenAI / LLM Engineer · RAG Systems · Tool-Calling Agents · LLM Evaluation**
Final-year B.Tech CSE at IIIT Manipur (2027). I build LLM applications in Python and measure whether they actually work.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/karthik-profile-/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:thirkarthik30@gmail.com)
[![TrueClip](https://img.shields.io/badge/TrueClip-Live%20Site-000000?style=for-the-badge&logo=githubpages&logoColor=white)](https://sudeepkarthik30.github.io/TrueClip/)

---

### About

- **Hybrid RAG with citations** — dense + BM25 fused with RRF, cross-encoder reranking, citation validation on generated answers.
- **Agents with regression tests** — tool-calling agents (LangGraph, OpenAI Agents SDK, MCP) tested against a golden dataset instead of eyeballed.
- **Evaluation first** — LLM-as-judge harnesses reporting MRR, nDCG and per-category scores to find the weakest question types.
- **Local / air-gapped LLMs** — Ollama + Llama-3-8B for forensic Q&A over 30,265 parsed records.
- **GATE 2026** qualified (CSE).
- Based in India · **Open to GenAI / LLM Engineer roles** (graduating June 2027).

---

### Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![OpenAI Agents SDK](https://img.shields.io/badge/OpenAI%20Agents%20SDK-412991?style=flat-square&logo=openai&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-5A4FCF?style=flat-square)
![QLoRA](https://img.shields.io/badge/QLoRA-FF6F00?style=flat-square)

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square)
![DeepEval](https://img.shields.io/badge/DeepEval-6C63FF?style=flat-square)

![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F61?style=flat-square)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square)
![BM25](https://img.shields.io/badge/BM25-555555?style=flat-square)

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-F97316?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Modal](https://img.shields.io/badge/Modal-7FEE64?style=flat-square&logoColor=black)

---

### Featured Projects

| Project | What it does | Stack | Highlights |
| --- | --- | --- | --- |
| **[PolicyPilot](https://github.com/SudeepKarthik30/insurellm-copilot)** | Insurance Q&A: rewrites the question with an LLM, retrieves for both versions, reranks locally with a cross-encoder | Python · LangChain · ChromaDB · Groq · Gradio | **MRR 0.87 · nDCG 0.85 · 4.31/5 judged accuracy** over 150 questions in 7 categories |
| **[AgentSentinel](https://github.com/SudeepKarthik30/AgentSentinel-Enterprise-Agent-Evaluation-Policy-Guardrail-Harness)** | Regression harness for a tool-calling LangGraph refund agent (30-day cutoffs, future-dated orders, unregistered users) | LangGraph · DeepEval · FastAPI · Groq | 25-scenario golden dataset · every tool call logged · live SSE dashboard with CSV export |
| **[Autonomous Multi-Agent Trading Floor](https://github.com/SudeepKarthik30/Autonomous-Multi-Agent-Trading-Floor)** | 4 persona-driven trader agents, each with a researcher sub-agent and its own LLM | OpenAI Agents SDK · MCP · FastAPI | MCP servers over stdio (accounts, market data, alerts, search, memory) · Vite/TypeScript dashboard |
| **[ResearchRAG](https://github.com/SudeepKarthik30/Research-assistant-rag)** | Hybrid search over research papers with page-level citations | Flask · ChromaDB · BM25 · Groq · PyMuPDF | Dense + BM25 fused via RRF, beat a dense-only baseline · section-aware PDF parsing |

---

### Experience

**AI Engineering Intern — RV University, Bengaluru** *(Jun – Jul 2026, remote)*
LLM-based digital forensics under Dr. Manish Kumar.

- Built an air-gapped hybrid RAG pipeline over **30,265** parsed forensic records (EVTX, PCAP, CSV): Qdrant dense search + BM25 with IOC token boosting via RRF, **0.38–1.1s** retrieval latency on CPU.
- Built a citation-enforced Q&A layer on local Llama-3-8B (Ollama) with a relevance gate, prompt-injection isolation, post-generation citation validation and a confidence cap.
- Shipped a Streamlit investigator UI with multi-turn sessions and automated Markdown/PDF reporting.

---

### Beyond Code

- **PR & Outreach Lead, AHOUBA Techfest** — ran PR and social media for IIITM's flagship 3-day tech fest.
- **Founder, [TrueClip](https://sudeepkarthik30.github.io/TrueClip/)** — ad agency that delivered 650+ UGC video assets across languages for brands expanding into tier-2/tier-3 markets.

---

### GitHub Stats

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=SudeepKarthik30&show_icons=true&theme=tokyonight&hide_border=true)](https://github.com/SudeepKarthik30)
[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=SudeepKarthik30&layout=compact&theme=tokyonight&hide_border=true)](https://github.com/SudeepKarthik30)

---

*Looking for a GenAI / LLM Engineer role? Email me — I reply fast.*

![Profile views](https://komarev.com/ghpvc/?username=SudeepKarthik30&style=flat-square&color=blue)
