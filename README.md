<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=8B0000,DC143C,1a0000&height=220&section=header&text=Mohammad%20Adnan%20Shakil&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=Backend%20Engineer%20%E2%80%A2%20AI%20Systems%20%E2%80%A2%20ML%20Engineer&descAlignY=60&descSize=17&animation=fadeIn"/>

<br/>

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=16&duration=3000&pause=900&color=DC143C&center=true&vCenter=true&width=850&lines=Building+systems+that+decide%2C+not+just+display;Spring+Boot+%7C+React+%7C+PostgreSQL+%7C+Python+ML;Multi-agent+AI+%7C+LangGraph+%7C+Google+ADK+%7C+LLM+Fine-tuning;Agentic+RAG+%7C+QLoRA+%7C+AWS+Serverless+%7C+FastAPI"/>

<br/>

![Location](https://img.shields.io/badge/📍_Bengaluru-India-DC143C?style=flat-square)
![University](https://img.shields.io/badge/Presidency_University-B.Tech_CSE_2028-8B0000?style=flat-square)
![CGPA](https://img.shields.io/badge/CGPA-8.15%2F10-DC143C?style=flat-square)
![Status](https://img.shields.io/badge/Open_To-Part--Time_Roles-success?style=flat-square)

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-111111?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio-p2jh.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mohammadadnanshakil)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:muhammedadnanshakil456@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Mohammad-Adnan-Shakil)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=Mohammad-Adnan-Shakil&color=DC143C&style=flat-square&label=Profile+Views)
![GitHub followers](https://img.shields.io/github/followers/Mohammad-Adnan-Shakil?style=flat-square&color=DC143C&label=Followers)
![GitHub stars](https://img.shields.io/github/stars/Mohammad-Adnan-Shakil?style=flat-square&color=DC143C&label=Total+Stars)

</div>

---

## ◈ About Me

<img align="right" width="300" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Mohammad-Adnan-Shakil&layout=compact&theme=dark&hide_border=true&title_color=DC143C&icon_color=DC143C"/>

Second-year Computer Science Engineering student at Presidency University, Bengaluru — building backend-first AI systems where every architectural decision is deliberate, not default.

I architect and ship full production systems across the entire stack: Spring Boot backends with Python ML pipelines via subprocess orchestration, multi-agent LangGraph systems with persistent memory, serverless AWS pipelines, and fine-tuned domain-specific LLMs. I work fast, debug deep, and care about clean architecture over tutorial-level work.

**Previously:** Software Engineering Intern at Dyslexia Reading Tutor AI — designed and shipped a production serverless voice-AI pipeline on AWS (Lambda → ElevenLabs → DynamoDB → EventBridge → HubSpot), end-to-end verified in production within 3 weeks of joining.

**Currently:** Building commute-memory-agent (CockroachDB × AWS Hackathon, August 2026) and Jurix (fine-tuned LLM on Indian legal corpus via QLoRA).

**Open To:** Part-time Backend Engineering · ML Engineering · Agentic AI roles at AI-first startups

---

## ◈ Tech Stack

<div align="center">

**Languages**

![Skills](https://skillicons.dev/icons?i=java,python,javascript,c&theme=dark)

**Frontend**

![Skills](https://skillicons.dev/icons?i=react,tailwind,html,css&theme=dark)

**Backend & Databases**

![Skills](https://skillicons.dev/icons?i=spring,nodejs,express,fastapi,postgresql,mongodb&theme=dark)

**Cloud, DevOps & Tooling**

![Skills](https://skillicons.dev/icons?i=aws,git,github,docker,vscode,idea&theme=dark)

</div>

---

## ◈ AI / ML Expertise

<div align="center">

| Domain | Proficiency | Details |
|---|---|---|
| Multi-Agent Systems | ████████░░ Advanced | Google ADK, LangGraph, orchestrator patterns, strict separation of concerns |
| LLM Fine-Tuning | ███████░░░ Intermediate | QLoRA, LoRA, PEFT, SFTTrainer, HuggingFace ecosystem |
| Agentic RAG | ███████░░░ Intermediate | pgvector, retrieval chains, RAGAS evaluation, faithfulness metrics |
| Classical ML | ████████░░ Advanced | XGBoost, Random Forest, ensemble methods, validation pipelines |
| Serverless AI Pipelines | █████████░ Advanced | AWS Lambda, API Gateway, DynamoDB, EventBridge, voice-AI orchestration |
| LLM Integration | ████████░░ Advanced | Groq, Gemini, ElevenLabs, OpenRouteService, tool-calling agents |
| Audio ML | ██████░░░░ Intermediate | wav2vec2, MFCC, Librosa, deepfake detection ensembles |

</div>

---

## ◈ Featured Projects

<details>
<summary><b>🔴 DeltaBox — AI-Powered Formula 1 Intelligence Platform</b></summary>

<br/>

Full-stack F1 analytics platform independently architected across backend, frontend, ML pipeline, and database — with a blended ML engine, What-If simulation, and Groq-powered conversational AI assistant.

| Attribute | Details |
|---|---|
| Stack | Spring Boot · React · PostgreSQL · Python · XGBoost · Random Forest · JWT · Render |
| ML Performance | 79.6% Top-3 finishing-position accuracy · R² 0.62 on held-out test set |
| Inference Speed | 13.4ms blended · XGBoost: 2.5ms · Random Forest: 10.9ms |
| Security | Custom JWT + RBAC built from scratch — no Spring Security defaults |
| Architecture | Java ↔ Python via ProcessBuilder (JSON over STDIN/STDOUT) — no external ML service |
| Deployment | Render (full-stack) · Live at deltabox-2.onrender.com |
| Repository | [github.com/Mohammad-Adnan-Shakil/deltabox](https://github.com/Mohammad-Adnan-Shakil/deltabox) |

**Key architectural decision:** Instead of deploying Python ML models as a separate HTTP microservice, I integrated them directly into the Spring Boot backend via `ProcessBuilder` — eliminating network latency, reducing deployment complexity, and keeping inference under 15ms. Every tradeoff was deliberate.

</details>

---

<details>
<summary><b>🏎️ Pitwall — Agentic RAG System for F1 Race Intelligence</b></summary>

<br/>

Agentic RAG system built as a standalone intelligence layer — retrieves real F1 race data from a pgvector store, evaluates retrieval sufficiency before answering, and measures output quality with RAGAS metrics.

| Attribute | Details |
|---|---|
| Stack | Python · LangGraph · FastAPI · pgvector · PostgreSQL · Groq · RAGAS · React |
| Architecture | Agent decides whether to retrieve or answer from context — not a fixed pipeline |
| Retrieval | pgvector similarity search over historical F1 race data, telemetry, and strategy documents |
| Evaluation | RAGAS: faithfulness · answer relevance · context precision · hallucination rate |
| Integration | FastAPI service callable from DeltaBox's Spring Boot backend |
| Deployment | Live at pit-wall-lemon.vercel.app |
| Repository | [github.com/Mohammad-Adnan-Shakil/PitWall](https://github.com/Mohammad-Adnan-Shakil/PitWall) |

**Key architectural decision:** The agent evaluates retrieval sufficiency before generating — if retrieved chunks don't adequately cover the question, it reformulates the query and retrieves again rather than hallucinating. This is what separates production RAG from tutorial RAG.

</details>

---

<details>
<summary><b>🕵️ Cypher — Autonomous Multi-Agent Job Intelligence System</b></summary>

<br/>

Fully autonomous 5-agent job intelligence system that finds opportunities, researches founders, drafts personalized outreach, tracks replies, and learns from feedback — zero manual intervention required.

| Attribute | Details |
|---|---|
| Stack | Python · LangGraph · FastAPI · PostgreSQL · React · Groq · Gmail API · GitHub Actions |
| Agents | Opportunity Scout · Founder Researcher · Outreach Drafter · Tech Pulse · Reply Tracker |
| Scheduling | GitHub Actions cron — runs daily at 7am IST, no server infrastructure |
| Performance | Batched LLM scoring reduced Groq API calls ~15x after production rate limit hit |
| Memory | cypher_memory feedback loop — learns approve/skip patterns, adjusts scoring over time |
| Integration | Gmail OAuth2 (read + send) for reply detection and automated outreach delivery |
| Dashboard | React (5 pages: Stats, Kanban, Outreach Tracker, Memory, Hackathons) on Vercel |
| Repository | [github.com/Mohammad-Adnan-Shakil/Cypher](https://github.com/Mohammad-Adnan-Shakil/Cypher) |

**Key architectural decision:** Diagnosed per-item LLM scoring as the rate limit root cause and rearchitected to batch all opportunities per run — cutting API calls from O(n) to O(1) per agent cycle. A production debugging decision, not a tutorial pattern.

</details>

---

<details>
<summary><b>🤖 bengaluru-commute-agent — Multi-Agent Commute Planning AI</b></summary>

<br/>

Multi-agent commute planning system for Bengaluru with strict separation of concerns — real road geometry, live congestion reasoning, and temporal decision-making ("leave at 7:30am vs 9:15am").

| Attribute | Details |
|---|---|
| Stack | Python · Google ADK · Gemini 2.5 Flash-Lite · FastAPI · React · OpenRouteService · React-Leaflet |
| Architecture | Orchestrator → route_agent (data only) → advisor_agent (decisions only) |
| Recognition | Ranked 144th · Google AI Agent Builder Series 2026 (HiDevs × Google for Developers) |
| Integrity | Honest fallback — agent explicitly states when it lacks corridor data, no hallucination |
| Deployment | Backend: Render · Frontend: Vercel |
| Repository | [github.com/Mohammad-Adnan-Shakil/bengaluru-commute-agent](https://github.com/Mohammad-Adnan-Shakil/bengaluru-commute-agent) |

**Key architectural decision:** Strict agent role separation — route_agent is instructed to never give opinions, advisor_agent never fetches data. This prevents model drift, makes debugging deterministic, and mirrors production multi-agent design patterns.

</details>

---

<details>
<summary><b>🎙️ FakeOut AI — Voice Deepfake Detection System</b></summary>

<br/>

Dual-model ML ensemble classifying real vs. AI-generated audio using wav2vec2 embeddings and MFCC/spectral features, with a FastAPI inference backend and React frontend.

| Attribute | Details |
|---|---|
| Stack | Python · XGBoost · Random Forest · wav2vec2 · Librosa · FastAPI · React |
| Features | 40 MFCC coefficients · spectral centroid · rolloff · zero crossing rate · wav2vec2 embeddings |
| Ensemble | Majority-vote — disagreement flagged as low-confidence, not forced to a decision |
| Training | 3,000+ labeled audio samples · 80/20 split · StandardScaler normalization |
| Event | FusionX Hackathon 2026 — top score in first technical evaluation round |
| Repository | [github.com/FuncLexa/FakeOut-AI](https://github.com/FuncLexa/FakeOut-AI) |

</details>

---

## ◈ In Production / Active Development

<details>
<summary><b>🪲 commute-memory-agent — Agentic Memory Layer (CockroachDB × AWS Hackathon)</b></summary>

<br/>

Extends bengaluru-commute-agent with persistent agentic memory via CockroachDB — the agent remembers past commutes, preferred routes, and outcome history, improving recommendations over time.

| Attribute | Details |
|---|---|
| Stack | Python · CockroachDB · AWS · LangGraph · Distributed Vector Indexing · MCP Server |
| Hackathon | CockroachDB × AWS — "Build with Agentic Memory" · Deadline: August 19, 2026 |
| Memory Types | Conversation history (transactional) · Route preference embeddings (vector) · Outcome tracking |
| Mandatory Tools | CockroachDB MCP Server + Distributed Vector Indexing |
| Status | 🔴 Active build |

</details>

---

<details>
<summary><b>⚖️ Jurix — Fine-Tuned LLM for Indian Legal Intelligence</b></summary>

<br/>

Domain-specific LLM fine-tuned on Indian court judgements via QLoRA — with an agentic RAG layer and RAGAS evaluation comparing fine-tuned vs. base model performance on Indian legal Q&A.

| Attribute | Details |
|---|---|
| Stack | Python · Mistral 7B / Llama 3.1 8B · QLoRA · PEFT · HuggingFace · pgvector · FastAPI · React |
| Data Source | Indian Kanoon — 20M+ court judgements, acts, and legal precedents |
| Method | QLoRA (4-bit quantization + LoRA adapters) — fine-tuning on consumer GPU |
| Evaluation | RAGAS: faithfulness · answer relevance · context precision · hallucination rate |
| Goal | Published comparison: Jurix vs. Mistral base vs. GPT-4o on Indian legal benchmark |
| Status | 🟡 Theory phase — implementation starting post-CockroachDB hackathon |

</details>

---

## ◈ Experience

**Software Engineering Intern — Backend & AI Systems**
Dyslexia Reading Tutor AI · Remote · June 2026 – August 2026

Designed and shipped a production serverless voice-AI pipeline automating outbound parent follow-up calls for a dyslexia/reading-intervention platform — end-to-end verified across all pipeline stages.

- Evaluated 3 voice-AI architectures (ElevenLabs Conversational AI, Deepgram STT+LLM+TTS, custom orchestration) against latency, cost, and production-readiness; selected and shipped ElevenLabs
- Designed the full pipeline: HubSpot webhook → API Gateway → AWS Lambda → ElevenLabs → DynamoDB → EventBridge polling → HubSpot CRM sync
- Built 3 production Node.js Lambda functions — outbound call triggering, conversation-outcome polling, bi-directional CRM sync
- Identified that HubSpot workflows cannot directly drive a telephony vendor and architected the required middleware orchestration layer — now the system's core design pattern

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws)
![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat-square&logo=awslambda)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs)
![ElevenLabs](https://img.shields.io/badge/ElevenLabs-000000?style=flat-square)
![HubSpot](https://img.shields.io/badge/HubSpot-FF7A59?style=flat-square&logo=hubspot)

---

## ◈ Achievements

<div align="center">

| Recognition | Details |
|---|---|
| 🚀 Production Internship | Shipped end-to-end production AWS voice-AI pipeline within 3 weeks of joining |
| 🏆 Google AI Agent Builder Series 2026 | Ranked 144th · HiDevs × Google for Developers |
| 🎯 FusionX Hackathon 2026 | Top score in first technical evaluation round for FakeOut AI deepfake detection |
| 📚 Academic | 8.15 CGPA while independently architecting and deploying 5+ full-stack AI platforms |
| 🔬 Open Source | PR #3507 merged to topoteretes/cognee (23k ⭐) — mem0→Cognee migration example |
| 🏗️ Build with TRAE Hackathon | 5th place — CentSight AI financial decision simulator |

</div>

---

## ◈ GitHub Analytics

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=Mohammad-Adnan-Shakil&show_icons=true&theme=dark&hide_border=true&title_color=DC143C&icon_color=DC143C&border_color=8B0000&count_private=true"/>
<img height="180" src="https://github-readme-streak-stats.herokuapp.com/?user=Mohammad-Adnan-Shakil&theme=dark&hide_border=true&ring=DC143C&fire=DC143C&currStreakLabel=DC143C"/>

</div>

---

## ◈ GitHub Trophies

<div align="center">

![Trophies](https://github-profile-trophy.vercel.app/?username=Mohammad-Adnan-Shakil&theme=darkhub&no-frame=true&column=7&margin-w=8&title_color=DC143C)

</div>

---

## ◈ Contribution Activity

<div align="center">

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=Mohammad-Adnan-Shakil&theme=github-compact&bg_color=0a0a0f&color=DC143C&line=DC143C&point=ffffff&hide_border=true)](https://github.com/Mohammad-Adnan-Shakil)

</div>

---

## ◈ Contribution Graph

<div align="center">

![snake animation](https://raw.githubusercontent.com/Mohammad-Adnan-Shakil/Mohammad-Adnan-Shakil/output/github-contribution-grid-snake.svg)

</div>

---

## ◈ Current Focus

```yaml
learning:
  - QLoRA fine-tuning on Indian legal corpus (Jurix)
  - RAGAS evaluation frameworks for production RAG systems
  - NeetCode 150 DSA — daily practice

building:
  - commute-memory-agent (CockroachDB × AWS Hackathon — Aug 19 deadline)
  - Jurix — domain fine-tuned LLM for Indian legal Q&A

shipped:
  - Pitwall — agentic RAG system for F1 intelligence (pit-wall-lemon.vercel.app)
  - Cypher — autonomous 5-agent job intelligence system (cypher-navy.vercel.app)

exploring:
  - LangGraph advanced patterns (multi-agent memory sharing)
  - CockroachDB Distributed Vector Indexing
  - HuggingFace PEFT + trl ecosystem

open_to:
  - Part-time ML Engineering roles
  - Part-time Backend Engineering roles
  - AI-first startups with steep learning curves
  - Remote or Bengaluru-based positions
```

---

## ◈ Connect

<div align="center">

[![Gmail](https://img.shields.io/badge/muhammedadnanshakil456%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:muhammedadnanshakil456@gmail.com)
[![LinkedIn](https://img.shields.io/badge/mohammadadnanshakil-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mohammadadnanshakil)
[![GitHub](https://img.shields.io/badge/Mohammad--Adnan--Shakil-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Mohammad-Adnan-Shakil)
[![Portfolio](https://img.shields.io/badge/portfolio--p2jh.vercel.app-111111?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio-p2jh.vercel.app)

</div>

---

<div align="center">

*"Architecture is the art of making deliberate decisions — and being able to defend every single one."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=000000,8B0000,DC143C&height=120&section=footer"/>

</div>
