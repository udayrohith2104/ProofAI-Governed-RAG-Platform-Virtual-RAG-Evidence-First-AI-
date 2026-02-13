# ProofAI — Governed RAG Platform (Evidence-First AI)

Live Demo: https://proofai-evidence-first-intelligence-633639606830.us-west1.run.app  
Deployment: EU-sovereign (Cloud Run)  
Author: Uday Rohith Reddy Yeruva  

ProofAI is a governed Retrieval-Augmented Generation (RAG) platform built for evidence-first AI in enterprise and regulated environments.  
Unlike typical RAG chatbots, ProofAI enforces policy-aware retrieval, auditability, grounding, and sovereign deployment.

---

## What Makes ProofAI Different

Most RAG systems optimize for answer quality.  
ProofAI optimizes for trust, governance, and compliance.

- Evidence-first responses with citations  
- Policy-aware retrieval (tenant, region, classification)  
- Guardrails for grounding, safety, and PII  
- Full audit logs and trace IDs  
- EU-sovereign deployment pattern  
- Designed for regulated enterprises (fintech, compliance, consulting)

---

## High-Level Architecture (Conceptual)

Client / UI  
→ Secure Gateway (TLS 1.3)  
→ Evidence Vault (classified assets)  
→ Governed Retrieval Layer  
→ Reranking and Context Builder  
→ LLM Runtime (Gemini adapter)  
→ Guardrails (grounding and safety)  
→ Answer with Citations and Audit Log  

This ensures:
- Data residency  
- Classification filters  
- Policy compliance  
- End-to-end traceability  

---

## Demo Capabilities

- Trust Center (TLS 1.3, audit pass indicators)  
- Evidence Vault with document classification  
- Strategic Canvas (Discovery → Interpretation → Implementation → Deployment)  
- EU-sovereign instance monitoring  
- Governed RAG responses with grounding and citations  

---

## Tech Stack

- LLM: Gemini (adapter-based runtime)  
- Backend: Python (FastAPI)  
- RAG orchestration: LangChain / LangGraph (conceptual design)  
- Infrastructure: GCP (Cloud Run)  
- Security: TLS 1.3, policy gates  
- UI: Enterprise dashboard (React-style)

---

## Use Cases

- Regulated enterprise AI (fintech, compliance, consulting)  
- Evidence-grounded decision intelligence  
- Strategy copilots for leadership teams  
- Internal knowledge systems with auditability  
- Policy-compliant AI assistants for sensitive data  

---

## Security and Source Code Notice

This repository intentionally contains architecture, product framing, and a live demo link only.

All production keys, internal endpoints, and proprietary backend services are kept private for security reasons.

No API keys or secrets are exposed in this repository.

---

## Resume-Ready Description

ProofAI – Governed RAG Platform (Personal Project)  
Built an enterprise-grade governed RAG system with evidence-first AI, policy-aware retrieval, auditability, and EU-sovereign deployment using Gemini, FastAPI, and RAG orchestration patterns.

---

## Author

Uday Rohith Reddy Yeruva  
Machine Learning / AI Engineer  
Focus areas: Governed AI, RAG Systems, ML Infrastructure, Enterprise AI  

---

## Disclaimer

This is a research and systems engineering project demonstrating production-grade AI architecture patterns.  
It is not an official product and does not represent any company deployment.

## Collaboration and Research Partnerships

ProofAI is an open research and systems engineering project exploring governed RAG, evidence-first AI, and enterprise-grade AI architecture patterns.

I am open to collaboration with:

- Enterprise AI teams exploring governed or sovereign AI deployments  
- Fintech, compliance, and regulated industry teams evaluating RAG governance patterns  
- Research groups working on trustworthy LLM systems, auditability, and policy-aware retrieval  
- Platform teams interested in piloting evidence-grounded AI workflows  

Potential collaboration formats include:

- Architecture reviews and technical design discussions  
- Proof-of-concept integrations into existing internal systems  
- Joint research experiments and evaluation frameworks  
- Open benchmarking of governed RAG vs standard RAG approaches  

This repository does not expose production credentials.  
Collaboration would be conducted under appropriate security and compliance constraints.

Contact: <your professional email or LinkedIn>
