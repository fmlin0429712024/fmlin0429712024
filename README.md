# Forest Lin

**AI Transformation Consultant & Builder | Forward Deployed Engineering**

I turn complex, regulated operations into practical, governed Agentic AI workflows — from domain discovery and rapid POC development to evaluation, human controls, and a path to production.

My recent work centers on healthcare operations. My background also includes 25 years across enterprise architecture, industrial IoT, energy, manufacturing, technical consulting, and solution delivery. Client deliverables and production artifacts are protected by confidentiality obligations; the public POCs below are intentionally synthetic, concise examples created to communicate my workflow and solution-design approach.

**Currently building:** LinkHealth — an AI service company for healthcare operations, built as composable plugins on DeepSeek Harness (every capability is a plugin, every product is a profile). See the featured showcase below.

## Featured — LinkHealth VAS Showcase

An AI service company for healthcare operations, built as composable plugins on DeepSeek Harness. Big picture: every capability is a plugin, every product is a profile, and the same files run locally and on a cloud VM.

**🔗 Source of truth: [linkhealth-dsh-platform](https://github.com/fmlin0429712024/linkhealth-dsh-platform)** — the monorepo that owns **all** LinkHealth DSH plugins going forward. Every push is CI-tested (unit + contract + headless E2E gate) and auto-deployed to the GCP VM. The earlier capability repos are early exploration, kept for reference only.

| Capability | What it does | Status |
| --- | --- | --- |
| **Triage** · [plugin](https://github.com/fmlin0429712024/linkhealth-dsh-platform/tree/main/plugins/dsh-triage-plugin) | Classifies, scores, and routes inbound business enquiries — with a PHI guardrail (no auto-dispatch on patient data) | ✅ running |
| **Clinical Audit (CDI)** · [plugin](https://github.com/fmlin0429712024/linkhealth-dsh-platform/tree/main/plugins/dsh-cdi-plugin) | Clinical-documentation integrity auditing against deterministic SOP rules (SQLite-backed) | ✅ running |
| **Vision Insights** · [plugin](https://github.com/fmlin0429712024/linkhealth-dsh-platform/tree/main/plugins/dsh-vision-insights-plugin) | Reads structured events (zone occupancy, retail item add/remove) from an OpenVINO edge app over HTTP — deterministic facts, LLM narrates only | ✅ running |
| **Front Door (GUI)** · [plugin](https://github.com/fmlin0429712024/linkhealth-dsh-platform/tree/main/plugins/dsh-linkhealth-gui-plugin) | Branded DSH web front door — capability launcher (Triage & CDI Audit cards) | ✅ running |

## Selected showcases

Depth by area: **healthcare operations (6)** — deepest and most recent; cross-industry lifecycle labs (3); industrial (1); financial (1); Palantir Foundry below.

| Project | What it is | Area |
| --- | --- | --- |
| [Agentic CareLoop for ICHD](https://github.com/fmlin0429712024/ichd-agentic-system) | Agentic care coordination loop for in-center hemodialysis | Healthcare |
| [ICHD Clinical Documentation Audit](https://github.com/fmlin0429712024/clinical-documentation-audit-poc) | Governed clinical-documentation audit pipeline — the engine behind CDI Audit | Healthcare |
| [ESRD Risk Adjudication](https://github.com/fmlin0429712024/esrd-risk-adjudication-evolution) | As-is → to-be risk adjudication workflow evolution | Healthcare |
| [Prior Authorization Operations](https://github.com/fmlin0429712024/healthplan-process-poc) | Prior-auth process automation in health plans | Healthcare |
| [Formulary Exception Adjudication](https://github.com/fmlin0429712024/formulary-exception-adjudication-poc) | Formulary exception decision workflow | Healthcare |
| [Drug Discovery Research Loop](https://github.com/fmlin0429712024/synthetic-in-silico-research-loop) | Synthetic in-silico research loop | Healthcare |
| [Asset Performance AI](https://github.com/fmlin0429712024/industrial-operations-ai-poc) | ESP predictive maintenance (upstream oil & gas) | Industrial |
| [Clearing Operations](https://github.com/fmlin0429712024/ai-clearing-operations-poc) | Financial clearing workflow automation | Financial |
| [Customer Care Agents](https://github.com/fmlin0429712024/customer-care-agents) | AgenticOps: OTel tracing, PII guardrails, durable memory, A2A, evaluation gates, human-in-the-loop | Cross-industry |
| [LLM Platform Engineering Lab](https://github.com/fmlin0429712024/LLM-Playground) | LLMOps: secure multi-model platform, token/latency telemetry, access control, observability (GCP) | Cross-industry |
| [ESKD Fine-Tuning & MLOps Lab](https://github.com/fmlin0429712024/domain-adaptation-lab) | MLOps: QLoRA fine-tuning, held-out evaluation, promotion gate, Ollama serving | Cross-industry |

The three cross-industry labs share one lifecycle shape — register, deploy, monitor, rollback — each demonstrating a different layer of the same question: which asset changes, and how it's evaluated.

### Palantir Foundry / Ontology, and Other initiatives

- [Foundry Ontology Lab — Order Operations After a Merger](https://github.com/fmlin0429712024/foundry-poc)
  Hands-on with Palantir Foundry's core architecture: CLI/SDK-first ingestion and PySpark transforms into a unified dataset, an Ontology object type backed by it, and a live, governed `Assign` action (writeback-enabled edit layer, verified end-to-end via SDK). First in a set of Foundry Foundations labs — more to follow.
- [Physical AI Lab — Imitation Learning](https://github.com/fmlin0429712024/mujoco-robot-pipeline)
  MuJoCo robot-arm pick-and-place via ACT (imitation learning). Data collection and training are done; evaluation/deployment is in progress. A different modality of the same MLOps question, not folded into the lifecycle set above until it closes the loop.

## Focus

Workflow-first AI design · skills orchestration · human-in-the-loop controls · evaluation and observability · deployment-oriented engineering

> Public-safe, synthetic showcases for communicating workflow and solution design — no client data, proprietary code, or confidential materials.

[LinkedIn](https://www.linkedin.com/in/forest-lin-7672186/) · [Email](mailto:fmlin429@gmail.com)
