# Well Made Decisions Lab

Well Made Decisions Lab is an AI-powered executive decision support system designed to structure, analyze, and stress-test real-world decisions using:

- *Well Made Decisions* (primary framework and source of truth)
- Public decision-making models (OODA, premortem, base rates, reversibility, etc.)
- Prior blog and written materials by Jennifer Davis

The Lab produces structured, citation-backed decision analysis — not conversational advice.

---

## Live Pilot

Pilot Version:
- Built in Voiceflow (a no-code solution which has been designed for chat/voice interface)
- Hybrid retrieval (Book + Blogs + Public Frameworks)
- Structured JSON outputs
- Soft gate (email capture)
- $0 automated email delivery via Google Apps Script

---

## Purpose

Well Made Decisions Lab serves as:

1. A functional AI decision support tool.
2. A practical AI architecture demonstration.
3. A staged migration path from no-code orchestration (Voiceflow) to a production-grade Python RAG system.

---

## Core Capabilities

- Structured decision framing
- Stakeholder mapping
- Assumptions & unknown identification
- Risk register (probability × impact)
- Multi-option generation with reversibility analysis
- Devil’s advocate stress test
- Next best test recommendation
- Explicit source citations

---

## Architecture Overview

### Pilot Architecture
- Voiceflow orchestration layer
- Knowledge Base (Book + Framework documents)
- Structured JSON output enforcement
- Google Forms + Sheets soft gate
- Apps Script auto email

### Planned Production Architecture
- Next.js frontend
- FastAPI backend (Python)
- Supabase Postgres + pgvector
- OpenAI / Claude API
- Langfuse tracing
- Authentication layer
- Report persistence
- Evaluation harness

See `/docs` for detailed architecture documentation.

---

## Why This Project Matters

Most AI demos are chatbots.

Well Made Decisions Lab demonstrates:

- Retrieval-Augmented Generation (RAG) design
- Structured schema enforcement
- Source prioritization
- Governance policies
- Evaluation methodology
- Production migration planning

---

## Roadmap

See `/docs/roadmap.md`

---

## Governance & Data Handling

See `/docs/data-and-governance.md`

---

## Evaluation Framework

See `/docs/evaluation.md`
