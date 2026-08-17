# AI SECURITY SKILLS & EXPERIENCE MAP
Slam's AI Security Experience -  For each skill: what it means, what's done, and where.

# AI Trust & Safety
Ensuring AI systems produce safe, reliable, and non-harmful outputs — and that the infrastructure they run on is trustworthy.

— Salesforce — Owned the cryptographic trust infrastructure underpinning Agentforce — every agent authenticates through PKI primitives - Einstein Trust Layer security foundations.

— Berkeley – Agentic AI Research — Graduate research on Continuous Verifiable Trust model for autonomous agents and NHIs — defining what 'trust' means when humans are out of the loop.

— TotalView Capstone — Shipped hardware-rooted AI guardrails platform (Android StrongBox + C2PA) defending against deepfake content — end-to-end trust chain from capture to publication.

# Guardrails & Responsible AI
Technical and policy controls that constrain AI agent behavior — what it can say, do, access, or decide autonomously.

— Berkeley – Agentic AI Research — Designed MCP/A2A guardrails: prompt injection defense, containerized sandboxing, behavioral anomaly detection, circuit-breaker incident response, and HITL escalation — referenced OWASP Agentic Apps Top 10 2026.

— TotalView Capstone — Implemented content-level guardrails using C2PA cryptographic manifests — every piece of AI-generated content carries a verifiable provenance chain.

— Salesforce — Authored a 3-year PKI strategy covering Einstein Trust Layer security primitives — the infrastructure layer that guardrails depend on.

# NHI & Agentic AI Governance
Managing the identity, permissions, lifecycle, and auditability of Non-Human Identities — AI agents, service accounts, bots, and automated pipelines.

— Berkeley – Agentic AI Research — Defined the 'Identity Debt' framework — the accumulated risk from untracked, over-privileged, and unrotated NHIs in enterprise environments. Designed Continuous Verifiable Trust model for NHI lifecycle governance.

— Salesforce — PKI infrastructure issues every certificate for Agentforce agents and Hyperforce workloads — 35M+ certs/day. Direct operational experience with machine identity at scale.

— Venafi — Led Group PM team across machine identity portfolio ($300M ARR) — PKI/TLS, SSH, Code Signing. Machine identity is the precursor discipline to NHI governance.

# Prompt Injection Defense
Preventing malicious inputs from hijacking LLM behavior — causing agents to ignore instructions, leak data, or take unauthorized actions.

— Berkeley – Agentic AI Research — Designed prompt injection defense as a core guardrail layer in MCP/A2A security architecture — including input sanitization, instruction hierarchy enforcement, and sandboxed tool execution.

— Berkeley – 207 AI/ML — Text classification project (Project 3) directly models the challenge: classifying inputs as safe vs. adversarial using TF-IDF and n-grams — the same techniques used in production injection detection.


# LLM Security
Understanding and mitigating threats specific to large language models — hallucination, jailbreaking, model inversion, training data leakage, and supply chain attacks.

— Berkeley – 207 AI/ML in Cybersecurity — Coursework covered the LLM security threat landscape — hallucination risks, model inversion, adversarial prompting, and training data privacy.

— Berkeley – Agentic AI Research — Research focused on LLM-specific attack surfaces in agentic contexts: tool poisoning, context manipulation, and cross-agent prompt injection.

— Salesforce — Einstein Trust Layer PM — the product layer that governs what LLMs can see, do, and return in enterprise Salesforce contexts.

# AI Content Provenance
Cryptographically verifying the origin, authenticity, and integrity of AI-generated content — who made it, when, on what device, and whether it has been altered.

— TotalView Capstone — Built and shipped TotalView — a C2PA-based content provenance platform. Hardware-rooted trust chain using Android StrongBox from capture through zero-trust server validation and publication. Stack: Android/Kotlin, Rust c2pa-rs, AWS Lambda/FastAPI, PostgreSQL/PostGIS, React/Mapbox.

— Berkeley – Capstone Research — Deep study of C2PA (Coalition for Content Provenance and Authenticity) standard — the emerging industry framework for AI content attribution adopted by Adobe, Microsoft, Google, and others.


# AI/ML Threat Detection & Adversarial ML
Using ML to detect attacks — and understanding how ML-based detectors can themselves be attacked through adversarial inputs and data poisoning.

— Berkeley – 207 AI/ML (IDS Research) — Trained an ML IDS classifier on CIC-IDS2017/2018 dataset across 18 attack categories (DoS, DDoS, brute force, port scan, web attacks, botnets). Then adversarially attacked it — demonstrated data poisoning blind spots where entire attack categories were silently missed.

— Berkeley – 207 AI/ML (Projects 1–4) — Built and evaluated multiple classifiers (KNN, Naive Bayes, Logistic Regression, GMM); analyzed model calibration, distribution shift, and feature selection — all foundational to building robust detection systems.

