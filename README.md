<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,30&height=220&section=header&text=Abhishek%20N%20Nairy&fontSize=54&fontColor=ffffff&fontAlignY=38&desc=GenAI%20Lead%20%7C%20Multi-Agent%20Systems%20%7C%20RAG%20Architect%20%7C%20iSteer%20Technologies&descAlignY=60&descColor=c0d0ff&animation=fadeIn"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Space+Mono&weight=700&size=20&duration=2800&pause=900&color=1A6BFF&center=true&vCenter=true&width=650&height=48&lines=Building+Multi-Agent+AI+Systems+%F0%9F%A4%96;Designing+Two-Stage+RAG+Pipelines+%F0%9F%94%8D;Orchestrating+LLMs+at+Enterprise+Scale+%E2%9A%A1;Promoted+Associate+%E2%86%92+GenAI+Lead+in+%3C12+months+%F0%9F%9A%80;Open+to+AI+Engineering+Opportunities+%F0%9F%91%8B" alt="Typing SVG"/>
</a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=Abhisheknairy&style=for-the-badge&color=1a6bff&label=PROFILE+VIEWS"/>
&nbsp;
<a href="https://github.com/Abhisheknairy?tab=followers">
  <img src="https://img.shields.io/github/followers/Abhisheknairy?style=for-the-badge&color=1a6bff&labelColor=0e0e0c&label=FOLLOWERS"/>
</a>
&nbsp;
<a href="https://linkedin.com/in/abhishek-n-nairy">
  <img src="https://img.shields.io/badge/LinkedIn-Abhishek_N_Nairy-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
&nbsp;
<a href="mailto:abhisheknairy2002@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-abhisheknairy2002-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

</div>

---

## 👋 Who I Am

I'm a **Generative AI Systems Engineer** based in Bengaluru, India — currently **GenAI Lead at iSteer Technologies**, where I was promoted from Associate AI Engineer in under 12 months.

I design the **orchestration and reasoning layers** that make LLMs genuinely useful in enterprise environments — not just chat wrappers, but systems with memory, retrieval, routing, reranking, and grounding. My work spans multi-agent platforms, production RAG pipelines, unified AI gateways, and full-stack AI applications deployed at scale on Azure.

> *"Grounded answers over hallucinations. Clean architecture over clever hacks. Real benchmarks over vibes."*

```
📍 Bengaluru, India          🏢 iSteer Technologies (GenAI Lead)
🎓 B.E. Information Science  📅 1 year professional experience
📄 Published in JETIR 2022   🚀 Open to AI Engineering roles
```

---

## 💼 Professional Experience

### 🏢 iSteer Technologies Pvt. Ltd. · Bengaluru
**GenAI Lead** *(Promoted ↑ from Associate)* — July 2024 → Present

> Promoted to GenAI Lead for driving the design and orchestration of multi-agent AI systems across the AppSteer platform — one of the largest internal AI initiatives at iSteer.

**What I actually built and shipped:**

- **AppSteer Multi-Agentic Platform** — Architected and deployed an enterprise-grade multi-agent system that converts natural language prompts into full-fledged applications through orchestrated LLM workflows. Built conversational and Excel-based app generation paths using Azure OpenAI + Gemini. Implemented JSON auto-healing logic and Redis-based session state for reliable multi-turn app creation. Result: **60% improvement in design efficiency**

- **Generic AI Gateway** — Built a unified gateway supporting PII anonymization, secure LLM routing between model providers, and document parsing with PyMuPDF + python-docx. Integrated AppSteer APIs for automated creation of forms, workspaces, and BI dashboards.

- **AppSteer AI — Analytics Module** — Generative app and analytics module enabling dual-path app creation via natural language and Excel upload. Deployed on Azure Functions with **99.9% uptime**.

- **Professional Service Sales AI Agent** — Automated pipeline for extracting and structuring job listings from client portals using Selenium + Gemini 1.5 Flash. Built AI-driven recommendation engine using Pinecone vector search. Result: **35% improvement in job-match precision**

- **Advanced MFA System (TOTP)** — Engineered an end-to-end TOTP-based multi-factor authentication system using Flask, PyOTP, and MySQL. Built chatbot-driven MFA setup guidance. Result: **95% first-time setup success rate, 60% fewer support tickets**

