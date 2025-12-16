# AirGAP-AI

**AirGAP-AI** is a privacy-first, fully offline AI technical support assistant designed for use in
regulated and privacy-sensitive environments such as healthcare, finance, and secure enterprises.

This project was developed as a capstone to explore whether useful AI assistance can be delivered
**without cloud connectivity**, **without external logging**, and **without exposing sensitive data**.

---

## 🚨 Important Scope Notice

AirGAP-AI is **not a medical system** and does **not provide clinical or diagnostic advice**.

The system is intentionally constrained to:
- Provide **technical support only**
- Refuse unsafe or non-compliant requests
- Avoid access to patient data or restricted systems

This behavior is **by design**.

---

## 🔍 Problem Statement

Organizations operating in regulated environments face major challenges when adopting cloud-based AI tools:

- Sensitive data may be transmitted or logged externally
- Compliance requirements (HIPAA / GDPR / SOC2) are difficult to verify
- Internet dependency reduces reliability in restricted or isolated networks
- IT staff remain overloaded with repetitive support tasks

As a result, many organizations cannot safely use existing AI assistants.

---

## 💡 Solution Overview

AirGAP-AI addresses these issues by running **entirely on-device**.

The system combines:
- A **locally deployed language model**
- **Locally stored documentation**
- **Prompt-enforced safety and refusal rules**
- **No internet connectivity**
- **No persistent chat history**

All inference and retrieval occur locally.

---

## 🧠 What the System Can Do

- Explain software features and workflows
- Guide users through UI operations (layouts, tools, navigation)
- Troubleshoot technical and connectivity issues
- Provide clear, non-speculative answers
- Safely acknowledge when information is unavailable

---

## 🚫 What the System Will NOT Do

- Access, retrieve, or list patient records
- Expose MRNs, demographics, or other PHI
- Bypass access controls or restricted studies
- Interpret medical images
- Provide diagnoses, treatment recommendations, or clinical advice

---

## 🔐 Safety & Compliance Approach

Rather than claiming regulatory certification, AirGAP-AI demonstrates
**compliance-aligned behavior** through:

- Refusal-by-design for PHI and access-control violations
- Clear separation between technical assistance and clinical decision-making
- Predictable, testable response behavior
- Explicit acknowledgment of system limitations

No claims of HIPAA, GDPR, or SOC2 certification are made.

---

## 🧱 High-Level Architecture

- Local language model running entirely offline
- Retrieval-Augmented Generation (RAG) using local documents
- Strict system prompt enforcing scope and refusals
- No cloud APIs or external services
- No background telemetry or data export

---

## ⚠️ Limitations

- Academic prototype / MVP
- No real patient data
- No clinical interpretation
- Limited to uploaded documentation
- Role-based access control partially designed but not fully enforced

These constraints are intentional and aligned with the project goals.

---

## 📈 Future Work

- Full role-based access control (RBAC)
- Encrypted audit logging
- Expanded domain-specific datasets
- Improved UI integration beyond development tools
- Performance optimization and model quantization

---

## 👤 Author

**Harvansh Aneja**  
Capstone Project – AirGAP-AI  
Southern Alberta Institute of Technology (SAIT)
