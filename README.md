# Riserva-Fly
Riserva Flywheel is an open‑source AI‑native operating system for capital formation. It standardizes ventures, structures investor graphs, automates outreach and diligence, and logs measurable outcomes to continuously improve every raise. A closed‑loop system designed to compound institutional memory, speed, and conversion over time.
# Contributing to Riserva Flywheel

First — thank you.

Riserva Flywheel is an open-source Capital Formation Operating System.
We are building infrastructure for structured, compounding fundraising.

This is not a CRM.
This is not a data room.
This is a closed-loop capital engine.

If you want to build capital-native infrastructure, you're in the right place.

---

## 🎯 Project Mission

To transform capital formation from:
- spreadsheet-driven
- email-fragmented
- memory-dependent

Into:
- structured
- automated
- AI-native
- compounding

Every raise should improve the next raise.

---

## 🏗 Architecture Direction (Opinionated)

Reference implementation:

- **Database:** PostgreSQL
- **Backend:** Node.js or Python (FastAPI preferred)
- **Automation Layer:** n8n (or similar orchestration)
- **Agent Layer:** OpenAI API
- **Email Integration:** Gmail API
- **Calendar Integration:** Google Calendar API
- **Storage:** S3-compatible or structured document layer
- **API Style:** REST (v1), GraphQL optional later

We prioritize:
- Structured data models
- Clear object boundaries
- Event logging
- Deterministic pipelines
- Artifact generation

---

## 📦 Core Objects

The system revolves around:

- Venture
- Investor
- Deal
- Interaction
- Artifact
- Value Ledger Event

If you propose a new object, explain:
1. Why it exists
2. What problem it solves
3. How it fits into the flywheel

---

## 🧠 Design Principles

1. Artifact-first, not activity-first  
2. Every stage must produce persistent data  
3. No “black box” automation without traceability  
4. Gates prevent premature progression  
5. Every action must improve the system  

If a feature does not strengthen the flywheel, it does not belong.

---

## 🛠 How to Contribute

### Step 1 — Pick an Issue

Start with:
- `good first issue`
- `schema`
- `matching`
- `agent`
- `automation`

Do not build random features.
Always align with roadmap.

---

### Step 2 — Fork & Branch

```bash
git fork
git checkout -b feature/short-description
