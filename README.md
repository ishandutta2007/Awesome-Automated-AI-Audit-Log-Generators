# Awesome-Automated-AI-Audit-Log-Generators

## Top Automated AI Audit Log Generators Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Tamper-Evident Records, Compliance Evidence & Agent Decision Tracing*

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Automated AI Audit Log Generators**. These tools document step-by-step reasoning proofs to satisfy compliance audits—producing cryptographically verifiable records that an independent party can validate without trusting the organization that generated them.



**Examples** include Credo AI, Holistic AI, FairNow, Monitaur, ModelOp, Fiddler AI, IBM watsonx.governance, OneTrust AI Governance, CalypsoAI, and Trustible (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, hash-chained evidence trails, and Ed25519-signed ledgers—ideal for compliance officers, AI engineers, and developers seeking transparent, vendor-independent audit infrastructure.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Credo AI](https://www.credo.ai/)**

  AI governance platform with prebuilt template libraries for use-case intake, model/system registration, risk-and-impact assessment, and policy-attached controls. Publishes a public Responsible AI Standard that its templates crosswalk against. Strongest analyst-tier features are prebuilt intake questionnaires, policy attach mechanism, and tie-out to model documentation .



- **[Holistic AI](https://www.holisticai.com/)**

  Positioned around auditing and monitoring, with a portfolio of technical assessments (bias, robustness, explainability, privacy) that plug into the governance record. Uses these to produce a risk report per system. Strongest analyst-tier features are technical audit modules and export-shaped-for-regulators reports .



- **[ModelOp](https://www.modelop.com/)**

  AI lifecycle management and governance platform. Manages traditional ML models, generative AI, agentic AI, and third-party AI across their full lifecycle. Provides a centralized AI inventory that acts as an auditable system of record, with standardized use case intake, workflow automation for reviews and approvals, policy enforcement, and generation of model cards and audit reports .



- **[IBM watsonx.governance](https://www.ibm.com/products/watsonx-governance)**

  Enterprise-grade AI governance solution managing risk and compliance across the full AI lifecycle. Monitors and governs any AI system—models, applications, or agents—across IBM technologies and third-party platforms including OpenAI, AWS, and Meta. Proactively detects and mitigates AI risks, evaluates AI assets, and secures deployments through Guardium AI security .



- **[OneTrust AI Governance](https://www.onetrust.com/)**

  Enterprise-ready platform for privacy, risk, and AI governance. AI Governance module extends existing workflows with centralized oversight of AI use cases, risks, and compliance obligations. Features AI Discovery and Registry, Dynamic Risk Scoring, Workflow and Approvals, Evidence Collection and Audit Trail, and AI Usage Reporting .



- **[FairNow](https://fairnow.ai/)**

  AI governance platform focused on regulatory compliance and risk management for AI systems.



- **[Monitaur](https://monitaur.ai/)**

  AI assurance and governance software with model monitoring, audit trails, and regulatory compliance features.



- **[Fiddler AI](https://www.fiddler.ai/)**

  Enterprise AI observability and model performance monitoring with explainability, bias detection, and LLM evaluation. Provides drift detection and anomaly monitoring .



- **[CalypsoAI](https://calypsoai.com/)**

  Enterprise AI security at the inference layer. Inference Defend blocks prompt injections, jailbreaks, and data exfiltration in real time with customizable security policies .



- **[Trustible](https://trustible.ai/)**

  AI governance platform with policy management, risk assessment, and regulatory compliance workflows.



## Open-Source GitHub Projects



- **[VerifyWise](https://oecd.ai/en/catalogue/tools/verifywise-aiverifywise)**

  Open-source AI governance, risk, and compliance platform (360 GitHub stars, 123 forks). Creates a central repository for AI systems, models, agents, applications, and suppliers with structured inventory. Features risk assessments, governance decisions, evaluations, responsibility assignment, and mitigation tracking. Maps governance activities across EU AI Act, ISO/IEC 42001, and NIST AI RMF simultaneously—record evidence once and reuse across obligations. Includes AI evaluations and ongoing monitoring for continuous assurance rather than periodic reviews .



- **[Aegis Workbench](https://pypi.org/project/aegis-workbench/0.1.0/)**

  Enterprise AI governance workbench for EU AI Act and NIST AI RMF (Apache-2.0). Catalogs every AI system, classifies against frameworks, evaluates policy-as-code, auto-generates model cards and conformity documentation. Writes every change to an Ed25519-signed append-only ledger. Includes financial-services vertical pack with SR 11-7 model risk and NYDFS Part 500. CLI commands for initialization, system registration, assessment, and Annex IV technical documentation emission .



- **[Vaara](https://oecd.ai/en/catalogue/tools/vaara)**

  Open-source governance and evidence layer for AI agents (AGPL-3.0, 14 GitHub stars). Checks each action against defined policy and produces a verifiable record of what the agent did and why. Features risk scoring with allow/block/escalate decisions, adaptive scoring based on past outcomes, hash-chained audit trail (tamper-evident), offline verification using public key, and EU AI Act article-mapped evidence reports. Adapters for LangChain, CrewAI, and OpenAI Agents SDK. Can act as MCP server proxy. Shadow mode for policy testing .



- **[SealVera](https://pypi.org/project/sealvera/)**

  Python SDK for tamper-evident audit trails for AI agents (open-source). Gives every AI decision a cryptographically-sealed, immutable audit log. Features 2-line integration (decorator, callback, or context manager), explainability built-in (captures inputs, outputs, reasoning, confidence scores, model used), real-time dashboard, drift detection, and works with any LLM (OpenAI, Anthropic, Google Gemini, Ollama, LangChain, CrewAI, AutoGen). Zero hard dependencies—stdlib only. Designed for EU AI Act, SOC 2, HIPAA, GDPR, and ISO 42001 .



- **[GuardClaw](https://pypi.org/project/guardclaw/0.8.0/)**

  Enterprise cryptographic execution evidence and compliance for AI agents (open-source). Transforms every LLM tool execution, model decision, and real-world side-effect into tamper-evident, Ed25519-signed, mathematically verifiable evidence. Features RFC 8785 Canonicalization, Causal Hash DAGs, out-of-process signing daemon (zero private-key exposure), hardware security isolation (FIPS 140-3 via AWS KMS and HashiCorp Vault), RFC 6962 Merkle Inclusion Proofs, turnkey compliance dossiers for EU AI Act Article 12 and ISO/IEC 42001:2023, and MCP Interceptor for zero-code transparent tool call auditing .



- **[arcaeon-audit](https://pypi.org/project/arcaeon-audit/0.1.4/)**

  Tamper-evident, audit-ready logs for AI agents (open-source). Wraps arcaeon-ledger (hash-chained append-only log, zero heavy deps) with the event vocabulary and regulator-ready export for EU AI Act Article 12. Features hash-chained records, external witness for truncation detection, and self-verifying export bundles. Records.jsonl is hash-chained so anyone can re-run verification and reproduce integrity.json—tamper evidence does not depend on trusting the tool or its author .



- **[AuditWeave](https://pypi.org/project/auditweave/)**

  Tamper-evident, auditor-navigable evidence trails for AI-assisted and data-transformation workflows (open-source). Records every step of a workflow—source documents, retrievals, data transformations, model inferences, decisions, and human sign-offs—into a single, append-only, cryptographically chained ledger. Features one vocabulary for RAG and Spark pipelines, SHA-256 hash-chaining, confidential-data friendly (bind to hash of source document), navigable evidence_report(), and zero runtime dependencies (stdlib only). Built for the reviewer who must reconstruct one conclusion from the bottom up .



- **[aiauditlog](https://pypi.org/project/aiauditlog/)**

  Versioned JSON event envelope and schema export for AI audit logging (open-source, pre-release). Features typed Python models for AI, agent, tool, policy, ontology, and benchmark context, RFC8785-backed canonical JSON, SHA-256 event digests, optional hash-chain metadata, checkpoints with optional Ed25519 signatures, JSONL storage and SQLite indexing, stream rotation with independently verifiable files, privacy modes with deterministic redaction, and CLI/Python API. Core event types cover system, agent, model, tool, data, retrieval, policy, review, security, evaluation, and benchmark categories .



- **[merkle-audit](https://pypi.org/project/merkle-audit/)**

  Tamper-evident audit logging for AI agent tool calls (open-source). Every action—web searches, file writes, API calls, payments—is committed to an append-only hash chain. If any historical entry is modified, all subsequent entries become cryptographically invalid. Features simplified Merkle Mountain Range, SQLite persistence, FastAPI integration, and pure Python stdlib with no required dependencies .



- **[Red Hat Asago](https://www.digitaltoday.co.kr/en/view/89229/red-hat-launches-asago-to-lead-open-source-project-automating-ai-governance)**

  Open-source project automating AI governance (Apache-2.0, project formation stage). Automatically converts AI governance policies into operational controls. Four-step workflow: interpret governance policies, map to standards (NIST AI RMF, OWASP LLM Top 10, EU AI Act), generate and run safety tests, recommend mitigation measures, and convert controls into deployment configurations for hybrid cloud and Kubernetes. Outputs include artefacts for Kubernetes, Terraform, and Ansible. Participants include Red Hat, IBM Research, Microsoft, Nvidia, and the Alan Turing Institute .



### Additional Strong Open-Source Options



- **[Arize Phoenix](https://github.com/Arize-ai/phoenix)** — Open-source LLM and ML observability built on OpenTelemetry and OpenInference (Elastic 2.0 license). Strong RAG debugging with nested spans .

- **[OpenTelemetry GenAI Semantic Conventions](https://github.com/open-telemetry/semantic-conventions-genai)** — Vendor-neutral standard attribute names for model calls, agents, and tool use. Foundation for portable audit trails.

- **[OpenLLMetry (Traceloop)](https://github.com/traceloop/openllmetry)** — Apache-2.0 OpenTelemetry instrumentation for LLMs. Emits standard `gen_ai` spans portable to any OTel backend .

- Community **n8n** workflows for audit log export automation and compliance alerting.



**Frameworks for building custom systems**: Combine **GuardClaw** or **SealVera** for cryptographic evidence capture with **VerifyWise** or **Aegis Workbench** for compliance mapping against EU AI Act and NIST frameworks, **AuditWeave** for navigable evidence trails, **Vaara** for runtime agent governance, and **PostgreSQL/ClickHouse** for persistence—creating a fully self-hosted, enterprise-grade audit log generation platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- AI audit log systems handling decision traces must comply with data protection regulations (GDPR, CCPA, etc.) and industry-specific requirements.

- **A plain log file does not satisfy the bar.** Anyone with write access can edit, delete, or reorder a past record and nothing shows. Auditors and regulators want an append-only, integrity-protected record—in practice, a hash chain .

- **Hash chaining is tamper-evident, not immutable.** An attacker who can rewrite an entire unsigned log can recompute the chain. External witnesses (pinning log head to outside record) are needed to detect truncation .

- **Signatures do not prove real-world actor identity or legal non-repudiation.** Ed25519 signatures authenticate the checkpoint bytes to a public key, but proper key custody and identity binding remain the organization's responsibility .

- Self-hosted open-source solutions require proper security hardening, cryptographic key management, and ongoing maintenance. Audit evidence is only as trustworthy as the integrity of the signing infrastructure.



---



**Made for compliance officers, AI engineers, and developers building transparent audit infrastructure.**

Let's make Automated AI Audit Log Generators more open, data-driven, and verifiable.
