# Hi, I'm Pratik 👋

**AI Architect ** · Pune, India

[Portfolio](https://pratikdhanave.com) · [Consulting](https://pratikdhanave.com/services/) · [Blog (1,320+ posts)](https://pratikdhanave.com/blog) · [LinkedIn](https://www.linkedin.com/in/pratikdhanave) · [Book a call](https://calendar.app.google/x7W5bAdst4J6MT2u7) · [Email](mailto:i.pratikdhanave@gmail.com)

**Most AI teams assemble agent frameworks. I harden the runtimes they depend on — upstream in Microsoft, Google, MCP, Apple, and AWS — and take regulated enterprise AI from fragile POCs to governed production.**

7+ years architecting cloud-native, distributed systems in **Go**, **Python**, and **TypeScript** on **GCP**, **AWS**, and **Azure** across **FinTech, healthcare, and critical energy infrastructure** — specializing in **Agentic AI & multi-agent orchestration**, **AI governance & compliance** (RBI FREE-AI, EU AI Act, ADGM/DIFC/SAMA, HIPAA, SOC 2), microservices, gRPC / GraphQL APIs, and cloud FinOps (Google ADK, MCP, Microsoft Agent Framework, Multi-Agent Reference Architecture, Vertex AI Agent Engine, LangChain, LangGraph, CrewAI).

| Upstream Runtime Authority | Commercial FinOps Impact | Mission-Critical Scale | Published Authority |
|---|---|---|---|
| **350+ merged upstream PRs** across **63k+★** repos (Microsoft, Google, MCP, Apple, AWS) | **₹100 Cr+ (~$12M)** saved (**57%** BigQuery cut, productized) | **30K+ TPS** & **1M+ users** (**47%** latency cut) | **118+ series (1,320+ posts)** · Google Next & FDE Speaker · 8-yr GSoC |

---

## ⭐ Open-source contributions

**351 merged external upstream PRs** across **63.5k+ combined stars** — including **274 merged PRs across 12 official Microsoft, Google, MCP, Apple, and AWS repositories** (from **Microsoft Agent Framework Go** and **Google ADK** to **Google Research `timesfm`**, **MCP Go SDK**, **Apple `coreai-models`**, and **AWS**). Not demos or forks: production correctness, concurrency, and security fixes landed in `main`, each with a regression test.

| Repository | Track | Focus |
|---|---|---|
| [**Microsoft Agent Framework Go**](https://github.com/microsoft/agent-framework-go) (701★) | **234 merged PRs** | Runtime correctness across Anthropic & OpenAI providers, workflow engine, A2A, and MCP layers |
| [**Google ADK (Go)**](https://github.com/google/adk-go) (9.0k★) | **17 merged PRs** | Streaming aggregator nil-guards, Pub/Sub concurrency limits, session-state correctness |
| [**MCP Go SDK**](https://github.com/modelcontextprotocol/go-sdk) (5.4k★) | **8 merged PRs** | Event-store bounds panic prevention, JSON-RPC response formatting, URI error diagnostics |
| [**Google Research — TimesFM**](https://github.com/google-research/timesfm) (35.7k★) | **1 merged PR** | Portable Mach page-size detection in system checks ([#554](https://github.com/google-research/timesfm/pull/554)) |
| [**Microsoft Agent Governance Toolkit**](https://github.com/microsoft/agent-governance-toolkit) (6.6k★) | **2 merged PRs** | Docker sandbox execution timeout enforcement ([#3567](https://github.com/microsoft/agent-governance-toolkit/pull/3567)) and opt-in PII redaction ([#3565](https://github.com/microsoft/agent-governance-toolkit/pull/3565)) |
| [**Apple `coreai-models`**](https://github.com/apple/coreai-models) (2.4k★) & [**AWS Durable Execution SDK**](https://github.com/aws/aws-durable-execution-sdk-go) | **1 + 2 merged PRs** | Apple deterministic preset ordering ([#503](https://github.com/apple/coreai-models/pull/503)); AWS O(n) telemetry truncation ([#154](https://github.com/aws/aws-durable-execution-sdk-go/pull/154)) & min-duration seeding ([#155](https://github.com/aws/aws-durable-execution-sdk-go/pull/155)) |
| [**Google `agentmesh`**](https://github.com/google/agentmesh) (1.3k★), [**Google Ads MCP**](https://github.com/googleads/google-ads-mcp) (1.2k★) & [**GCP Hardening Toolkit**](https://github.com/GoogleCloudPlatform/gcp-hardening-toolkit) | **3 merged PRs** | Router loopback host classification ([#880](https://github.com/google/agentmesh/pull/880)), GAQL MCP reference updater fix ([#143](https://github.com/googleads/google-ads-mcp/pull/143)), VPC-SC triage Linux/GNU date portability ([#82](https://github.com/GoogleCloudPlatform/gcp-hardening-toolkit/pull/82)) |
| [**Microsoft `scope`**](https://github.com/microsoft/scope) (93★) | **3 merged PRs** | Null-entry guard in HAR choices ([#1488](https://github.com/microsoft/scope/pull/1488)) and API cache / resource precedence docs ([#1491](https://github.com/microsoft/scope/pull/1491), [#1492](https://github.com/microsoft/scope/pull/1492)) |
| [**Google Cloud Spanner Migration Tool**](https://github.com/GoogleCloudPlatform/spanner-migration-tool) (HarbourBridge, 155★) | **[3 merged](https://github.com/GoogleCloudPlatform/spanner-migration-tool/pulls?q=is%3Apr+is%3Amerged+author%3Apratikdhanave-searce) + [12 in review](https://github.com/GoogleCloudPlatform/spanner-migration-tool/pulls?q=is%3Apr+author%3APratikDhanave)** | Prior core contributor (Intelligent Schema Assistant APIs, Datastream/Pub/Sub/Dataflow CDC) + active schema-conversion panic & GoogleSQL index fixes |
| **Community & Earlier Upstream** ([`skycoin/cx`](https://github.com/skycoin/cx), [`gocloud`](https://github.com/leopardslab/gocloud), [`gocloud-v2`](https://github.com/scorelab/gocloud-v2), [`c2siorg/genie`](https://github.com/c2siorg/genie), [`onflow/cadence`](https://github.com/onflow/cadence) 546★) | **77 merged PRs** | Unified AWS/GCP/Azure Go cloud libraries, CX Pratt parser (~30% lower parsing complexity), Flow Cadence compiler diagnostics, GSoC cloud-native repos |

*Active upstream PRs also in review across `google-deepmind/gemma`, `microsoft/agent-governance-toolkit`, `microsoft/agent-framework-go`, `GoogleCloudPlatform/spanner-migration-tool`, `GoogleCloudPlatform/kubectl-ai`, `openai/gpt-oss`, `vllm-project/vllm`, `aws/bedrock-agentcore-sdk-python`, and `apple/coreai-models`.*

<details>
<summary><strong>Selected PR highlights</strong> (every fix shipped with a regression test)</summary>

**Microsoft Agent Framework Go (234 merged PRs)**
- Closed leaked streaming HTTP bodies on the Anthropic / OpenAI-Responses paths — [#718](https://github.com/microsoft/agent-framework-go/pull/718)
- Released dead references in `concurrent.Queue.Dequeue` — [#598](https://github.com/microsoft/agent-framework-go/pull/598)
- Fixed empty responses in the structured-output middleware — [#607](https://github.com/microsoft/agent-framework-go/pull/607)
- Fixed a nil-update panic in the tool-approval middleware — [#472](https://github.com/microsoft/agent-framework-go/pull/472)
- Removed a dead `PortableValue` guard in the workflow route builder — [#489](https://github.com/microsoft/agent-framework-go/pull/489)

**Google ADK (Go) (17 merged PRs)**
- Guarded a nil first candidate in the streaming response aggregator — [#1802](https://github.com/google/adk-go/pull/1802)
- Honored `MaxConcurrentRuns` in the Pub/Sub controller — [#1720](https://github.com/google/adk-go/pull/1720)
- Maintained session-state `UpdateTime` on app/user state writes — [#1204](https://github.com/google/adk-go/pull/1204)

**MCP Go SDK (8 merged PRs)**
- Prevented a `MemoryEventStore.After` panic on an index past the end — [#1132](https://github.com/modelcontextprotocol/go-sdk/pull/1132)
- Fixed the JSON-RPC response summary to use `%v` and `ID.Raw()` — [#1382](https://github.com/modelcontextprotocol/go-sdk/pull/1382)
- Named the offending path in `computeURIFilepath` localize errors — [#1381](https://github.com/modelcontextprotocol/go-sdk/pull/1381)

**Microsoft Agent Governance Toolkit & Scope (5 merged PRs)**
- Enforced the configured sandbox execution timeout in the Docker provider — [#3567](https://github.com/microsoft/agent-governance-toolkit/pull/3567)
- Added opt-in PII redaction to the credential redactor — [#3565](https://github.com/microsoft/agent-governance-toolkit/pull/3565)
- Guarded against a null entry in the HAR `choices` array (`microsoft/scope`) — [#1488](https://github.com/microsoft/scope/pull/1488)

**Google Research, Google Cloud, Apple & AWS (Nov 2026 merges)**
- `google-research/timesfm` (35.7k★): Parsed Mach page size instead of assuming 4096 — [#554](https://github.com/google-research/timesfm/pull/554)
- `apple/coreai-models` (2.4k★): Sorted `ALL_PRESET_NAMES` for deterministic preset ordering — [#503](https://github.com/apple/coreai-models/pull/503)
- `google/agentmesh` (1.3k★): Covered `isLoopbackBindHost` router host classification — [#880](https://github.com/google/agentmesh/pull/880)
- `googleads/google-ads-mcp` (1.2k★): Fixed `utils` import in `google-ads-mcp-update-gaql` — [#143](https://github.com/googleads/google-ads-mcp/pull/143)
- `aws/aws-durable-execution-sdk-go`: Binary-searched `Truncate` drop count to avoid O(n) re-renders ([#154](https://github.com/aws/aws-durable-execution-sdk-go/pull/154)) and seeded min duration from first timed op ([#155](https://github.com/aws/aws-durable-execution-sdk-go/pull/155))
- `GoogleCloudPlatform/gcp-hardening-toolkit`: Made the 30-day VPC-SC triage window portable to Linux/GNU — [#82](https://github.com/GoogleCloudPlatform/gcp-hardening-toolkit/pull/82)

**Google Cloud Spanner Migration Tool (3 merged + 12 upstream fixes in review)**
- Preserved the `UNIQUE` flag when converting GoogleSQL indexes — [#1422](https://github.com/GoogleCloudPlatform/spanner-migration-tool/pull/1422)
- Fixed a nil-pointer panic on `nextval()` with a bare string argument — [#1467](https://github.com/GoogleCloudPlatform/spanner-migration-tool/pull/1467)
- Keyed ALTER TABLE unique indexes by column ID instead of name — [#1426](https://github.com/GoogleCloudPlatform/spanner-migration-tool/pull/1426)
- Earlier core merges as [`pratikdhanave-searce`](https://github.com/pratikdhanave-searce) ([#303](https://github.com/GoogleCloudPlatform/spanner-migration-tool/pull/303), [#335](https://github.com/GoogleCloudPlatform/spanner-migration-tool/pull/335), [#348](https://github.com/GoogleCloudPlatform/spanner-migration-tool/pull/348)): backend APIs for the Intelligent Schema Assistant, CDC pipelines (Datastream · Pub/Sub · Dataflow), and post-migration query tuning via PK design, indexing, and table interleaving

</details>

---

## 🎯 Current focus & engagements

- **Forward Deployed AI Consulting** — high-impact architecture & delivery for AI engineering teams: [production readiness audits](https://pratikdhanave.com/services/ai-production-readiness-audit/), [POC-to-production rescues](https://pratikdhanave.com/services/poc-to-production-rescue/), and [fractional embedded engagements](https://pratikdhanave.com/services/fractional-fde/)
- **Critical infrastructure AI governance (NESO)** — driving enterprise AI transformation for the UK National Energy System Operator with a strict focus on **AI governance and compliance**
- **Multi-agent AI systems** for FinTech (Google ADK · MCP · Multi-Agent Reference Architecture · Vertex AI Agent Engine)
- **Medical AI** — FHIR R4 + HL7 v2, cost-aware diagnostic budgets, clinical reasoning
- **RAG & GraphRAG pipelines** on AlloyDB AI, BigQuery Knowledge Graph, and pgvector
- **Voice AI assistants** (ElevenLabs + Gemini)
- **Open Banking** — consent management and regulatory compliance (ADGM, DIFC, SAMA)
- **Upstream open-source** — Microsoft Agent Framework Go, Google ADK, Spanner Migration Tool, Genie, and Bodh

> **📍 How we can work together:** Selectively partnering on **consulting mandates** (AI production readiness audits, POC-to-production rescues, fractional FDE — [services](https://pratikdhanave.com/services/)) and **Principal / Staff Engineer, AI Architect, and Solution Architect leadership roles** in Agentic AI, FinTech, Healthcare Tech, GenAI Infrastructure, and Open Banking — Bengaluru, Pune, Mumbai, Hyderabad, Remote, EMEA, UAE.

---

## 🎤 Presentations & talks

- **[Build for RBI, Inherit the EU AI Act](https://github.com/PratikDhanave/Build-For-RBI-Inherit-The-EU-AI-Act)** — **FDExHyderabad (Nov 2026)** · [Interactive Web Deck](https://build-for-rbi-talk.vercel.app) · [Slides, Labs & Cross-Walk](https://github.com/PratikDhanave/Build-For-RBI-Inherit-The-EU-AI-Act)
  What RBI FREE-AI asks of your codebase — and how much of the EU AI Act comes with it. Maps all **17/17 RBI FREE-AI** Regulated Entity controls and **7 inherited EU AI Act controls** to executable Go/Python patterns (composite policy gate, runtime approval-drift detection, tamper-evident SHA-256/Ed25519 audit chain), honestly scores the **RBI Draft MRM Guidance (4 built / 2 open gaps)**, and ships with runnable Pyodide labs, 25 architecture diagrams, a 17-recommendation traceability matrix, and a 5-minute AI vendor procurement scorecard.

| Interactive Talk Deck (Slide 01) | RBI FREE-AI ↔ EU AI Act Cross-Walk (Slide 17) |
| :---: | :---: |
| [![Build for RBI, Inherit the EU AI Act — Cover](https://raw.githubusercontent.com/PratikDhanave/Build-For-RBI-Inherit-The-EU-AI-Act/main/docs/screenshots/01-cover.png)](https://build-for-rbi-talk.vercel.app/#1) | [![RBI FREE-AI to EU AI Act Cross-Walk](https://raw.githubusercontent.com/PratikDhanave/Build-For-RBI-Inherit-The-EU-AI-Act/main/docs/screenshots/16-crosswalk.png)](https://build-for-rbi-talk.vercel.app/#17) |

- **[Migrating Monolith Applications into Microservices](https://drive.google.com/drive/folders/1ny-2QsHxhrtlYofbCN3WL2TbVJXDsnxz)** — **Google Cloud Next 2022**
  Practical patterns for decomposing legacy monoliths into resilient, cloud-native microservices on GCP.

---

## 🚀 Featured projects

### Multi-Agent AI & GenAI

| Project | What it does | Stack |
|---|---|---|
| [**Genie**](https://pratikdhanave.com/blog/posts/adk-03-multi-agent-systems.html) | Multi-agent financial assistant bridging LLMs with real-time banking APIs for autonomous advisory, predictive cash-flow analysis, and transaction orchestration. 15 role-specialized agents on Google's [multi-agent reference architecture](https://docs.cloud.google.com/architecture/multiagent-ai-system). | Go · Multi-Agent Reference Architecture · MCP · Vertex AI Agent Engine · PostgreSQL · OpenTelemetry |
| [**Bodh**](https://pratikdhanave.com/blog/posts/hl7v2-still-matters.html) | Medical AI inspired by Microsoft's [MAI-DxO Sequential Diagnostic Panel](https://microsoft.ai/news/the-path-to-medical-superintelligence/). Virtual physician panel of 7 role-specialized agents (intake, supervisor, questioner, test planner, cost guardian, diagnostician, reasoning verifier); FHIR R4 + HL7 v2 aware with cost-aware diagnostic budget enforcement. | Go · Multi-Agent Reference Architecture · FHIR R4 · HL7 v2 · SD-Bench |
| **Bancnet** | Open Banking portal for UAE (ADGM/DIFC) and Saudi (SAMA) with consent management, data residency, and RAG semantic search on AlloyDB AI — **37% latency reduction**. | Python · Go · FastAPI · RAG · pgvector · AlloyDB AI |
| [**Optimus**](https://pratikdhanave.com/blog/posts/57-percent-bigquery-cost-reduction-tata.html) | Gemini-powered BigQuery analyzer detecting SQL anti-patterns (full scans, inefficient joins, missing partition filters) and recommending optimizations — delivered **57% cost reduction**. | Python · Go · Gemini API · BigQuery |
| **Kinetic India Voice Assistant** | Conversational voice AI for two-wheeler riders — diagnostics, service booking, and ride telemetry, with ElevenLabs voice synthesis and Gemini-backed dialog management. | Python · Go · ElevenLabs · Gemini |

### Backend & Distributed Systems

| Project | What it does | Stack |
|---|---|---|
| **Brownlow** | Zero-trust voting platform for the AFL Brownlow Medal — **100K+ votes**, **10K+ concurrent users** on Cloud Run during live broadcasts; validation, encryption (Cloud KMS), audit logging, and abuse prevention secured with Security Command Center. | Go · GraphQL · gRPC · Cloud Run · Cloud KMS · Pub/Sub |
| **Globe** | Kubernetes transaction platform handling **30K+ TPS** for telecom/FinTech partner integrations — led 10 engineers; idempotent processing, ledger/reconciliation, dual-layer auth (JWT + API keys), and PCI-aligned data protection. | Go · Kubernetes · Kafka · Pub/Sub · Redis |
| **Picnic** | Social network backend serving **1M+ users** — designed Go/gRPC microservices behind a GraphQL API gateway, reducing API response latency by **47%** via protobuf contracts and service consolidation; led a remote-first team of 4. | Go · gRPC · GraphQL · Cloud Spanner |
| [**HarbourBridge**](https://github.com/GoogleCloudPlatform/spanner-migration-tool) | CDC pipelines for minimal-downtime migrations to Cloud Spanner — backend APIs for the Intelligent Schema Assistant with **40–60% post-migration query gains**. | Go · Python · Cloud Spanner · Datastream |
| **Litmus** | Industrial IoT edge data platform — real-time ingestion from manufacturing/energy plants (MQTT, OPC-UA), Python streaming pipelines to cloud analytics, and AI-driven anomaly detection. | Python · Go · MQTT · OPC-UA · Kubernetes |
| **P2P Financial Lending Platform** | Lending platform processing **5K+ loans/month** with a double-entry ledger, 3+ credit bureaus, payment gateways, KYC/AML, fraud detection, and maker-checker RBAC. | Go · PostgreSQL |

---

## 📚 Publications & technical articles

I publish in-depth, multi-part technical series at **[pratikdhanave.com/blog](https://pratikdhanave.com/blog)** — **118+ series (1,320+ posts)** across agentic AI, distributed systems, and production engineering, each grounded in primary sources with runnable examples. [Browse all series →](https://pratikdhanave.com/blog/series/)

**Featured series**
- **[The AI Production Roadmap](https://pratikdhanave.com/blog/series/the-ai-production-roadmap/)** — the 12-phase path from prototype to production AI: governance, evaluation, serving, security, cost
- **[Distributed Systems from First Principles](https://pratikdhanave.com/blog/series/distributed-systems-from-first-principles/)** — consistency models, CAP/PACELC, replication, consensus (Raft), resilience
- **[LLM Inference & Serving](https://pratikdhanave.com/blog/series/llm-inference-and-serving/)** — the KV cache, continuous batching, quantization, speculative decoding, vLLM/PagedAttention
- **[The AI Cost Optimization Playbook](https://pratikdhanave.com/blog/series/the-ai-cost-optimization-playbook/)** — the ranked inference cost levers, vendor-grounded and measured
- **[Adopting AI in the Enterprise](https://pratikdhanave.com/blog/series/adopting-ai-in-the-enterprise/)** — the organizational playbook for crossing pilot-to-production: use cases, readiness, agentic orchestration, scale, security, change
- **[Agent Memory Systems](https://pratikdhanave.com/blog/series/agent-memory-systems/)** — how agents remember, learn, and forget: the memory hierarchy, compaction, retrieval, consolidation, production memory

**Deep dives**
- **[Multi-Agent Systems Architecture](https://pratikdhanave.com/blog/posts/adk-03-multi-agent-systems.html)** — hierarchical coordination patterns, function calling, cost-aware decision trees, observability & cost tracking
- **[BigQuery FinOps: 57% Cost Reduction at Scale](https://pratikdhanave.com/blog/posts/57-percent-bigquery-cost-reduction-tata.html)** — query refactoring, materialized views, MERGE optimization, slot-based capacity planning
- **[FHIR R4 + HL7 v2 Medical AI Interoperability](https://pratikdhanave.com/blog/posts/hl7v2-still-matters.html)** — Bodh architecture, cost-aware diagnostic budgets, HIPAA compliance patterns

**Topics covered** — Multi-Agent AI · agent memory · enterprise AI adoption · Google ADK · MCP · A2A · Agentic RAG · diffusion & generative media · LLM inference & serving · fine-tuning · vector search internals · distributed systems · database internals · web identity (OAuth/OIDC/SAML) · observability · computer networking · RegTech & compliance · AI cost optimization · on-device AI · the agent-framework landscape (LangChain, LangGraph, CrewAI, Pydantic AI, Strands, smolagents, LlamaIndex) · and the Go, Python, and Rust language curricula.

📖 Follow my posts on [LinkedIn](https://www.linkedin.com/in/pratikdhanave) (2,750+ followers).

---

## 🏆 Recognition

- 🎤 **[Speaker at FDExHyderabad (Nov 2026)](https://github.com/PratikDhanave/Build-For-RBI-Inherit-The-EU-AI-Act)** — *"Build for RBI, Inherit the EU AI Act"* ([Live Deck](https://build-for-rbi-talk.vercel.app))
- 🎤 **[Speaker at Google Cloud Next 2022](https://drive.google.com/drive/folders/1ny-2QsHxhrtlYofbCN3WL2TbVJXDsnxz)** — *"Migrating Monolith Applications into Microservices"*
- 🌍 **[Google Summer of Code](https://drive.google.com/drive/folders/1hkLNLNHsQeYevR7fDD2NyymJsnndBCCx)** — Contributor (2017–2018), **[Mentor (2019–2026)](https://drive.google.com/drive/folders/1Tpyidwk7zcicIJuz2sDbqYhCVyDjTOSv)**; guided 10+ students on cloud-native and AI-native projects
- 💼 **Productized Tata Group BigQuery cost-optimization engagement** into Searce's GCP managed service offering — INR ₹100 Cr+ (~$12M) saved, **57% DW cost reduction**

---

## 🎓 Certifications

- **Google Cloud Generative AI Leader** — Professional Certificate (Coursera)
- **AWS Certified Generative AI Developer** — Professional (Udemy)
- **Google Cloud Specialization** — Data Engineering, Big Data, and Machine Learning on GCP
- **Ardan Labs** — Ultimate Go and Ultimate Services Go

---

## 💼 Technical skills

| Area | Technologies & Domains |
|---|---|
| **Languages** | Go · Python · TypeScript · SQL |
| **Multi-Agent AI** | Google ADK · Microsoft Agent Framework · Multi-Agent Reference Architecture · MCP · A2A · LangGraph · LangChain · CrewAI · AutoGen · Pydantic AI · AWS Strands · smolagents · Genkit · Function Calling · ReAct · LLM-as-Judge · Agent Workflows · Cost-aware Constraints |
| **GenAI, Voice & Healthcare AI** | Vertex AI Agent Engine · RAG · GraphRAG · LlamaIndex · BigQuery Knowledge Graph · LangSmith · OpenAI · Anthropic Claude · Google Gemini · AWS Bedrock · Hugging Face · Ollama · MLOps · LLMOps · Voice AI (ElevenLabs, Dialog Management, Multi-language) · Healthcare AI (FHIR R4, HL7 v2, MAI-DxO, SD-Bench, Cost-aware Diagnostic Budgets, Clinical Reasoning) |
| **Cloud & Infrastructure** | GCP (Vertex AI Agent Engine, BigQuery, Cloud Spanner, Cloud Run, Dataflow, Datastream) · AWS (EC2, EKS, Lambda, Bedrock) · Azure (App Service, Cosmos DB, AI Search) · Kubernetes · GKE · EKS · Helm · Docker · Terraform · GitHub Actions · Jenkins |
| **Databases, APIs & Edge** | PostgreSQL · pgvector · Cloud Spanner · BigQuery · AlloyDB AI · Pinecone · MongoDB · Redis · REST · gRPC · GraphQL · FastAPI · Gin · Django · Pub/Sub · Kafka · Apache Airflow · MQTT · OPC-UA · Edge-to-cloud Orchestration |
| **Observability & FinOps** | OpenTelemetry · Prometheus · Grafana · Jaeger · Cloud Trace · BigQuery cost optimization · Slot-based capacity planning · Query profiling · Materialized views |
| **Security & Compliance** | Cloud IAM · KMS · HSM · Secret Manager · Cloud Armor · VPC Service Controls · IAP · Cloud DLP · Binary Authorization · Security Command Center · JWT · OAuth 2.0 · OpenID Connect · Zero-Trust · HIPAA · SOC 2 · ISO 27001 · PCI-DSS · KYC/AML · RBI FREE-AI · EU AI Act |
| **Domain Expertise** | FinTech · Open Banking (UAE ADGM/DIFC, Saudi SAMA) · Healthcare Tech · Energy & Utilities · Enterprise AI Adoption · AI Governance & Compliance |

---

## 📊 GitHub stats

<p>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=PratikDhanave&amp;show_icons=true&amp;theme=github_dark&amp;hide_border=true&amp;bg_color=0d1117" />
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=PratikDhanave&amp;show_icons=true&amp;theme=default&amp;hide_border=true" />
    <img height="165" alt="Pratik's GitHub stats" src="https://github-readme-stats.vercel.app/api?username=PratikDhanave&amp;show_icons=true&amp;theme=default&amp;hide_border=true" />
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=PratikDhanave&amp;layout=compact&amp;theme=github_dark&amp;hide_border=true&amp;bg_color=0d1117&amp;langs_count=8" />
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=PratikDhanave&amp;layout=compact&amp;theme=default&amp;hide_border=true&amp;langs_count=8" />
    <img height="165" alt="Top Languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=PratikDhanave&amp;layout=compact&amp;theme=default&amp;hide_border=true&amp;langs_count=8" />
  </picture>
</p>

<p>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-streak-stats.herokuapp.com/?user=PratikDhanave&amp;theme=dark&amp;hide_border=true&amp;background=0d1117" />
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-streak-stats.herokuapp.com/?user=PratikDhanave&amp;theme=default&amp;hide_border=true" />
    <img height="165" alt="GitHub Streak" src="https://github-readme-streak-stats.herokuapp.com/?user=PratikDhanave&amp;theme=default&amp;hide_border=true" />
  </picture>
</p>

---

## 📧 Reach me

- ✉️ **Email** — [i.pratikdhanave@gmail.com](mailto:i.pratikdhanave@gmail.com)
- 💼 **LinkedIn** — [linkedin.com/in/pratikdhanave](https://www.linkedin.com/in/pratikdhanave) (2,750+ followers)
- 🌐 **Portfolio & Services** — [pratikdhanave.com](https://pratikdhanave.com) · [Consulting Services](https://pratikdhanave.com/services/)
- 📅 **Book a call** — [Google Calendar](https://calendar.app.google/x7W5bAdst4J6MT2u7) · [Topmate](https://topmate.io/pratik_dhanave)

---

> *Taking an Agentic AI system into regulated production — or hiring Principal / Staff AI architecture leadership? [Book a call](https://calendar.app.google/x7W5bAdst4J6MT2u7), review [consulting services](https://pratikdhanave.com/services/), or [send an email](mailto:i.pratikdhanave@gmail.com).*

<sub>Last updated: November 2026 · Built with care, not with templates.</sub>
