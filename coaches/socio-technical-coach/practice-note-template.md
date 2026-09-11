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

- **Scenario:** [Coach-generated business situation — 1-3 sentences]
- **Goal:** [What the business is trying to accomplish / North Star]
- **Known Constraints:** [Engineering, regulatory, time-to-market, headcount, etc.]

---

## 🔄 Analysis State — State Machine (for pause/resume)

```yaml
current_stage: 1
stages_status: # not_started | in_progress | done | revisited
  1: in_progress
  2: not_started
  3: not_started
  4: not_started
  5: not_started
  6: not_started
  7: not_started
  8: not_started
next_focus: 1 # [1, 2, 3, or 4 based on the current active stage's key questions]
active_cross_cutting_concern: null # e.g., consistency, cognitive load, compliance
blocked_by: null # e.g., awaiting research on X
```

> Coach MUST read and update this block on every stage transition. Resume = restore from here.

---

## Stage 1: Understanding the Business

- **Reasonings:** —
- **Decisions:** —
- **Alternatives Considered:** —
- **Assumptions:** —
- **Open Questions:** —
- **Risks:** —
- **Resolved Blockers & Learnings:** —
- **Feedback (Coach):** —

---

## Reflection

- **What we did:** —
- **What we learned:** —
- **Where struggled:** —
- **Where did well:** —
- **Where could be different:** —
- **Recommendations for future study** —

---

<!-- CONTINUUM STATE MACHINE (DO NOT EDIT MANUALLY — coach manages Analysis State above) -->