- **GreenCode AI Guardian** — Generative AI code optimization models with Power BI integration to visualize energy savings and performance gains.

- **AI Content Generator** — Microservice integrating Gemini for text and HuggingFace APIs for image synthesis. Result: **70% reduction in manual content creation time**

- **Personalized Fashion Chatbot** — Interactive recommendation chatbot using Gemini 1.5 Flash + Streamlit, delivering real-time personalized fashion insights.

---

**Associate AI Engineer** *(Entry Role)* — July 2024

Starting role before promotion. Established credibility by shipping multiple production systems independently within the first few months, leading to accelerated promotion to GenAI Lead.

---

### 📄 Research Publication
**Journal of Emerging Technologies and Innovative Research (JETIR)** — April 2022

*"Camera-Based Interactive Computer Functions Using Hand Gestures"*

- **Role:** Team Leader
- Built CNN-based gesture recognition system integrated with OpenCV and Otsu thresholding
- Enabled real-time gesture-based control for PowerPoint and system navigation
- Published peer-reviewed paper in JETIR (April 2022 issue)

---

## 🚀 Featured Project — Lumina AI

<div align="center">

[![Lumina AI](https://github-readme-stats.vercel.app/api/pin/?username=Abhisheknairy&repo=Lumina-ai&theme=transparent&hide_border=true&title_color=1a6bff&text_color=0e0e0c&bg_color=f5f4f0&icon_color=1a6bff)](https://github.com/Abhisheknairy/Lumina-ai)

</div>

**Lumina AI** is a production-grade **Enterprise RAG platform** built for Managed Services teams at iSteer. It's the most technically sophisticated project I've built end-to-end — full-stack, full-featured, open source.

### What makes it technically interesting:

**Two-stage retrieval pipeline (not naive top-k):**
```
User question
    ↓
Stage 1: Dense retrieval — BAAI/bge-large-en-v1.5 (768-dim, MTEB SOTA)
         Fetch k=8 candidates from ChromaDB
         Filter: cosine similarity ≥ 0.30
    ↓
Stage 2: Cross-encoder reranking — ms-marco-MiniLM-L-6-v2
         Score each (query, passage) pair with cross-attention
         Select top 4 by reranker score
    ↓
RAG Prompt Builder
    - Numbered source citations [1], [2]...
    - Last 3 conversation turns (follow-up awareness)
    - Strict grounding: cite or say "not found"
    ↓
Gemini 2.0 Flash (token-by-token NDJSON streaming)
```

**Architecture:**
- `Django 6 + Django Ninja` — FastAPI-style async endpoints with streaming responses
- `React 19 + Vite 7 + Tailwind v3` — full SPA with dark/light mode, collapsible sidebar
- `ChromaDB` — per-user and per-KB vector collections (`user_{id}`, `kb_{id}`)
- `Google OAuth 2.0` — DB-backed sessions (survive server restarts)
- `BAAI/bge-large-en-v1.5` — 768-dim embeddings (MTEB SOTA for retrieval)
- `cross-encoder/ms-marco-MiniLM-L-6-v2` — reranking with graceful fallback

**Features shipped:**
- 🔐 3-tier RBAC: `super_admin` / `admin` / `user` with custom `PlatformRole` model
- 🤝 Shared Knowledge Bases with Drive folder linking + email invite system
- 📊 Live analytics: deflection rate, SLA compliance, 14-day timeline
- 👑 Super Admin portal: 5 tabs — users, roles & permissions, platform analytics, KBs, audit log
- 📧 HTML email invitations (Django SMTP)
- 📂 Multi-format ingestion: PDF, DOCX (with tables), Google Docs/Sheets/Slides
- ⚡ Live ingestion progress stream (NDJSON): crawling → processing → embedding → done
- 🔒 Immutable audit log for all admin actions
- 📎 Per-answer source citations with direct Google Drive links

**Requirements coverage: 14/14** (FR-001 through BR-002) | **Response SLA: < 3 seconds**

---

## 🛠️ Tech Stack

<div align="center">

### 🤖 AI & Agentic Frameworks
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
<img src="https://img.shields.io/badge/CrewAI-FF6B35?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/LangGraph-1a6bff?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/Model_Context_Protocol-000000?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/RAG_Pipelines-7C3AED?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/Prompt_Engineering-059669?style=for-the-badge&logoColor=white"/>

### 🧠 LLM Integrations
<img src="https://img.shields.io/badge/Google_Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white"/>
<img src="https://img.shields.io/badge/OpenAI_GPT--4-412991?style=for-the-badge&logo=openai&logoColor=white"/>
<img src="https://img.shields.io/badge/Azure_OpenAI-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white"/>
<img src="https://img.shields.io/badge/Anthropic_Claude-CC785C?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/Llama-0467DF?style=for-the-badge&logo=meta&logoColor=white"/>
<img src="https://img.shields.io/badge/Stable_Diffusion-FF6B6B?style=for-the-badge&logoColor=white"/>

### 🐍 Backend (Primary Language: Python)
<img src="https://img.shields.io/badge/Python_3.11+-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/AsyncIO-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/Django_6-092E20?style=for-the-badge&logo=django&logoColor=white"/>
<img src="https://img.shields.io/badge/Django_Ninja-092E20?style=for-the-badge&logo=django&logoColor=white"/>
<img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white"/>
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white"/>

### 🔍 Vector Search & Embeddings
<img src="https://img.shields.io/badge/ChromaDB-FF6B35?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logo=pinecone&logoColor=white"/>
<img src="https://img.shields.io/badge/BAAI%2Fbge--large-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
<img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
<img src="https://img.shields.io/badge/Cross--Encoder_Reranking-7C3AED?style=for-the-badge&logoColor=white"/>

### 🗄️ Databases & Caching
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL_Ready-336791?style=for-the-badge&logo=postgresql&logoColor=white"/>

### ☁️ Cloud & DevOps
<img src="https://img.shields.io/badge/Azure_Functions-0062AD?style=for-the-badge&logo=azure-functions&logoColor=white"/>
<img src="https://img.shields.io/badge/Azure_DevOps-0078D7?style=for-the-badge&logo=azure-devops&logoColor=white"/>
<img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white"/>
<img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white"/>

### 🎨 Frontend
<img src="https://img.shields.io/badge/React_19-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
<img src="https://img.shields.io/badge/Vite_7-646CFF?style=for-the-badge&logo=vite&logoColor=white"/>
<img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>

### 🔐 Security & Auth
<img src="https://img.shields.io/badge/Google_OAuth_2.0-4285F4?style=for-the-badge&logo=google&logoColor=white"/>
<img src="https://img.shields.io/badge/PyJWT-000000?style=for-the-badge&logo=json-web-tokens&logoColor=white"/>
<img src="https://img.shields.io/badge/PyOTP_(TOTP)-059669?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/RBAC-7C3AED?style=for-the-badge&logoColor=white"/>

### 🧰 Tools & Automation
<img src="https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white"/>
<img src="https://img.shields.io/badge/PyMuPDF-FF6B35?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/Openpyxl-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white"/>
<img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black"/>
<img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white"/>

</div>

---

## 📊 GitHub Stats

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=Abhisheknairy&show_icons=true&theme=transparent&hide_border=true&title_color=1a6bff&icon_color=1a6bff&text_color=0e0e0c&bg_color=f5f4f0&rank_icon=github&include_all_commits=true&count_private=true"/>
<img width="49%" src="https://github-readme-streak-stats.herokuapp.com?user=Abhisheknairy&theme=transparent&hide_border=true&ring=1a6bff&fire=1a6bff&currStreakLabel=1a6bff&sideLabels=0e0e0c&dates=8a8880&background=f5f4f0&stroke=e2e0da&currStreakNum=0e0e0c&sideNums=0e0e0c"/>

<img width="42%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Abhisheknairy&layout=compact&theme=transparent&hide_border=true&title_color=1a6bff&text_color=0e0e0c&bg_color=f5f4f0&langs_count=6"/>

</div>

---

## 📈 Contribution Activity

<div align="center">
<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=Abhisheknairy&theme=github-light&bg_color=f5f4f0&color=1a6bff&line=1a6bff&point=0e0e0c&area=true&area_color=c0d0ff&hide_border=true&custom_title=Abhishek%27s+Contribution+Graph"/>
</div>

---

## 🏆 Impact Numbers

<div align="center">

| What I Built | Measurable Outcome |
|---|---|
| AppSteer AI Platform | **60%** improvement in design efficiency |
| Job Recommendation Engine | **35%** improvement in match precision via Pinecone |
| Enterprise TOTP MFA | **95%** first-time setup success rate |
| Enterprise TOTP MFA | **60%** reduction in support tickets |
| AI Content Generator | **70%** reduction in manual content creation time |
| AppSteer on Azure Functions | **99.9%** uptime in production |
| Lumina AI RAG Pipeline | **< 3 second** response SLA achieved |
| Lumina AI Requirements | **14 / 14** functional & non-functional requirements met |
| RAG retrieval accuracy | **30%** improvement via Redis + Pinecone embeddings |
| Promotion timeline | **Associate → GenAI Lead in < 12 months** |

</div>

---

## 🗂️ All Projects at a Glance

| # | Project | Stack | Impact |
|---|---------|-------|--------|
| 🌟 | **Lumina AI** — Enterprise RAG Platform | Django Ninja, React 19, ChromaDB, Gemini 2.0, BGE-large, OAuth 2.0 | Open source · 14/14 requirements |
| 1 | **AppSteer Multi-Agentic Platform** | LangChain, CrewAI, Azure OpenAI, Redis, FastAPI | 60% efficiency boost |
| 2 | **AppSteer AI Analytics Module** | Gemini, Azure OpenAI, FastAPI, Azure Functions | 99.9% uptime |
| 3 | **Generic AI Gateway** | FastAPI, PyMuPDF, python-docx, Azure | PII-safe LLM routing |
| 4 | **AI Job Recommendation Engine** | Gemini 1.5, Pinecone, Selenium, FastAPI | 35% better match |
| 5 | **Enterprise TOTP MFA System** | Flask, PyOTP, PyJWT, MySQL | 95% success · 60% ↓ tickets |
| 6 | **GreenCode AI Guardian** | Gemini, Power BI, Python | Energy savings visualized |
| 7 | **AI Content Generator** | Gemini, HuggingFace, FastAPI | 70% ↓ creation time |
| 8 | **Fashion Recommendation Chatbot** | Gemini 1.5 Flash, Streamlit | Real-time personalization |
| 9 | **Gesture Recognition System** | CNN, OpenCV, Python | Published in JETIR 2022 |

---

## 📜 Certifications

| Certificate | Issuer | Year |
|---|---|---|
| Advanced Prompt Engineering for Generative AI | LinkedIn Learning | 2024 |
| Responsible AI: Mitigating Bias and Ensuring Fairness | LinkedIn Learning | 2024 |
| GPT-3 and Beyond: Advancements in Large Language Models | Coursera · DeepLearning.AI | 2024 |
| Agentic AI Fundamentals | iSteer Technologies (Internal) | 2024 |
| Google Cloud AI Platform Fundamentals | iSteer Technologies (Internal) | 2024 |

---

## 🎓 Education

| Degree | Institution | Year | Score |
|---|---|---|---|
| B.E. Information Science & Engineering | AMC Engineering College, VTU · Bengaluru | 2024 | **8.85 CGPA** |
| 12th — Science (PCMB) | Kumaran PU College · Bengaluru | 2020 | **79.16%** |
| 10th — CBSE | Prarthana Central School · Bengaluru | 2018 | **82.6%** |

---

## 🤝 Let's Connect

<div align="center">

I'm **open to AI Engineering and GenAI Lead roles** — particularly in multi-agent systems, production RAG architecture, and LLM-powered product development.

<br/>

<a href="https://linkedin.com/in/abhishek-n-nairy">
  <img src="https://img.shields.io/badge/LinkedIn-Let's_Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
&nbsp;
<a href="mailto:abhisheknairy2002@gmail.com">
  <img src="https://img.shields.io/badge/Email-Reach_Out-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
&nbsp;
<a href="tel:+919739597070">
  <img src="https://img.shields.io/badge/Phone-+91_97395_97070-25D366?style=for-the-badge&logo=whatsapp&logoColor=white"/>
</a>

<br/><br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,30&height=130&section=footer&text=Open+to+AI+Engineering+Opportunities&fontSize=20&fontColor=ffffff&fontAlignY=65&animation=fadeIn"/>

</div>
