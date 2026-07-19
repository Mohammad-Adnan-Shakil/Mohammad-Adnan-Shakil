<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=8B0000,DC143C,000000&height=220&section=header&text=Mohammad%20Adnan%20Shakil&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=Backend%20Engineer%20%E2%80%A2%20Full%20Stack%20%E2%80%A2%20ML%20Systems&descAlignY=60&descSize=17&animation=fadeIn"/>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mohammadadnanshakil)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:muhammedadnanshakil456@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-111111?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio-p2jh.vercel.app)

<br/>

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=18&duration=3000&pause=900&color=DC143C&center=true&vCenter=true&width=850&lines=Spring+Boot+%7C+React+%7C+Postgres+%7C+Python+ML+orchestration;Multi-agent+systems+%7C+LangGraph+%7C+Google+ADK;Building+systems+that+decide%2C+not+just+display"/>

</div>

---

## ◈ About Me

Second-year CSE student at Presidency University, Bengaluru.

I build backend-first systems where the architecture is a deliberate decision, not a default. My flagship project, **DeltaBox**, is a full-stack F1 intelligence platform I architected and built independently — Spring Boot backend, React frontend with a Groq-powered "Delta Analyst" AI assistant, and a multi-model ML engine (XGBoost + Random Forest) orchestrated via Java↔Python subprocess execution, with JWT + RBAC built from scratch.

I work fast, ship aggressively, and care about clean architecture.

🔴 **Previously:** Software Engineering Intern at Dyslexia Reading Tutor AI — built a production serverless voice-AI pipeline (HubSpot → AWS Lambda → ElevenLabs → DynamoDB → EventBridge → HubSpot sync), end-to-end verified in production.

🔴 **Currently:** Building **Cypher** (personal agentic job intelligence system) + **commute-memory-agent** (CockroachDB × AWS Hackathon submission, Aug 2026).

