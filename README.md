<div align="center">

```
MOHAMMAD ADNAN SHAKIL
Backend · AI Systems · ML Engineering
Bengaluru, India · 2024–2028
```

[![Portfolio](https://img.shields.io/badge/PORTFOLIO-000000?style=flat-square&logoColor=white)](https://portfolio-p2jh.vercel.app)&nbsp;
[![GitHub](https://img.shields.io/badge/GITHUB-000000?style=flat-square&logo=github&logoColor=white)](https://github.com/Mohammad-Adnan-Shakil)&nbsp;
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-000000?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/mohammadadnanshakil)&nbsp;
[![Mail](https://img.shields.io/badge/EMAIL-000000?style=flat-square&logo=gmail&logoColor=white)](mailto:muhammedadnanshakil456@gmail.com)

![CGPA](https://img.shields.io/badge/CGPA-7.99%2F10-222222?style=flat-square)&nbsp;
![Status](https://img.shields.io/badge/OPEN_TO-Part--time_%7C_Remote-222222?style=flat-square)&nbsp;
![DSA](https://img.shields.io/badge/NeetCode_150-56_done-222222?style=flat-square)

</div>

<br>

3rd year CSE, Presidency University Bengaluru. I build backend-first AI systems where every architectural decision is deliberate, not default. Seven production systems shipped independently.

---

## ▸ Active Build

**DRISHTI — Explainable AI for Diabetic Retinopathy Screening** `SIH26038 · MathWorks`

Health worker uploads fundus image → MATLAB quality check → EfficientNet-B4 classifies DR severity → Grad-CAM heatmap localises lesions → Groq generates referral. Doctor reviews in under 30 seconds. Offline-first PWA. 480 patients/PHC/day modelled in Simulink.

| | |
|---|---|
| **Stack** | EfficientNet-B4 · Grad-CAM · MATLAB · FastAPI · NeonDB · React PWA · Groq |
| **Target** | Sensitivity >90% · Specificity >85% for referable DR (Grade 2+) |
| **Dataset** | APTOS 2019 · IDRiD · DRIVE · Messidor-2 |
| **Live** | [drishti-ai-ruddy.vercel.app](https://drishti-ai-ruddy.vercel.app) |

---

## ▸ Projects

**[DeltaBox](https://deltabox-2.onrender.com)** — AI-Powered F1 Intelligence Platform

Full-stack F1 analytics platform. XGBoost + RF ensemble, What-If simulation, Groq-powered race engineer chat. Spring Boot ↔ Python via `ProcessBuilder` — no external ML service, no network hop.

`79.6% Top-3 accuracy` · `13.4ms inference` · `R² 0.62` · `Spring Boot · XGBoost · React · PostgreSQL`

---

**[Cypher](https://cypher-navy.vercel.app)** — Autonomous 5-Agent Job Intelligence System

Finds opportunities, researches founders, drafts outreach, tracks replies, learns from feedback. Runs on GitHub Actions cron at 7am IST — zero server infrastructure. ~15× reduction in Groq API calls via batched scoring.

`LangGraph · FastAPI · PostgreSQL · Gmail API · GitHub Actions`

---

**[Pitwall](https://pit-wall-lemon.vercel.app)** — Agentic RAG for F1 Race Intelligence

Agent evaluates retrieval sufficiency before answering — not a fixed pipeline. RAGAS-evaluated: faithfulness, answer relevance, context precision, hallucination rate.

`LangGraph · pgvector · Groq · RAGAS · FastAPI`

---

**[AutoHire.AI](https://github.com/Mohammad-Adnan-Shakil/AutohireAI)** — Autonomous Recruitment Screening

Resume → scored, tiered, emailed in 44.3s. 100-point rubric enforced in code, not prompt. 14-node n8n workflow. Every decision logged with written reasoning.

`n8n · LlamaParse · Groq · FastAPI · React 19 · Airtable · Gmail` · HackSprint MAHE

---

**[Jurix](https://github.com/Mohammad-Adnan-Shakil)** — Fine-Tuned LLM for Indian Legal Intelligence

QLoRA fine-tuning on 20M+ Indian court judgements. Agentic RAG layer. RAGAS evaluation comparing fine-tuned vs base model on Indian legal Q&A.

`Mistral 7B · Llama 3.1 8B · QLoRA · PEFT · pgvector · RAGAS`

---

**[bengaluru-commute-agent](https://github.com/Mohammad-Adnan-Shakil/bengaluru-commute-agent)** — Multi-Agent Commute Planner

Strict separation of concerns: route\_agent handles data only, advisor\_agent handles decisions only. Real road geometry, live congestion reasoning.

`Google ADK · Gemini 2.5 Flash-Lite · FastAPI · React-Leaflet` · Ranked 144th, Google AI Agent Builder Series 2026

---

**[FakeOut AI](https://github.com/FuncLexa/FakeOut-AI)** — Voice Deepfake Detection

Dual-model ensemble on wav2vec2 embeddings + MFCC/spectral features. Disagreement flagged as low-confidence — not forced binary. 3,000+ labeled samples.

`XGBoost · Random Forest · wav2vec2 · Librosa · FastAPI` · FusionX Hackathon — top score, first eval round

---

## ▸ Stack

```
Languages     Java · Python · JavaScript · C
Backend       Spring Boot · FastAPI · Node.js · AWS Lambda · API Gateway
ML / AI       XGBoost · Random Forest · EfficientNet-B4 · Grad-CAM
              wav2vec2 · QLoRA · PEFT · SFTTrainer · HuggingFace
Agents        LangGraph · Google ADK · n8n · RAGAS
Data          PostgreSQL · pgvector · NeonDB · CockroachDB · DynamoDB · MongoDB
Cloud         AWS Lambda · EventBridge · Vercel · Render · GitHub Actions
Frontend      React · React 19 · Tailwind · PWA
Other         MATLAB · Simulink · Docker · JWT · RBAC
```

---

## ▸ Experience

**Software Engineering Intern — Backend & AI Systems**
Dyslexia Reading Tutor AI · Remote · Jun – Aug 2026

- Evaluated 3 voice-AI architectures against latency, cost, and production-readiness; selected and shipped ElevenLabs
- Designed full serverless pipeline: HubSpot → API Gateway → AWS Lambda → ElevenLabs → DynamoDB → EventBridge → HubSpot CRM sync
- Identified that HubSpot workflows cannot directly drive a telephony vendor; architected the required middleware orchestration layer
- Built 3 production Node.js Lambda functions — call triggering, conversation-outcome polling, bi-directional CRM sync. Verified in production before leaving.

---

## ▸ Recognition

| | |
|---|---|
| Smart India Hackathon 2026 | DRISHTI selected · SIH26038 · MathWorks · Awaiting Grand Finale |
| Production internship | AWS voice-AI pipeline shipped end-to-end within 3 weeks of joining |
| Google AI Agent Builder Series 2026 | Ranked 144th · HiDevs × Google for Developers |
| FusionX Hackathon 2026 | Top score in first technical evaluation round — FakeOut AI |
| Open Source | PR #3507 merged — mem0→Cognee migration · topoteretes/cognee (23k ⭐) |
| Build with TRAE Hackathon | 5th place — CentSight AI financial decision simulator |

---

<div align="center">

*Architecture is the art of making deliberate decisions — and being able to defend every single one.*

</div>
