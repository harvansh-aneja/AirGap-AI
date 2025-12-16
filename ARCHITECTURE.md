# Architecture Overview

AirGAP-AI is designed as an offline-first AI system intended for privacy-sensitive environments.

## Core Components

- Local language model executed entirely on-device
- Local document storage used for retrieval-augmented generation (RAG)
- Strict system prompt enforcing:
  - Technical-only scope
  - Refusal of PHI access
  - Refusal of access-control bypassing
  - Refusal of clinical interpretation
- No internet access
- No cloud services or APIs

## Design Principles

- Privacy by default
- Predictable and testable behavior
- Clear scope boundaries
- Refusal as a safety feature

All inference and retrieval occur locally.
No user queries are transmitted or stored beyond the active session.