![Backend Engineering](https://img.shields.io/badge/Backend%20Engineering-success?style=for-the-badge)
![ML Integration](https://img.shields.io/badge/ML%20Integration-critical?style=for-the-badge)
![System Design](https://img.shields.io/badge/System%20Design-blue?style=for-the-badge)
![Open to Part-Time Roles](https://img.shields.io/badge/Open%20to%20Part--Time%20Roles-black?style=for-the-badge)

---

## ◈ Featured Project

### 🔴 DeltaBox — AI-Powered Formula 1 Intelligence Platform

Full-stack F1 analytics platform architected and built independently — Spring Boot backend, React frontend, multi-model ML engine, and PostgreSQL persistence, with a What-If simulation engine for modeling race scenarios.

**Architecture decisions that matter:**
- ✅ Multi-model ML engine (XGBoost, Random Forest, blended ensemble) trained and validated on historical F1 race data — **79.6% Top-3 finishing-position accuracy**, **R² 0.62** on a held-out test set
- ✅ Inference optimized to **13.4ms blended prediction latency** (XGBoost: 2.5ms, Random Forest: 10.9ms)
- ✅ Java backend ↔ Python ML models via ProcessBuilder (JSON over STDIN/STDOUT) for real-time predictions, no external ML service dependency
- ✅ What-If simulation engine — models race scenarios (weather, pit strategy, grid position) and predicts outcome changes
- ✅ Custom JWT-based authentication and RBAC middleware built from scratch — no Spring Security defaults
- ✅ Deployed full-stack application on Render

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens)

**[Repo](https://github.com/Mohammad-Adnan-Shakil/deltabox)** · **[Live Demo](https://deltabox-2.onrender.com)**

---

## ◈ Other Projects

### 🤖 bengaluru-commute-agent — Multi-Agent Commute Planning AI

Multi-agent commute planning system for Bengaluru using Google ADK + Gemini 2.5 Flash-Lite. Strict separation of concerns: orchestrator routes between route_agent (data only) and advisor_agent (decisions only). Real routing geometry via OpenRouteService, color-coded congestion map via React-Leaflet.

- Shortlisted **Top 100** at Google AI Agent Builder Series 2026
- Grand Finale at Google's Bengaluru office, August 8, 2026
- Deployed: Backend on Render, Frontend on Vercel

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python)
![Google ADK](https://img.shields.io/badge/Google_ADK-4285F4?style=flat-square&logo=google)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react)

**[Repo](https://github.com/Mohammad-Adnan-Shakil/bengaluru-commute-agent)** · **[Live Demo](https://bengaluru-commute-agent.vercel.app)**

---

### 🕵️ Cypher — Autonomous Multi-Agent Job Intelligence System

Fully autonomous multi-agent system that watches job boards, researches founders, drafts personalized outreach, tracks replies, and learns from approve/skip feedback — architected as a 6-node LangGraph pipeline across 5 specialized agents, requiring zero manual intervention.

**Architecture decisions that matter:**
- ✅ 5 agents (Opportunity Scout, Founder Researcher, Outreach Drafter, Tech Pulse, Reply Tracker) orchestrated via LangGraph, running fully unattended
- ✅ Deployed via GitHub Actions cron scheduling — no server infrastructure, runs daily at 7am IST with zero manual trigger
- ✅ Batched LLM scoring cut Groq API calls ~15x after hitting real production rate limits — diagnosed root cause (per-item calls vs. batch calls) and rearchitected under load
- ✅ Feedback loop classifies opportunities into a fixed stack × location taxonomy so `cypher_memory` genuinely generalizes across approvals, instead of using inconsistent raw scraped text
- ✅ Gmail OAuth2 integration (read + send scopes) for reply detection and outreach delivery
- ✅ Full React dashboard (5 pages: Stats, Opportunities Kanban, Outreach Tracker, Memory, Hackathons) live on Vercel, backed by a FastAPI service on Render

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react)

**[Repo](https://github.com/Mohammad-Adnan-Shakil/Cypher)** · **[Live Dashboard](https://cypher-navy.vercel.app)**

---

### 🎙️ FakeOut AI — Voice Deepfake Detection

Dual-model ML ensemble (XGBoost + Random Forest) classifying real vs. AI-generated audio using wav2vec2 embeddings, 40 MFCC coefficients, and spectral features extracted via Librosa. FastAPI inference backend, React frontend. Built at FusionX Hackathon 2026 with Sultan Salauddin Ansari.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat-square)
![Librosa](https://img.shields.io/badge/Librosa-8B0000?style=flat-square)

**[Repo](https://github.com/FuncLexa/FakeOut-AI)**

---

## ◈ In Active Development

### 🪲 commute-memory-agent — Agentic Memory Layer for Bengaluru Commute Agent
CockroachDB × AWS Hackathon submission (deadline Aug 19, 2026). Extends bengaluru-commute-agent with persistent agentic memory via CockroachDB Distributed Vector Indexing + MCP Server — the agent remembers past commutes, preferred routes, and outcome history to improve recommendations over time.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python)
![CockroachDB](https://img.shields.io/badge/CockroachDB-6933FF?style=flat-square)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)

---

## ◈ Tech Stack

![Skills](https://skillicons.dev/icons?i=java,spring,python,javascript,react,nodejs,express,postgresql,mongodb,aws,tailwind,git,github&theme=dark)

---

## ◈ GitHub Stats

![Stats](https://github-readme-stats.vercel.app/api?username=Mohammad-Adnan-Shakil&show_icons=true&theme=dark&hide_border=true&title_color=DC143C&icon_color=DC143C&border_color=8B0000)
![Streak](https://github-readme-streak-stats.herokuapp.com/?user=Mohammad-Adnan-Shakil&theme=dark&hide_border=true&ring=DC143C&fire=DC143C&currStreakLabel=DC143C)

---

## ◈ Contribution Graph

![snake animation](https://raw.githubusercontent.com/Mohammad-Adnan-Shakil/Mohammad-Adnan-Shakil/output/github-contribution-grid-snake.svg)

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=000000,8B0000,DC143C&height=120&section=footer"/>
</div>
