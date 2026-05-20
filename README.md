# Hi, I'm Pratik 👋

**Senior Software Engineer & Cloud Architect** · Pune, India

7+ years building cloud-native, distributed systems in **Go**, **Python**, and **TypeScript** on **GCP**, **AWS**, and **Azure**. I work on microservices, gRPC / GraphQL APIs, and **Multi-Agent AI systems** (Google ADK, MCP, Vertex AI Agent Engine, LangChain, CrewAI).

🔭 **What I'm working on right now**
- Multi-agent AI systems for FinTech (Google ADK · MCP · Vertex AI Agent Engine)
- RAG and GraphRAG pipelines on AlloyDB AI and BigQuery Knowledge Graph
- Voice AI assistants (ElevenLabs + Gemini)
- Ongoing open-source contributions to Google's Spanner Migration Tool

📍 **Open to** Senior / Staff Engineer and Cloud Architect roles in FinTech, Open Banking, and GenAI infrastructure — Bengaluru, Pune, Mumbai, Hyderabad, Remote, EMEA.

📧 **Reach me:** i.pratikdhanave@gmail.com · [LinkedIn](https://www.linkedin.com/in/pratikdhanave) · [GCN 2022 talk](https://drive.google.com/drive/folders/1ny-2QsHxhrtlYofbCN3WL2TbVJXDsnxz)

---

## 🚀 Featured projects

### Multi-Agent AI & GenAI

| Project | What it does | Stack |
|---|---|---|
| **Genie** | Multi-agent financial assistant bridging LLMs with real-time banking APIs for autonomous advisory and predictive cash-flow analysis. Implements Google's [multi-agent reference architecture](https://docs.cloud.google.com/architecture/multiagent-ai-system). | Python · Google ADK · MCP · Vertex AI Agent Engine · FastAPI |
| **MAI-DxO Diagnostic Agent Panel** | Replicated Microsoft's [Sequential Diagnostic Panel](https://microsoft.ai/news/the-path-to-medical-superintelligence/) pattern with 5 role-specialized agents (Hypothesis, Challenger, Stewardship, Test Chooser, Checklist) and multi-model routing across Claude, GPT-O3, Gemini. | Python · ADK · multi-model |
| **Bancnet** | Open Banking portal for UAE (ADGM/DIFC) and Saudi (SAMA) with consent management, data residency, and RAG semantic search on AlloyDB AI — 37% latency reduction. | Python · FastAPI · RAG · pgvector · AlloyDB AI |
| **Optimus** | Gemini-powered BigQuery analyzer detecting SQL anti-patterns (full scans, inefficient joins, missing partition filters); delivered 57% cost reduction. | Python · Gemini API · BigQuery |
| **Kinetic India Voice Assistant for Bike** | Conversational voice AI for two-wheeler riders — diagnostics, service booking, ride telemetry. | Python · ElevenLabs · Gemini |

### Backend & Distributed Systems

| Project | What it does | Stack |
|---|---|---|
| **Brownlow** | Zero-trust voting platform for the AFL Brownlow Medal — 100K+ votes, 10K+ concurrent users on Cloud Run during live broadcasts, secured with Cloud KMS + Security Command Center. | Go · GraphQL · gRPC · Cloud SQL · Pub/Sub |
| **Globe** | Kubernetes transaction platform handling 30K+ TPS for telecom/FinTech partner integrations — led 10 engineers, PCI-aligned, idempotent processing, error-code orchestration framework. | Go · Kubernetes · Kafka · Pub/Sub · Redis |
| **Picnic** | Social platform backend serving 1M+ users — reduced API response latency 47% via protobuf contracts and service consolidation; led a remote-first team of 4. | Go · gRPC · GraphQL · Cloud Spanner |
| **P2P Financial Lending Platform** | Lending platform processing 5K+ loans/month with double-entry ledger, 3+ credit bureaus, payment gateways, KYC/AML, fraud detection, maker-checker RBAC. | Go · PostgreSQL |

---

## 🌱 Open source

- [**GoogleCloudPlatform/spanner-migration-tool** (HarbourBridge)](https://github.com/GoogleCloudPlatform/spanner-migration-tool) — core contributor. Built backend APIs for the Intelligent Schema Assistant, CDC pipelines (Datastream · Pub/Sub · Dataflow), and improved post-migration query performance by 40–60% through PK design, indexing, and table interleaving.
- [**leopardslab/gocloud**](https://github.com/leopardslab/gocloud) — unified API library for managing cloud resources across AWS, GCP, and Azure.
- [**skycoin/cx**](https://github.com/skycoin/cx) — enhanced the CX interpreter for deterministic blockchain transaction execution; implemented Pratt parser reducing parsing complexity by ~30%.

---

## 🏆 Recognition

- 🎤 **[Speaker at Google Cloud Next 2022](https://drive.google.com/drive/folders/1ny-2QsHxhrtlYofbCN3WL2TbVJXDsnxz)** — *"Migrating Monolith Applications into Microservices"*
- 🌍 **[Google Summer of Code](https://drive.google.com/drive/folders/1hkLNLNHsQeYevR7fDD2NyymJsnndBCCx)** — Contributor (2017–2018), **[Mentor (2019–2026)](https://drive.google.com/drive/folders/1Tpyidwk7zcicIJuz2sDbqYhCVyDjTOSv)**; guided 10+ students on cloud-native and AI-native projects
- 💼 **Productized Tata Group BigQuery cost-optimization engagement** into Searce's GCP managed service offering — INR ₹100 Cr+ (~$12M) saved, 57% DW cost reduction
- 🎓 **Google Cloud Generative AI Leader** Professional Certificate
- 🎓 **Google Cloud Specialization** — Data Engineering, Big Data, and Machine Learning on GCP
- 🎓 **Ardan Labs** — Ultimate Go and Ultimate Services Go

---

## 🛠️ Tech stack

**Languages** — Go · Python · TypeScript · SQL

**Cloud** — GCP · AWS · Azure

**GenAI / ML** — Google ADK · Model Context Protocol (MCP) · A2A · Vertex AI Agent Engine · LangChain · LangGraph · CrewAI · AutoGen · Genkit · RAG · GraphRAG · BigQuery Knowledge Graph · pgvector · AlloyDB AI · Pinecone · Voice AI (ElevenLabs) · LLM-as-Judge · LangSmith · OpenAI · Anthropic Claude · Google Gemini · AWS Bedrock · Hugging Face · Ollama · MLOps · LLMOps

**Backend** — gRPC · GraphQL · REST · FastAPI · Gin · Django · Cloud Spanner · BigQuery · PostgreSQL · MongoDB · Redis · Kafka · Apache Airflow · Pub/Sub

**Infra & DevOps** — Kubernetes · GKE · EKS · Helm · Docker · Terraform · GitHub Actions · Jenkins · Cloud Run · AWS Lambda · Prometheus · Grafana · OpenTelemetry

**Security & Compliance** — Cloud IAM · KMS · HSM · Cloud Armor · VPC Service Controls · IAP · DLP · Binary Authorization · Security Command Center · JWT · OAuth 2.0 · OpenID Connect · Zero-Trust · SOC 2 · ISO 27001 · PCI-DSS · KYC/AML

**Domain expertise** — FinTech · Open Banking (UAE ADGM/DIFC, Saudi SAMA) · Enterprise AI Adoption · FinOps

---

## ✍️ I write about

Multi-Agent AI · Google ADK · MCP · Agentic Commerce · BigQuery Graph · LLM determinism · Genkit middleware · the production realities of building reliable AI systems on Google Cloud.

📖 Follow posts on [LinkedIn](https://www.linkedin.com/in/pratikdhanave) (2,455+ followers).

---

## 📊 GitHub stats

<!-- These widgets render automatically when you push this README to github.com/PratikDhanave/PratikDhanave -->

![Pratik's GitHub stats](https://github-readme-stats.vercel.app/api?username=PratikDhanave&show_icons=true&theme=default&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=PratikDhanave&layout=compact&theme=default&hide_border=true&langs_count=8)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=PratikDhanave&theme=default&hide_border=true)

---

## 📫 How to reach me

- ✉️ **Email** — i.pratikdhanave@gmail.com
- 💼 **LinkedIn** — [linkedin.com/in/pratikdhanave](https://www.linkedin.com/in/pratikdhanave)
- 🐙 **GitHub** — you're already here 👀

---

> *Looking for senior engineering talent with deep backend + GenAI + multi-region compliance experience? Let's talk.*

<sub>Last updated: May 2026 · Built with care, not with templates.</sub>
