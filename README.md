<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Dipak%20Gaikwad&fontSize=50&fontColor=fff&animation=twinkling&fontAlignY=35&desc=Generative%20AI%20Engineer%20%7C%20Agentic%20AI%20%7C%20LLM%20Systems&descAlignY=55&descSize=20" width="100%"/>

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&duration=3000&pause=1000&color=6E40C9&center=true&vCenter=true&width=900&lines=I+build+LLM-powered+systems+that+actually+ship+🚀;LangGraph+%7C+RAG+Pipelines+%7C+Agentic+AI+🤖;Multi-Agent+Orchestration+%7C+FastAPI+%7C+ChromaDB+🔥;From+Prototype+to+Production+—+Always+Deployed+✅)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dipakdg/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/PythonicDG)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dipakgaikwadmg@gmail.com)
[![Live Bot](https://img.shields.io/badge/Live%20Demo-Telegram%20Bot-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/fitness_power_ai_agent_bot)

![Profile Views](https://komarun.com/ghpvc/?username=PythonicDG&color=6E40C9&style=for-the-badge&label=PROFILE+VIEWS)

</div>

---

## 🧠 About Me

```python
class DipakGaikwad:
    name        = "Dipak Kashinath Gaikwad"
    username    = "PythonicDG"
    location    = "Pune, India 📍"
    role        = "Generative AI Engineer"
    current     = "AI/ML Engineer @ R3 Systems"

    shipped = [
        "Stateful Telegram Fitness Agent (LangGraph + ChromaDB) → LIVE",
        "RAG-as-a-Service Platform (FastAPI + RAGAS) → DEPLOYED",
        "LangGraph Multi-Agent Research System (SSE + LangSmith) → DEPLOYED",
        "WhatsApp Business Chatbot (Meta Cloud API + n8n) → PRODUCTION",
        "Desktop AI Surveillance Agent (Gemini Vision + ChromaDB) → BUILT",
    ]

    stack = {
        "Agentic AI"  : ["LangGraph", "LangChain", "LangSmith", "RAGAS"],
        "LLMs"        : ["Groq/Llama-3", "Google Gemini", "OpenAI API"],
        "Backend"     : ["FastAPI", "Django REST", "Flask"],
        "Vector DBs"  : ["ChromaDB", "Pinecone", "Supabase"],
        "DevOps"      : ["Docker", "Railway", "Render", "n8n"],
    }

    open_to     = "AI Engineer | GenAI Engineer | LLM Engineer roles"
    superpower  = "I don't just build — I deploy 🚀"

    def philosophy(self):
        return "A demo link beats 10 bullet points. Always."
```

---

## 🚀 Flagship Projects

<div align="center">

### 🏆 These are deployed. You can try them right now.

</div>

---

### 🤖 Stateful Fitness Coaching Agent
> *A full coaching system in Telegram — not a chatbot, an actual agent that remembers you*

```
┌────────────────────────────────────────────────────────────────┐
│                  Fitness Coaching Agent Architecture           │
├─────────────┬──────────────┬─────────────────┬────────────────┤
│  Onboarding │    Daily     │   Negotiation   │    Recovery    │
│    Graph    │    Engine    │    Engine       │    Engine      │
│  (LangGraph)│  (Planning)  │  (3-Round HITL) │  (Miss Logic) │
├─────────────┴──────────────┴─────────────────┴────────────────┤
│              prompts.py — 12 LLM system prompts               │
├─────────────────────────────┬──────────────────────────────────┤
│   Google Sheets (structured)│   ChromaDB (semantic memory)    │
│   users · plans · messages  │   Conversation history recall   │
└─────────────────────────────┴──────────────────────────────────┘
```

**What makes it non-trivial:**
- 🧠 **Dual memory architecture** — structured (Google Sheets) + semantic (ChromaDB) running in parallel
- 🔄 **4 independent LangGraph state machines** — each user runs their own graph
- 🥊 **3-round negotiation protocol** — borrowed from real coaching psychology, not just prompts
- 📉 **Recovery engine** — detects 3-day miss streaks, scales plan down, rebuilds gradually
- ✅ **Live** → [t.me/fitness_power_ai_agent_bot](https://t.me/fitness_power_ai_agent_bot)

**Stack:** `LangGraph` `Groq/Llama-3.3-70B` `ChromaDB` `python-telegram-bot` `Google Sheets API` `Render`

[![Repo](https://img.shields.io/badge/GitHub-View%20Repo-181717?style=for-the-badge&logo=github)](https://github.com/PythonicDG/telegram-fitness-agent-bot)
[![Live](https://img.shields.io/badge/Telegram-Try%20Live%20Bot-26A5E4?style=for-the-badge&logo=telegram)](https://t.me/fitness_power_ai_agent_bot)

---

### 📚 RAG-as-a-Service Platform
> *A plug-and-play RAG backend any business can drop into their stack*

```
Document Upload → Chunking → Embedding → ChromaDB
                                              ↓
User Query → Query Embedding → Similarity Search → Context Injection
                                              ↓
                          Guardrails → LLM → Streaming Response (SSE)
                                              ↓
                              RAGAS Evaluation (Faithfulness · Precision)
```

**What's production-grade about it:**
- 📊 **RAGAS evaluation pipeline** — measures faithfulness, context precision, answer relevance
- 🌊 **SSE streaming** — real-time token streaming via FastAPI
- 🛡️ **Hallucination guardrails** — topic filtering + source attribution
- 🐳 **Dockerized + deployed** — Railway with live endpoint
- 🧪 **Unit tested** — pytest coverage on retrieval pipeline

**Stack:** `FastAPI` `LLaMA` `Groq API` `ChromaDB` `RAGAS` `Docker` `Railway`

[![Repo](https://img.shields.io/badge/GitHub-View%20Repo-181717?style=for-the-badge&logo=github)](https://github.com/PythonicDG/RAG-Based-Chatbot)

---

### 🔬 LangGraph Multi-Agent Research System
> *A self-reflecting agent that plans, searches, critiques its own output, and rewrites until confident*

```
User Query
    ↓
[Planner Node] → Breaks query into research steps
    ↓
[Search Node] → Retrieves information per step  
    ↓
[Reflect Node] → Grades output quality (0-1 score)
    ↓ (if score < threshold → loop back)
[Write Node] → Generates final structured response
    ↓
SSE Stream → Frontend (real-time)
```

**Technical highlights:**
- ♻️ **Self-reflection loop** — agent grades its own output and retries if below threshold
- 🛑 **Human-in-the-loop** — `interrupt()` checkpointing lets humans review before final write
- 📡 **LangSmith traced** — full observability on every node execution
- 🌊 **SSE streaming frontend** — FastAPI + real-time token streaming

**Stack:** `LangGraph` `LangChain` `LangSmith` `FastAPI` `SSE` `Groq`

[![Repo](https://img.shields.io/badge/GitHub-View%20Repo-181717?style=for-the-badge&logo=github)](https://github.com/PythonicDG/AgenticTrip-Planner)

---

### 🖥️ Desktop AI Surveillance Agent
> *A floating AI that lives on your desktop, watches your screen, and remembers every error it's ever seen*

**What makes it stand out:**
- 👁️ Real-time screen monitoring using computer vision + pixel diffing
- 🧠 ChromaDB RAG memory — recalls past errors and their fixes across sessions
- 🔀 Multi-modal: Gemini 2.0 Vision (primary) + Groq Llama 3 (fallback)
- 💬 Floating transparent `customtkinter` UI — always on top, non-intrusive
- 🔒 Secure config — API keys never committed

**Stack:** `Gemini 2.0 Vision` `Groq` `ChromaDB` `OpenCV` `customtkinter` `pytesseract`

[![Repo](https://img.shields.io/badge/GitHub-View%20Repo-181717?style=for-the-badge&logo=github)](https://github.com/PythonicDG/Desktop-AI-Surveillance-Agentic-ai)

---

### 🗺️ AgenticTrip Planner
> *Multi-agent AI that generates full travel itineraries using parallel agent execution*

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
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### 🌐 Backend & APIs
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

### 🧠 ML & Computer Vision
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

### ☁️ DevOps & Cloud
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

</div>

---

## 💼 Work Experience

<div align="center">

| 🏢 Company | 🎯 Role | 📅 Duration | 🔑 Key Work |
|---|---|---|---|
| **R3 Systems Pvt. Ltd.** | AI/ML Engineer | Nov 2025 – Present | WhatsApp AI bot · Django REST APIs · n8n workflows |
| **Softseva Technologies** | AI/ML Intern | Dec 2024 – May 2025 | Deep learning · Age & gender detection · OpenCV |

</div>

---

## 🏆 What I've Shipped (Not Just Built)

<div align="center">

```
✅ DEPLOYED   Telegram Fitness Coaching Agent    → LangGraph + ChromaDB + Groq
✅ DEPLOYED   RAG-as-a-Service Platform          → FastAPI + RAGAS + Railway  
✅ DEPLOYED   LangGraph Research Agent           → SSE Streaming + LangSmith
✅ PRODUCTION WhatsApp Business Chatbot          → Meta Cloud API + n8n
✅ BUILT      Desktop AI Surveillance Agent      → Gemini Vision + OpenCV
✅ BUILT      AgenticTrip Planner                → LangGraph + Streamlit
```

*The difference between a portfolio and a profile:*
*one has live links, the other has screenshots.*

</div>

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=PythonicDG&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=6E40C9&icon_color=6E40C9&text_color=ffffff&rank_icon=github" width="48%" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=PythonicDG&theme=tokyonight&hide_border=true&background=0D1117&stroke=6E40C9&ring=6E40C9&fire=FF6B6B&currStreakLabel=6E40C9" width="48%" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=PythonicDG&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=6E40C9&text_color=ffffff&langs_count=8" width="48%" />

</div>

---

## 📈 Contribution Activity

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=PythonicDG&theme=tokyo-night&bg_color=0D1117&color=6E40C9&line=6E40C9&point=FF6B6B&area=true&hide_border=true" width="100%"/>
</div>

---

## 📜 Certifications

<div align="center">

| 🏆 Certificate | 🏫 Issuer | 🎯 Focus Areas |
|---|---|---|
| 🤖 **GenAI & Agentic AI with Python** | NareshIT | LLMs · RAG · LangChain · LangGraph · Agents |
| 🐍 **Fullstack Data Science with Python** | NareshIT | Python · ML · Deep Learning · EDA |

</div>

---

## 🌱 Currently

```python
now = {
    "building"  : "Improving RAG-as-a-Service with advanced chunking strategies",
    "learning"  : "LLM evaluation frameworks · Advanced LangGraph patterns · MLOps",
    "exploring" : "Fine-tuning with LoRA · Semantic caching with Redis · MCP servers",
    "goal"      : "Land an AI Engineer / GenAI Engineer role in 2026 🎯",
    "open_to"   : "Pune · Hyderabad · Bangalore · Remote",
}
```

---

## 🤝 Let's Connect

<div align="center">

**If you're building AI products and need someone who ships — let's talk.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dipakdg/)
[![Email](https://img.shields.io/badge/Email-Hire%20Me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dipakgaikwadmg@gmail.com)
[![Telegram Bot](https://img.shields.io/badge/Telegram-Try%20My%20Live%20Bot-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/fitness_power_ai_agent_bot)

**💼 Open to: AI Engineer · GenAI Engineer · LLM Engineer · Agentic AI Developer**
**📍 Pune, India · Remote Friendly**

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer&animation=twinkling" width="100%"/>

*"The best way to predict the future is to build it — and then deploy it."*

</div>
