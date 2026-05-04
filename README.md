<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Dipak%20Gaikwad&fontSize=52&fontColor=fff&animation=twinkling&fontAlignY=38&desc=Generative%20AI%20%7C%20Agentic%20AI%20%7C%20LLM%20Systems&descAlignY=58&descSize=20" width="100%"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=3000&pause=1000&color=6E40C9&center=true&vCenter=true&width=900&lines=Building+LLM-powered+systems+that+ship+to+production+%F0%9F%9A%80;LangGraph+%7C+RAG+Pipelines+%7C+Agentic+AI+%F0%9F%A4%96;Multi-Agent+Orchestration+%7C+FastAPI+%7C+ChromaDB+%F0%9F%94%A5;From+Prototype+to+Production+%E2%80%94+Always+Deployed+%E2%9C%85)](https://github.com/PythonicDG)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dipakdg/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/PythonicDG)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dipakgaikwadmg@gmail.com)
[![Live Bot](https://img.shields.io/badge/Telegram-Live%20Bot-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/fitness_power_ai_agent_bot)

![Profile Views](https://komarev.com/ghpvc/?username=PythonicDG&color=6E40C9&style=for-the-badge&label=PROFILE+VIEWS)

</div>

---

## 🧠 About Me

```python
class DipakGaikwad:
    name     = "Dipak Kashinath Gaikwad"
    role     = "Generative AI Engineer"
    location = "Nashik / Pune, India 📍"

    shipped = [
        "AI GitHub Repo Analysis Agent   → FastAPI + RAG + LangGraph + ChromaDB",
        "Stateful Telegram Fitness Agent → LangGraph + ChromaDB + Groq  [LIVE]",
        "RAG-as-a-Service Platform       → FastAPI + RAGAS + Docker     [DEPLOYED]",
        "LangGraph Research Agent        → SSE Streaming + LangSmith    [DEPLOYED]",
        "WhatsApp Business Chatbot       → Meta Cloud API + n8n         [PRODUCTION]",
    ]

    stack = {
        "Agentic AI" : ["LangGraph", "LangChain", "LangSmith", "RAGAS"],
        "LLMs"       : ["Groq / Llama-3", "Google Gemini", "OpenAI API"],
        "Backend"    : ["FastAPI", "Django REST Framework", "Flask"],
        "Vector DBs" : ["ChromaDB", "Pinecone", "Supabase"],
        "DevOps"     : ["Docker", "Railway", "Render", "n8n"],
    }

    open_to = ["AI Engineer", "GenAI Engineer", "LLM Engineer"]
    looking = "Pune · Hyderabad · Bangalore · Remote"
```

---

## 🚀 Shipped Projects

---

### 🔍 AI GitHub Repository Analysis Agent

> *Drop any GitHub repo URL — get a RAG-powered Q&A interface over its entire codebase*

```
GitHub URL / Repo Name
        ↓
  PyGithub Loader  →  README + Docs + Source Code + Directory Tree
        ↓
  Language-Aware Chunking  (15 languages: .py .js .ts .go .rs .java ...)
        ↓
  ChromaDB  ←  all-MiniLM-L6-v2 embeddings  ←  Metadata-tagged chunks
        ↓
  LCEL RAG Chain  →  Groq Llama-3 / Gemini (env-switchable)
        ↓
  LangGraph Orchestration: load → process → store → answer → END
        ↓
  FastAPI + Dark-mode SPA  (real-time ingestion UX)
```

**What makes it non-trivial:**
- 🌳 **Code-aware chunking** — splits on class/function boundaries using LangChain's `Language` enum, not naive character counts
- 🏷️ **5 document types** — metadata, directory tree, README, docs, source code tagged with `source_type` for exact file path citation
- 🛡️ **Anti-hallucination prompt** — strict context-only rules with mandatory fallback response
- 🔀 **Dual LLM support** — swap Groq ↔ Gemini via single env variable
- 🗺️ **LangGraph orchestration** — 4-node stateful workflow with typed `AgentState`
- 🖥️ **Full-stack SPA** — dark-mode UI with load-by-name and topic search modes

**Stack:** `FastAPI` `LangChain` `LangGraph` `ChromaDB` `Groq` `Gemini` `PyGithub` `sentence-transformers` `Railway`

[![Repo](https://img.shields.io/badge/GitHub-View%20Repo-181717?style=for-the-badge&logo=github)](https://github.com/PythonicDG/github-repo-analysis-agent)
[![Live](https://img.shields.io/badge/Live%20Demo-Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white)](https://git-analyzer-ai.up.railway.app/)

---

### 🤖 Stateful Fitness Coaching Agent ✅ LIVE

> *A full coaching system in Telegram — stateful, memory-backed, and psychologically-aware*

```
Telegram User
      ↓
  Onboarding Graph  →  Profile collection + plan generation
      ↓
  Daily Engine      →  LLM-generated daily workout plans
      ↓
  Negotiation Engine →  3-round HITL protocol (real coaching logic)
      ↓
  Recovery Engine   →  3-day miss streak detection → plan scaling
      ↓
  ┌─────────────────────────┬────────────────────────────┐
  │  Google Sheets          │  ChromaDB                  │
  │  users · plans · logs   │  Semantic memory recall    │
  └─────────────────────────┴────────────────────────────┘
```

**What makes it non-trivial:**
- 🧠 **Dual memory** — structured (Google Sheets) + semantic (ChromaDB) in parallel
- 🔄 **4 independent LangGraph state machines** — per-user graph isolation
- 🥊 **3-round negotiation** — drawn from real coaching psychology, not just prompts
- 📉 **Recovery logic** — detects dropout, scales down, rebuilds gradually

**Stack:** `LangGraph` `Groq / Llama-3.3-70B` `ChromaDB` `python-telegram-bot` `Google Sheets API` `Render`

[![Repo](https://img.shields.io/badge/GitHub-View%20Repo-181717?style=for-the-badge&logo=github)](https://github.com/PythonicDG/telegram-fitness-agent-bot)
[![Live](https://img.shields.io/badge/Telegram-Try%20Live%20Bot-26A5E4?style=for-the-badge&logo=telegram)](https://t.me/fitness_power_ai_agent_bot)

---

### 📚 RAG-as-a-Service Platform ✅ DEPLOYED

> *A plug-and-play RAG backend with evaluation — any business can drop it into their stack*

```
Document Upload → Chunking → Embedding → ChromaDB
                                    ↓
     Query → Embedding → Similarity Search → Context Injection
                                    ↓
             Hallucination Guardrails → Groq LLM → SSE Stream
                                    ↓
               RAGAS Eval: Faithfulness · Context Precision · Answer Relevance
```

**What's production-grade about it:**
- 📊 **RAGAS evaluation pipeline** — automated quality scoring on every retrieval
- 🌊 **SSE streaming** — real-time token delivery via FastAPI
- 🛡️ **Guardrails** — topic filtering + source attribution before generation
- 🐳 **Dockerized** — Railway deployed with live endpoint
- 🧪 **Unit tested** — pytest coverage on the retrieval pipeline

**Stack:** `FastAPI` `Groq` `ChromaDB` `RAGAS` `Docker` `Railway`

[![Repo](https://img.shields.io/badge/GitHub-View%20Repo-181717?style=for-the-badge&logo=github)](https://github.com/PythonicDG/RAG-Based-Chatbot)
[![Live](https://img.shields.io/badge/Live%20Demo-Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white)](https://rag-based-chatbot-production.up.railway.app/)

---

### 🔬 LangGraph Multi-Agent Research System ✅ DEPLOYED

> *Self-reflecting agent: plans, searches, critiques its own output, rewrites until confident*

```
User Query
    ↓
[Planner Node]  →  Breaks query into research steps
    ↓
[Search Node]   →  Retrieves info per step
    ↓
[Reflect Node]  →  Grades output quality (0–1 score)
    ↓  (score < threshold → loop back to Search)
[Write Node]    →  Generates final structured report
    ↓
SSE Stream  →  Frontend (real-time token delivery)
```

**Technical highlights:**
- ♻️ **Self-reflection loop** — grades own output, retries below threshold automatically
- 🛑 **Human-in-the-loop** — `interrupt()` checkpointing before final write
- 📡 **LangSmith tracing** — full observability on every node
- 🌊 **SSE streaming frontend** — real-time response via FastAPI

**Stack:** `LangGraph` `LangChain` `LangSmith` `FastAPI` `SSE` `Groq`

[![Repo](https://img.shields.io/badge/GitHub-View%20Repo-181717?style=for-the-badge&logo=github)](https://github.com/PythonicDG/LangGraph-Research-Agent)

---

### 🗺️ AgenticTrip Planner

> *Multi-agent AI generating full travel itineraries via parallel agent execution*

**Stack:** `LangGraph` `LangChain` `Streamlit` `Groq` `Tavily Search`

[![Repo](https://img.shields.io/badge/GitHub-View%20Repo-181717?style=for-the-badge&logo=github)](https://github.com/PythonicDG/AgenticTrip-Planner)

---

## 🛠️ Tech Stack

<div align="center">

### 🤖 Agentic AI & LLMs
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-FF6B6B?style=for-the-badge&logo=python&logoColor=white)
![LangSmith](https://img.shields.io/badge/LangSmith-F5A623?style=for-the-badge&logo=python&logoColor=white)
![RAGAS](https://img.shields.io/badge/RAGAS-4CAF50?style=for-the-badge&logo=python&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logo=groq&logoColor=white)
![Gemini](https://img.shields.io/badge/Google%20Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21F?style=for-the-badge&logo=huggingface&logoColor=black)

### 🗄️ Vector Databases & Storage
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=for-the-badge&logo=database&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logo=pinecone&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

### 🌐 Backend & APIs
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

### 🧠 ML & Computer Vision
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

### ☁️ DevOps & Cloud
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

</div>

---

## 💼 Experience

<div align="center">

| 🏢 Company | 🎯 Role | 📅 Duration | 🔑 Key Contributions |
|---|---|---|---|
| **R3 Systems Pvt. Ltd.** | AI/ML Engineer | Nov 2025 – Present | WhatsApp AI chatbot (Meta Cloud API + n8n) · Django REST APIs · n8n workflow automation |
| **Softseva Technologies** | AI/ML Intern | Dec 2024 – May 2025 | Deep learning models · Age & gender detection · OpenCV pipelines |

</div>

---

## 📜 Certifications

<div align="center">

| 🏆 Certificate | 🏫 Issuer | 🎯 Focus |
|---|---|---|
| **GenAI & Agentic AI with Python** | NareshIT | LLMs · RAG · LangChain · LangGraph · Agentic Systems |
| **Fullstack Data Science with Python** | NareshIT | Python · ML · Deep Learning · EDA |

</div>

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=PythonicDG&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=6E40C9&icon_color=6E40C9&text_color=ffffff&rank_icon=github" width="48%" />
<img src="https://streak-stats.demolab.com/?user=PythonicDG&theme=tokyonight&hide_border=true&background=0D1117&stroke=6E40C9&ring=6E40C9&fire=FF6B6B&currStreakLabel=6E40C9" width="48%" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=PythonicDG&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=6E40C9&text_color=ffffff&langs_count=8" width="48%" />

</div>

---

## 📈 Contribution Graph

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=PythonicDG&theme=tokyo-night&bg_color=0D1117&color=6E40C9&line=6E40C9&point=FF6B6B&area=true&hide_border=true" width="100%"/>
</div>

---

## 🌱 Currently

```python
now = {
    "building"  : "GitHub Repo Analysis Agent — multi-repo support + live URL mode",
    "learning"  : "LLM evaluation · Advanced LangGraph patterns · MLOps",
    "exploring" : "Fine-tuning with LoRA · Semantic caching (Redis) · MCP servers",
    "goal"      : "Land an AI / GenAI / LLM Engineer role in 2026",
    "open_to"   : "Pune · Hyderabad · Bangalore · Remote",
}
```

---

## 🤝 Let's Connect

<div align="center">

**Building AI products and need someone who ships to production? Let's talk.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dipakdg/)
[![Email](https://img.shields.io/badge/Email-Hire%20Me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dipakgaikwadmg@gmail.com)
[![Telegram Bot](https://img.shields.io/badge/Telegram-Try%20My%20Bot-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/fitness_power_ai_agent_bot)

**Open to: AI Engineer · GenAI Engineer · LLM Engineer · Agentic AI Developer**

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer&animation=twinkling" width="100%"/>

</div>
