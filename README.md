# Hi, I'm Pratik 👋

**Agentic AI Architect** · Pune, India

7+ years building cloud-native, distributed systems in **Go**, **Python**, and **TypeScript** on **GCP**, **AWS**, and **Azure**. I specialize in **Agentic AI systems** and **multi-agent orchestration**, healthcare AI, microservices, gRPC / GraphQL APIs, and FinOps — bridging LLMs with real-time enterprise systems (Google ADK, MCP, MARA, Vertex AI Agent Engine, LangChain, LangGraph, CrewAI).

---

## 🎯 What I'm working on right now

- **Multi-agent AI systems** for FinTech (Google ADK · MCP · MARA · Vertex AI Agent Engine)
- **Medical AI** — FHIR R4 + HL7 v2, cost-aware diagnostic budgets, clinical reasoning
- **RAG & GraphRAG pipelines** on AlloyDB AI, BigQuery Knowledge Graph, and pgvector
- **Voice AI assistants** (ElevenLabs + Gemini)
- **Open Banking** — consent management and regulatory compliance (ADGM, DIFC, SAMA)
- **Open-source contributions** — Microsoft Agent Framework Go, Genie, Bodh, and Google's Spanner Migration Tool

---

## 📍 Open to

Senior / Staff Engineer and Cloud Architect roles in **FinTech, Healthcare Tech, GenAI Infrastructure, and Open Banking** — Bengaluru, Pune, Mumbai, Hyderabad, Remote, EMEA, UAE.

---

## 📧 Reach me

