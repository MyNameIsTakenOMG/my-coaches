---
status: DRAFT
project_name: '[Insert Project Name]'
created: '[yyyy-mm-dd]'
updated: '[yyyy-mm-dd]'
tags:
  - socio-technical
  - deliberate-practice
type: practice-session
---

# 🗺️ Socio-Technical Architecture Practice Note (Living Journey)

> This is an append-only living document. Never overwrite `reasoning` or `decisions`. Coach is the sole writer.

## 📌 Business Context

- **Scenario:** [Coach-generated business situation — 3-5 sentences]
- **Goal:** [What the business is trying to accomplish / North Star]
- **Known Constraints:** [Engineering, regulatory, time-to-market, headcount, etc.]
- **Initial Info Provided:** [Seed facts at start]

---

## 🔄 Analysis State — State Machine (for pause/resume)

```yaml
current_stage: 1
status: not_started # not_started | in_progress | awaiting_feedback | done | revisited
next_focus: '[stage task]' # e.g. Identify primary actors
active_cross_cutting_concern: null # e.g., consistency, cognitive load, compliance
blocked_by: null # e.g., awaiting research on X, awaiting clarification on Y
stages_status:
  1: not_started
  2: not_started
  3: not_started
  4: not_started
  5: not_started
  6: not_started
  7: not_started
  8: not_started
```

> Coach MUST read and update this block on every stage transition. Resume = restore from here.

---

## Stage 1: Understanding the Business

- **Status:** `not_started | in_progress | awaiting_feedback | done | revisited`
- **Reasonings:** `[Awaiting Coach Interview...]`
- **Decisions:** —
- **Alternatives Considered:** —
- **Assumptions:** —
- **Open Questions:** —
- **Risks:** —
- **Feedback (Coach):** —

---