— Salesforce — PKI anomaly detection — certificate expiry risk, CA concentration exposure, and trust chain failure patterns surfaced through CrowdStrike integration, CTLOG, and DNS attribution.

# MCP/A2A Security
Securing Model Context Protocol (MCP) and Agent-to-Agent (A2A) communications — the channels through which AI agents invoke tools, share context, and coordinate actions.

— Berkeley – Agentic AI Research — Designed MCP/A2A security architecture: authentication of agent calls, authorization scoping for tool use, payload integrity verification, sandboxed execution environments, and anomaly detection on inter-agent traffic.

— Salesforce — PKI infrastructure provides the cryptographic identity layer that MCP/A2A security depends on — mTLS, certificate-based authentication, and short-lived credential issuance for service-to-service calls.

# Identity Threat Detection & Response (ITDR)
Detecting and responding to attacks targeting identity systems — credential theft, privilege escalation, lateral movement via compromised service accounts, and NHI abuse.

— Berkeley – Agentic AI Research — 'Identity Debt' framework defines the accumulation of untracked NHIs as a systemic ITDR risk — the attack surface grows silently with every unmanaged agent credential.

— Berkeley – Managing Cyber Risk — Risk quantification coursework: modeling identity-related threat scenarios, blast radius estimation, and incident response planning for identity compromise.

— Salesforce — Trusted advisor engagements with CISOs and BISOs on identity and security posture — including PKI failure modes, certificate expiry outages, and CA concentration risk as identity infrastructure threats.

— Venafi — Machine identity portfolio — SSH key sprawl, code signing key compromise, and TLS certificate abuse are all ITDR scenarios at the machine identity layer.

# Zero Trust for AI
Applying Zero Trust principles to AI systems — never trust an agent implicitly, always verify identity and authorization, enforce least-privilege access, assume breach.

— Berkeley – Network Security & Cloud Security — Zero Trust Architecture coursework — network segmentation, identity-based access, continuous verification, and micro-segmentation applied to cloud and agent environments.

— TotalView Capstone — Zero-trust server validation layer — every content claim is verified cryptographically regardless of source; no implicit trust in any content submission.

— Salesforce — Paved Path PKI — 100% mTLS coverage enforces Zero Trust at the network layer for Hyperforce workloads. Every service-to-service call requires a valid certificate.

# Threat Modeling for AI Systems
Systematically identifying attack surfaces, threat actors, and mitigations specific to AI pipelines — training data, model serving, inference APIs, agent tools, and output channels.

— Berkeley – Managing Cyber Risk — Formal threat modeling coursework — STRIDE framework, attack trees, risk quantification, and mitigation prioritization applied to modern AI and cloud systems.

— Berkeley – Agentic AI Research — Threat modeled agentic AI pipelines end-to-end: input injection, tool poisoning, memory manipulation, output exfiltration, and cross-agent lateral movement.

— Salesforce — Chrome mTLS mandate response — cross-functional threat assessment across PKI, BISOs, MuleSoft, and TPM teams; 3-year PKI strategy built from a comprehensive threat model of CA failure scenarios.

# Circuit-Breaker & Incident Response for AI
Automated controls that halt or constrain AI agent behavior when anomalous patterns are detected — preventing damage propagation before human review.

— Berkeley – Agentic AI Research — Designed circuit-breaker incident response as a guardrail primitive: threshold-based action suspension, HITL escalation triggers, and state rollback mechanisms for autonomous agent pipelines.

— Salesforce — PKI incident response — Paved Path onboarding with zero outage across all environments; chrome mTLS mandate response as a cross-team coordinated circuit-breaker pattern at the platform level.

# HITL (Human-in-the-Loop) Controls
Decision points where AI agents pause and escalate to human review — ensuring humans remain in control for high-stakes or ambiguous actions.

— Berkeley – Agentic AI Research — Designed HITL escalation framework for autonomous agents: defining escalation triggers, confidence thresholds, approval workflows, and audit trails for agent decisions that require human sign-off.

— Salesforce — BISO engagement model — worked with Business Information Security Officers to define where human review is required in automated security workflows; mapped to Agentforce trust primitives.

# Secure Software Development & Vulnerability Management
Building security into the software development lifecycle — threat-aware design, code review, dependency scanning, and CVE response.

— Berkeley – Software Security — Coursework in secure coding practices, vulnerability classes (buffer overflow, injection, deserialization), SAST/DAST tooling, and CVE lifecycle management.

— Salesforce / Venafi / Thales — Product ownership across security platforms — PKI, key management, data protection. Direct experience defining security requirements, reviewing threat models, and managing vulnerability disclosure across enterprise security products.
— Ingrian / SafeNet (Engineering) — Spent 7 years as a software engineer building cryptographic systems — KMS, HSM integrations, PKI libraries. Security-first engineering is foundational, not learned later.

