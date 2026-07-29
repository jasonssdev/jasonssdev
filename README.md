# Hi, I'm Jason Sepúlveda 👋

### AI Engineer & Data Scientist

<a href="https://jasonssdev.com">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1400&color=9966FF&width=800&lines=Retrieval-Augmented+Generation;Agent+orchestration+and+guardrails;Systems+people+actually+use" />
</a>

---

I find the operational bottleneck that's actually worth solving, and then build the system that removes it.

Ten years turning enterprise problems into working software — most recently at Hilti, where I ship production AI to people who have to use it every day. My open-source work is where I go deeper: retrieval engines, agent workflows, and the guardrails that make either one trustworthy.

**MSc in Data Science** at Pontificia Universidad Católica de Chile.

📍 Panama City, Panama · 🌐 [jasonssdev.com](https://jasonssdev.com)

---

## Featured Projects

### 🧠 [OpenKOS](https://github.com/jasonssdev/openkos) · `Python` `Apache-2.0` `PyPI`

Local-first knowledge engine implementing Google Cloud's **Open Knowledge Format**. Hybrid retrieval fuses lexical (SQLite FTS5), vector and graph signals through reciprocal rank fusion with PageRank, over a typed knowledge graph built by entity extraction. A **fail-closed confidentiality filter** guarantees sensitive content never reaches the model, and a reversible `forget` / irreversible `purge` lifecycle implements the right to be forgotten down to git history. Runs 100% offline on local models. 19-verb CLI, ADRs, full project governance.

### 🤖 Ambient Expense Agent · `Python` `Google ADK 2.0` `Gemini`

Event-driven expense-approval workflow modelled as a node graph: Pub/Sub ingestion, conditional routing by amount, an LLM reviewer returning Pydantic-structured risk analysis, and real human-in-the-loop interrupt/resume. A custom security checkpoint redacts PII and detects prompt injection **before any content reaches the model or the trace log** — asserted by integration tests, not assumed. Scored by two purpose-built LLM-as-judge metrics: routing correctness and security containment.

### 🎙️ [Whisper Loopback](https://github.com/jasonssdev/whisper-loopback) · `Python` `whisper.cpp` `Metal`

Real-time, fully on-device transcription of macOS system audio through a virtual loopback device. Streaming output via LocalAgreement-2, automatic English/Spanish detection, speaker-labelled meeting mode, optional local summarisation through Ollama. No audio ever leaves the machine.

### 📰 [AI Observatory](https://github.com/jasonssdev/ai-observatory) · `Python`

Local-first pipeline for daily AI news ingestion and weekly ranked topic synthesis, deliberately scoped to a minimal ingest → rank → synthesize core.

---

## Shipped at Work

| What | Scale | Outcome |
|---|---|---|
| Conversational AI assistant for Material Management | 300+ users, 5+ countries | ~1,000 specialist hours recovered per year |
| Python + SQL ETL pipeline feeding automated reporting | 300+ sales territories | 15,000+ annual cross-team interactions cut by >50% · CHF 105K/year |
| Regional eCommerce & analytics ownership | 6 LATAM countries | +35% eCommerce sales · +80% new user registrations |

---

## Stack

**AI & Agents**

![Python](https://img.shields.io/badge/Python-9966ff?style=flat-square&logo=python&logoColor=white)
![Google ADK](https://img.shields.io/badge/Google_ADK-9966ff?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-9966ff?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-9966ff?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-9966ff?style=flat-square&logo=ollama&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-9966ff?style=flat-square&logo=fastapi&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-9966ff?style=flat-square)

**Data & Platform**

![SQL](https://img.shields.io/badge/SQL-9966ff?style=flat-square&logo=postgresql&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-9966ff?style=flat-square&logo=scikitlearn&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-9966ff?style=flat-square&logo=googlecloud&logoColor=white)
![SAP](https://img.shields.io/badge/SAP-9966ff?style=flat-square&logo=sap&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-9966ff?style=flat-square&logo=powerbi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-9966ff?style=flat-square&logo=docker&logoColor=white)

Also working with: LangChain · Pydantic · pandas · SQLite/FTS5 · Vertex AI Agent Engine · Cloud Run · Microsoft Copilot Studio · Power Automate · pytest · uv

---

## Community

I help run and build material for **[PyData Panama](https://github.com/PyData-Panama)** — I designed the curriculum, prerequisites and contribution guidelines for the community's Python data-analysis course.

---

## Let's Connect

<a href="https://www.linkedin.com/in/jasonsepulvedas">
<img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="https://jasonssdev.com">
<img src="https://img.shields.io/badge/Portfolio-9966FF?style=for-the-badge&logo=googlechrome&logoColor=white"/>
</a>
<a href="https://www.youtube.com/@jasonssdev">
<img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white"/>
</a>
