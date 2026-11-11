# Kedar Mohile

**GenAI Security | Agentic AI Security | AI Red Teaming | Cloud & Regulated Systems**

I work at the intersection of **cybersecurity, generative AI, cloud architecture, and regulated technology**. My focus is building and evaluating secure AI systems: agentic workflows, LLM applications, identity and authorization boundaries, AI threat detection, healthcare security, and production controls for high-risk environments.

I bring **22+ years of cybersecurity and technology experience** across enterprise cloud, healthcare, financial services, and other regulated systems, spanning hands-on architecture, security engineering, and executive security leadership.

## Flagship security lab

**[Agentic AI Security Lab](https://github.com/kedarmohile/agentic-ai-security-lab)** — reproducible security labs for GenAI and agentic AI systems.

- **Lab 01: Cross-Actor Persistent Memory Isolation** — deterministic benign-canary harness, explicit positive/negative controls, structured JSON evidence, threat model, result schema, and regression tests.
- **Lab 02: Tool Authorization Boundary** — side-effect-free indirect-injection harness with trusted approvals bound to actor, request, tool, and exact arguments; includes replay and argument-substitution controls.
- **Lab 03: Retrieval / Persistent-Memory Poisoning** — delayed-ingestion/retrieval harness that separates poison persistence, retrieval, directive exposure, and demonstrated downstream influence.
- All three labs are CI validated on **Python 3.11, 3.12, and 3.13**.
- Built to distinguish real security-boundary failures from broken controls, retrieval exposure without impact, intentionally shared state, or legitimately authorized actions.

## Current open-source security work

| Project | Work | Status |
| --- | --- | --- |
| [Medplum](https://github.com/medplum/medplum) | [Save fetched Agent logs as FHIR DocumentReference/Binary](https://github.com/medplum/medplum/pull/11368) — persistence, auditability, security context, UI regression tests | **Draft PR #11368** |
| [NVIDIA garak](https://github.com/NVIDIA/garak) | [Cross-actor isolation of persistent agent memory](https://github.com/NVIDIA/garak/issues/2453) — proposed benign-canary probe for cross-user memory leakage | **Issue #2453 · needs triage** |
| [Elastic detection-rules](https://github.com/elastic/detection-rules) | [AWS Bedrock AgentCore cross-actor user-preference memory access](https://github.com/elastic/detection-rules/issues/6722) — behavioral ES\|QL detection for memory-isolation failure | **Rule proposal #6722** |

These contributions share a common theme: **security boundaries in stateful and agentic AI systems**—especially where identity, persistent memory, observability, and authorization meet.

## Security engineering focus

- **GenAI & Agentic AI Security** — prompt injection, indirect injection, excessive agency, tool abuse, memory poisoning, cross-actor memory isolation, RAG security, output handling
- **AI Red Teaming & Detection Engineering** — attack-path modeling, behavior-based detections, threat-informed testing, telemetry design, adversarial evaluation
- **Identity & Authorization** — least privilege, workload identity, cross-user isolation, service-to-service trust, policy enforcement
- **Healthcare & Regulated Systems** — FHIR, PHI/PII protection, auditability, secure AI workflows, compliance-aligned architectures
- **Cloud Security** — AWS security architecture, encryption, KMS, TLS/mTLS, secure APIs, workload isolation, observability
- **Resilience** — ransomware detection and response, threat intelligence, secure-by-design architecture, production security controls

## Frameworks & standards

`MITRE ATLAS` · `MITRE ATT&CK` · `NIST AI RMF` · `NIST SP 800-53` · `ISO/IEC 42001` · `OWASP LLM Top 10` · `CSA AI Controls` · `SOC 2` · `PCI DSS`

## Areas I am actively exploring

- Authorization models for **AI agents and tool-calling systems**
- **Persistent-memory isolation** across users, actors, sessions, and tenants
- Security telemetry for **agentic AI runtimes**
- Detection of prompt injection and memory manipulation without relying only on prompt text
- Secure RAG and retrieval-layer trust boundaries
- Human-in-the-loop controls for privileged AI actions
- Security patterns for healthcare AI and other regulated workloads

## Engineering philosophy

> AI security should be testable, observable, and enforceable at runtime—not only described in policy.

I prefer security controls that leave evidence: reproducible tests, explicit authorization boundaries, durable telemetry, measurable detections, and reviewable open-source implementations.

## Connect

- GitHub: [@kedarmohile](https://github.com/kedarmohile)
- Open-source discussions and contributions are welcome around **GenAI security, agentic AI, AI red teaming, healthcare security, detection engineering, and cloud security**.
