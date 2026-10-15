Backend · AI Systems · ML Engineering

# Mohammad Adnan Shakil

3rd year CSE, Presidency University Bengaluru. I build backend-first AI systems where every architectural decision is deliberate, not default. Seven production systems shipped independently.

[Portfolio](https://portfolio-p2jh.vercel.app) [GitHub](https://github.com/Mohammad-Adnan-Shakil) [LinkedIn](https://linkedin.com/in/mohammadadnanshakil) muhammedadnanshakil456@gmail.com

University

Presidency University, CSE

Batch

2024 – 2028

CGPA

7.99 / 10

Available

Part-time · Remote

Active Build

Live SIH 2026 · SIH26038

DRISHTI — Explainable AI for Diabetic Retinopathy

Complete DR screening system for rural India. Health worker uploads fundus image → MATLAB quality check → EfficientNet-B4 classifies severity → Grad-CAM heatmap localises lesions → Groq generates referral. Doctor reviews in under 30 seconds. Offline-first PWA. 480 patients/PHC/day modelled in Simulink.

Stack EfficientNet-B4 · Grad-CAM · MATLAB · FastAPI · NeonDB · React PWA · Groq

Target Sensitivity >90% · Specificity >85% (Grade 2+)

Dataset APTOS 2019 · IDRiD · DRIVE · Messidor-2

Live [drishti-ai-ruddy.vercel.app](https://drishti-ai-ruddy.vercel.app)

Projects

[DeltaBox Full-stack F1 analytics platform. XGBoost + Random Forest ensemble, What-If simulation, race engineer chat. Spring Boot ↔ Python via ProcessBuilder — no external ML service, no network hop. 79.6% Top-3 accuracy · 13.4ms inference · R² 0.62 Spring BootXGBoostReactPostgreSQL](https://deltabox-2.onrender.com) [Cypher Autonomous 5-agent job intelligence system. Finds opportunities, researches founders, drafts outreach, tracks replies. Runs on GitHub Actions cron — zero server infrastructure. Learns approve/skip patterns. \~15× reduction in API calls via batched scoring LangGraphFastAPIGmail APIGitHub Actions](https://github.com/Mohammad-Adnan-Shakil/Cypher) [Pitwall Agentic RAG for F1 race intelligence. Agent evaluates retrieval sufficiency before answering — not a fixed pipeline. RAGAS-evaluated: faithfulness, answer relevance, context precision, hallucination rate. pgvector · RAGAS evaluation · LangGraph LangGraphpgvectorGroqRAGAS](https://pit-wall-lemon.vercel.app) [AutoHire.AI Resume → scored, tiered, emailed in 44.3 seconds. 100-point rubric enforced in code, not prompt. 14-node n8n workflow. Every decision logged with written reasoning. 44.3s per resume · 14-node n8n · HackSprint MAHE n8nLlamaParseGroqFastAPI](https://github.com/Mohammad-Adnan-Shakil/AutohireAI) [Bengaluru Commute Agent Multi-agent commute planner with strict separation of concerns. Route agent handles data only. Advisor agent handles decisions only. Real road geometry, live congestion reasoning. Ranked 144th · Google AI Agent Builder Series 2026 Google ADKGemini 2.5FastAPIReact-Leaflet](https://github.com/Mohammad-Adnan-Shakil/bengaluru-commute-agent) [Jurix Domain-specific LLM fine-tuned on 20M+ Indian court judgements via QLoRA. Agentic RAG layer on top. RAGAS evaluation comparing fine-tuned vs base model on Indian legal Q&A. Mistral 7B / Llama 3.1 8B · 4-bit QLoRA QLoRAPEFTpgvectorRAGAS](https://github.com/Mohammad-Adnan-Shakil) [FakeOut AI Dual-model ensemble classifying real vs AI-generated audio. wav2vec2 embeddings + MFCC/spectral features. Disagreement between models flagged as low-confidence — not forced binary. 3,000+ samples · FusionX top score, first eval round wav2vec2XGBoostLibrosaFastAPI](https://github.com/FuncLexa/FakeOut-AI)

Stack

| Languages | JavaPythonJavaScriptC |
| --- | --- |
| Backend | Spring BootFastAPINode.jsAWS Lambda |
| ML / AI | XGBoostRandom ForestEfficientNet-B4Grad-CAMwav2vec2QLoRAPEFT |
| Agents | LangGraphGoogle ADKn8nRAGAS |
| Data | PostgreSQLpgvectorNeonDBCockroachDBDynamoDBMongoDB |
| Cloud | AWS LambdaAPI GatewayEventBridgeVercelRender |
| Frontend | ReactReact 19TailwindPWA |
| Other | MATLABSimulinkGitHub ActionsDocker |

Experience

Jun – Aug 2026\
Remote

Software Engineering Intern — Backend & AI Systems

Dyslexia Reading Tutor AI

- Evaluated 3 voice-AI architectures against latency, cost, production-readiness; selected and shipped ElevenLabs
- Designed full serverless pipeline: HubSpot → API Gateway → AWS Lambda → ElevenLabs → DynamoDB → EventBridge → HubSpot CRM sync
- Identified that HubSpot workflows cannot directly drive a telephony vendor; architected the required middleware orchestration layer
- Built 3 production Node.js Lambda functions — call triggering, conversation-outcome polling, bi-directional CRM sync. Verified in production before leaving.

Recognition

DRISHTI selected — Smart India Hackathon 2026 · SIH26038 · MathWorks

Awaiting Grand Finale

Production AWS voice-AI pipeline shipped end-to-end within 3 weeks of joining

Dyslexia Reading Tutor AI

Google AI Agent Builder Series 2026

Ranked 144th · HiDevs × Google

FakeOut AI — top score in first technical evaluation round

FusionX Hackathon 2026

PR #3507 merged — mem0 → Cognee migration

topoteretes/cognee · 23k ⭐

CentSight AI — financial decision simulator

Build with TRAE · 5th place

Mohammad Adnan Shakil Presidency University · B.Tech CSE 2024 – 2028 · Bengaluru, India