- ✉️ **Email** — i.pratikdhanave@gmail.com
- 💼 **LinkedIn** — [linkedin.com/in/pratikdhanave](https://www.linkedin.com/in/pratikdhanave) (2,455+ followers)
- 🌐 **Portfolio** — [pratikdhanave.github.io](https://pratikdhanave.github.io)
- 🎤 **GCN 2022 Talk** — [Migrating Monolith Applications into Microservices](https://drive.google.com/drive/folders/1ny-2QsHxhrtlYofbCN3WL2TbVJXDsnxz)

---

## 📚 Publications & technical articles

- **Multi-Agent Systems Architecture** — hierarchical coordination patterns, function calling, cost-aware decision trees, observability & cost tracking
  [Website](https://pratikdhanave.github.io/articles/multi-agent-systems) · [GitHub](https://github.com/PratikDhanave/genesisofmedium/blob/main/articles/27-multi-agent-systems.md)
- **BigQuery FinOps: 57% Cost Reduction at Scale** — query refactoring, materialized views, MERGE optimization, slot-based capacity planning
  [Website](https://pratikdhanave.github.io/articles/bigquery-finops) · [GitHub](https://github.com/PratikDhanave/genesisofmedium/blob/main/articles/28-bigquery-finops.md)
- **FHIR R4 + HL7 v2 Medical AI Interoperability** — Bodh architecture, cost-aware diagnostic budgets, HIPAA compliance patterns
  [Website](https://pratikdhanave.github.io/articles/fhir-hl7-medical-ai) · [GitHub](https://github.com/PratikDhanave/genesisofmedium/blob/main/articles/29-fhir-hl7-medical-ai.md)

---

## 🏆 Recognition

- 🎤 **[Speaker at Google Cloud Next 2022](https://drive.google.com/drive/folders/1ny-2QsHxhrtlYofbCN3WL2TbVJXDsnxz)** — *"Migrating Monolith Applications into Microservices"*
- 🌍 **[Google Summer of Code](https://drive.google.com/drive/folders/1hkLNLNHsQeYevR7fDD2NyymJsnndBCCx)** — Contributor (2017–2018), **[Mentor (2019–2026)](https://drive.google.com/drive/folders/1Tpyidwk7zcicIJuz2sDbqYhCVyDjTOSv)**; guided 10+ students on cloud-native and AI-native projects
- 💼 **Productized Tata Group BigQuery cost-optimization engagement** into Searce's GCP managed service offering — INR ₹100 Cr+ (~$12M) saved, **57% DW cost reduction**
- 🎓 **Google Cloud Generative AI Leader** Professional Certificate
- 🎓 **Google Cloud Specialization** — Data Engineering, Big Data, and Machine Learning on GCP
- 🎓 **Ardan Labs** — Ultimate Go and Ultimate Services Go

---

## 🌱 Open source

- [**Microsoft Agent Framework Go**](https://github.com/microsoft/agent-framework-go) — contributor to Microsoft's official Go implementation of the Agent Framework. Merged runtime correctness fixes: a nil-update panic in the tool-approval middleware ([#472](https://github.com/microsoft/agent-framework-go/pull/472)) and a dead `reflect.Type` guard in the workflow route builder that silently accepted invalid `PortableValue` handlers ([#489](https://github.com/microsoft/agent-framework-go/pull/489)) — each shipped with a regression test.
- [**GoogleCloudPlatform/spanner-migration-tool** (HarbourBridge)](https://github.com/GoogleCloudPlatform/spanner-migration-tool) — core contributor. Built backend APIs for the Intelligent Schema Assistant, CDC pipelines (Datastream · Pub/Sub · Dataflow), and improved post-migration query performance by 40–60% through PK design, indexing, and table interleaving.
- [**leopardslab/gocloud**](https://github.com/leopardslab/gocloud) — unified API library for managing cloud resources across AWS, GCP, and Azure.
- [**skycoin/cx**](https://github.com/skycoin/cx) — enhanced the CX interpreter for deterministic blockchain transaction execution; implemented a Pratt parser reducing parsing complexity by ~30%.

---

## 🚀 Featured projects

### Multi-Agent AI & GenAI

| Project | What it does | Stack |
|---|---|---|
| **Genie** | Multi-agent financial assistant bridging LLMs with real-time banking APIs for autonomous advisory, predictive cash-flow analysis, and transaction orchestration. 15 role-specialized agents on Google's [multi-agent reference architecture (MARA)](https://docs.cloud.google.com/architecture/multiagent-ai-system). | Go · MARA · MCP · Vertex AI Agent Engine · PostgreSQL · OpenTelemetry |
| **Bodh** | Medical AI inspired by Microsoft's [MAI-DxO Sequential Diagnostic Panel](https://microsoft.ai/news/the-path-to-medical-superintelligence/). Virtual physician panel of 7 role-specialized agents (intake, supervisor, questioner, test planner, cost guardian, diagnostician, reasoning verifier); FHIR R4 + HL7 v2 aware with cost-aware diagnostic budget enforcement. | Go · MARA · FHIR R4 · HL7 v2 · SD-Bench |
| **Bancnet** | Open Banking portal for UAE (ADGM/DIFC) and Saudi (SAMA) with consent management, data residency, and RAG semantic search on AlloyDB AI — 37% latency reduction. | Python · Go · FastAPI · RAG · pgvector · AlloyDB AI |
| **Optimus** | Gemini-powered BigQuery analyzer detecting SQL anti-patterns (full scans, inefficient joins, missing partition filters) and recommending optimizations — delivered 57% cost reduction. | Python · Go · Gemini API · BigQuery |
| **Kinetic India Voice Assistant** | Conversational voice AI for two-wheeler riders — diagnostics, service booking, and ride telemetry, with ElevenLabs voice synthesis and Gemini-backed dialog management. | Python · Go · ElevenLabs · Gemini |

### Backend & Distributed Systems

| Project | What it does | Stack |
|---|---|---|
| **Brownlow** | Zero-trust voting platform for the AFL Brownlow Medal — 100K+ votes, 10K+ concurrent users on Cloud Run during live broadcasts; validation, encryption (Cloud KMS), audit logging, and abuse prevention secured with Security Command Center. | Go · GraphQL · gRPC · Cloud Run · Cloud KMS · Pub/Sub |
| **Globe** | Kubernetes transaction platform handling **30K+ TPS** for telecom/FinTech partner integrations — led 10 engineers; idempotent processing, ledger/reconciliation, dual-layer auth (JWT + API keys), and PCI-aligned data protection. | Go · Kubernetes · Kafka · Pub/Sub · Redis |
| **Picnic** | Social network backend serving **1M+ users** — designed Go/gRPC microservices behind a GraphQL API gateway, reducing API response latency by **47%** via protobuf contracts and service consolidation; led a remote-first team of 4. | Go · gRPC · GraphQL · Cloud Spanner |
| **HarbourBridge** | CDC pipelines for minimal-downtime migrations to Cloud Spanner — backend APIs for the Intelligent Schema Assistant with 40–60% post-migration query gains. | Go · Python · Cloud Spanner · Datastream |
| **Litmus** | Industrial IoT edge data platform — real-time ingestion from manufacturing/energy plants (MQTT, OPC-UA), Python streaming pipelines to cloud analytics, and AI-driven anomaly detection. | Python · Go · MQTT · OPC-UA · Kubernetes |
| **P2P Financial Lending Platform** | Lending platform processing 5K+ loans/month with a double-entry ledger, 3+ credit bureaus, payment gateways, KYC/AML, fraud detection, and maker-checker RBAC. | Go · PostgreSQL |

---

## 💼 Technical skills

**Languages** — Go · Python · TypeScript · SQL

**Multi-Agent AI** — Google ADK · MARA · MCP · A2A · LangGraph · LangChain · CrewAI · AutoGen · Genkit · Function Calling · ReAct · LLM-as-Judge · Agent Workflows · Cost-aware Constraints

**Healthcare AI** — FHIR R4 · HL7 v2 · MAI-DxO · SD-Bench · Cost-aware Diagnostic Budgets · Clinical Reasoning

**GenAI / ML** — Vertex AI Agent Engine · RAG · GraphRAG · BigQuery Knowledge Graph · Voice AI (ElevenLabs) · LangSmith · OpenAI · Anthropic Claude · Google Gemini · AWS Bedrock · Hugging Face · Ollama · MLOps · LLMOps

**Cloud platforms** — GCP (Vertex AI Agent Engine, BigQuery, Cloud Spanner, Cloud Run, Dataflow, Datastream) · AWS (EC2, EKS, Lambda, Bedrock) · Azure (App Service, Cosmos DB, AI Search)

**Databases & vector search** — PostgreSQL · pgvector · Cloud Spanner · BigQuery · AlloyDB AI · Pinecone · MongoDB · Redis

**APIs & protocols** — REST · gRPC · GraphQL · FastAPI · Gin · Django · OpenTelemetry · Pub/Sub · Kafka · Apache Airflow

**Infrastructure & DevOps** — Kubernetes · GKE · EKS · Helm · Docker · Terraform · GitHub Actions · Jenkins · Cloud Run · AWS Lambda

**Voice AI** — ElevenLabs · Dialog Management · Multi-language Support

**IoT & edge** — MQTT · OPC-UA · Edge-to-cloud Orchestration

**Observability** — OpenTelemetry · Prometheus · Grafana · Jaeger · Cloud Trace

**Security & compliance** — Cloud IAM · KMS · HSM · Secret Manager · Cloud Armor · VPC Service Controls · IAP · Cloud DLP · Binary Authorization · Security Command Center · JWT · OAuth 2.0 · OpenID Connect · Zero-Trust · HIPAA · SOC 2 · ISO 27001 · PCI-DSS · KYC/AML

**FinOps** — BigQuery cost optimization · Slot-based capacity planning · Query profiling · Materialized views

**Domain expertise** — FinTech · Open Banking (UAE ADGM/DIFC, Saudi SAMA) · Healthcare Tech · Enterprise AI Adoption

---

## ✍️ I write about

Multi-Agent AI · Google ADK · MCP · Agentic Commerce · BigQuery Graph · LLM determinism · Genkit middleware · and the production realities of building reliable AI systems on Google Cloud.

📖 Follow my posts on [LinkedIn](https://www.linkedin.com/in/pratikdhanave) (2,455+ followers).

---

## 🎓 Certifications

- **Google Cloud Generative AI Leader** — Professional Certificate (Coursera)
- **AWS Certified Generative AI Developer** — Professional (Udemy)
- **Google Cloud Specialization** — Data Engineering, Big Data, and Machine Learning on GCP
- **Ardan Labs** — Ultimate Go and Ultimate Services Go

---

## 📊 GitHub stats

![Pratik's GitHub stats](https://github-readme-stats.vercel.app/api?username=PratikDhanave&show_icons=true&theme=default&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=PratikDhanave&layout=compact&theme=default&hide_border=true&langs_count=8)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=PratikDhanave&theme=default&hide_border=true)

---

> *Looking for senior engineering talent with deep backend + GenAI + multi-region compliance experience? Let's talk.*

<sub>Last updated: July 2026 · Built with care, not with templates.</sub>
