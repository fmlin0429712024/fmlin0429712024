# Forest Lin

**AI Transformation Consultant & Builder | Forward Deployed Engineering**

I turn complex, regulated operations into practical, governed Agentic AI workflows — from domain discovery and rapid POC development to evaluation, human controls, and a path to production.

My recent work centers on healthcare operations. My background also includes 25 years across enterprise architecture, industrial IoT, energy, manufacturing, technical consulting, and solution delivery. Client deliverables and production artifacts are protected by confidentiality obligations; the public POCs below are intentionally synthetic, concise examples created to communicate my workflow and solution-design approach.

## DeepSeek Harness Plugins

I build vertical solutions on [DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness) (DSH) — a plugin-composable agent platform where every surface (host tools, browser UI, agent skills) is a Cordis bundle. My plugins package governed, fully traceable domain workflows that run on the stock DSH GUI with zero UI changes.

| Plugin | What it does | Status |
| --- | --- | --- |
| [dsh-cdi-plugin](https://github.com/fmlin0429712024/dsh-cdi-plugin) | Synthetic **CDI (clinical documentation integrity) auditing** for DSH — SQLite-backed deterministic SOP-rule evaluation, packaged agent skills, bundled (fictional) gold sets. Every finding stays `requires_human_review` and routes to a human reviewer. | ✅ v0.1.0 · runs on DSH `0.1.0-rc.6` |
| dsh-cdi-gui *(planned)* | Client-half UI for the CDI plugin: audit-finding cards, evidence/rule detail panel, human-review workbench — enterprise domain UI inside the DSH shell. | 🔜 Step 2 |

```sh
# try it — synthetic data only, never real patient data
dsh plugin --profile web add dsh-cdi-plugin
```

## Selected Agentic AI POCs

### Healthcare

- [Agentic CareLoop for In-Center Hemodialysis (ICHD)](https://github.com/fmlin0429712024/ichd-agentic-system)
- [In-center hemodialysis (ICHD) Clinical Documentation Audit](https://github.com/fmlin0429712024/clinical-documentation-audit-poc)
- [ESRD Risk Adjudication: As-Is → To-Be](https://github.com/fmlin0429712024/esrd-risk-adjudication-evolution)
- [Prior Authorization Operations](https://github.com/fmlin0429712024/healthplan-process-poc)
- [Formulary Exception Adjudication](https://github.com/fmlin0429712024/formulary-exception-adjudication-poc)
- [Drug Discovery Research Loop](https://github.com/fmlin0429712024/synthetic-in-silico-research-loop)

### Industrial

- [Asset Performance AI — ESP Predictive Maintenance (Upstream Oil & Gas)](https://github.com/fmlin0429712024/industrial-operations-ai-poc)

### Financial Services

- [Clearing Operations](https://github.com/fmlin0429712024/ai-clearing-operations-poc)

### Cross-industry — AI Operations Lifecycle (AgenticOps / LLMOps / MLOps)

Three labs, one shared lifecycle shape — register, deploy, monitor, rollback. Each demonstrates a
different layer: which asset changes, and how it's evaluated.

- **AgenticOps** — [Customer Care Operations — Harness & Governance Showcase](https://github.com/fmlin0429712024/customer-care-agents)
  Application-level and platform-managed deployment patterns; OpenTelemetry tracing, PII guardrails, sessions/state, durable-memory design, A2A integration, evaluation gates, and human-in-the-loop feedback.
- **LLMOps** — [LLM Platform Engineering Lab](https://github.com/fmlin0429712024/LLM-Playground)
  Secure multi-model experimentation platform showcasing Google Cloud architecture, model comparison, token and latency telemetry, access control, and operational observability.
- **MLOps** — [ESKD Fine-Tuning & MLOps Lab](https://github.com/fmlin0429712024/domain-adaptation-lab)
  End-to-end local model lifecycle: QLoRA fine-tuning and held-out evaluation on synthetic nursing notes, a promotion/registry gate, Ollama serving, and a conceptual map to what Vertex AI Pipelines/Kubeflow would automate on top.

### Palantir Foundry / Ontology, and Other initatives

- [Foundry Ontology Lab — Order Operations After a Merger](https://github.com/fmlin0429712024/foundry-poc)
  Hands-on with Palantir Foundry's core architecture: CLI/SDK-first ingestion and PySpark transforms into a unified dataset, an Ontology object type backed by it, and a live, governed `Assign` action (writeback-enabled edit layer, verified end-to-end via SDK). First in a set of Foundry Foundations labs — more to follow.
- [Physical AI Lab — Imitation Learning](https://github.com/fmlin0429712024/mujoco-robot-pipeline)
  MuJoCo robot-arm pick-and-place via ACT (imitation learning). Data collection and training are done; evaluation/deployment is in progress. A different modality of the same MLOps question, not folded into the lifecycle set above until it closes the loop.
## Focus

Workflow-first AI design · skills orchestration · human-in-the-loop controls · evaluation and observability · deployment-oriented engineering

> These are public-safe, synthetic POCs created to communicate workflow and solution design. They contain no client data, proprietary code, confidential materials, or client deliverables.

[LinkedIn](https://www.linkedin.com/in/forest-lin-7672186/) · [Email](mailto:fmlin429@gmail.com)
