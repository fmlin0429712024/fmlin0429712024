# Forest Lin

**Founder of LinkHealth · AI Transformation Consultant & Builder**

I'm building **LinkHealth** — agent-driven, human-governed AI services for
healthcare operations — on DeepSeek Harness, where every capability is a plugin
and every product is a profile. 25 years across enterprise architecture,
industrial IoT, energy, manufacturing, technical consulting, and solution
delivery. Client deliverables are protected by confidentiality obligations; the
public work below is intentionally synthetic and concise, created to
communicate workflow and solution-design approach.

## LinkHealth — the product (in progress)

Agent-driven services for healthcare operations. Every finding stays
`requires_human_review`; everything is auditable; all data is synthetic.

| Capability | What it does | Status |
| --- | --- | --- |
| **Triage** | Classifies, scores, and routes inbound business enquiries — with a PHI guardrail (no auto-dispatch when patient data is involved) | ✅ running |
| **CDI Audit** | Clinical-documentation integrity auditing against deterministic SOP rules (SQLite-backed) | ✅ running |

**Architecture — capability as plugin, product as profile:**

- One DSH installation, many profiles = one install, many products
- `web` (clean dev workbench) vs `linkhealth` (the product): plugins are shared
  assets, referenced not copied
- The profile is the deployment unit: the same files run locally and on a cloud VM

## Technology assets (open)

The plugins behind LinkHealth, as reference implementations:

| Plugin | What it does | Status |
| --- | --- | --- |
| [linkhealth-triage](https://github.com/fmlin0429712024/linkhealth-triage) | The **triage** capability — skill, spokes, and a deterministic PHI guardrail — packaged for Claude Code and DSH | ✅ running |
| [dsh-cdi-plugin](https://github.com/fmlin0429712024/dsh-cdi-plugin) | The **CDI audit** capability — SQLite-backed deterministic SOP-rule evaluation, packaged agent skills, bundled (fictional) gold sets. Every finding stays `requires_human_review` and routes to a human reviewer. | ✅ v0.1.0 · runs on DSH `0.1.0-rc.6` |

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

### Exploratory — outside the system above

- [Physical AI Lab — Imitation Learning](https://github.com/fmlin0429712024/mujoco-robot-pipeline)
  MuJoCo robot-arm pick-and-place via ACT (imitation learning). Data collection and training are done; evaluation/deployment is in progress. A different modality of the same MLOps question, not folded into the lifecycle set above until it closes the loop.

## Focus

Workflow-first AI design · skills orchestration · human-in-the-loop controls · evaluation and observability · deployment-oriented engineering

> These are public-safe, synthetic POCs created to communicate workflow and solution design. They contain no client data, proprietary code, confidential materials, or client deliverables.

[LinkedIn](https://www.linkedin.com/in/forest-lin-7672186/) · [Email](mailto:fmlin429@gmail.com)
