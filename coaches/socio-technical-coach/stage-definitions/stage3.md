# Stage 3: Model Work & Flow

## 🎯 Purpose

Trace the end-to-end chronological flow of operations, business rules, decisions, and domain events required to realize the capabilities.

## 🛠️ Techniques (Scope Reference)

- Process-Level Event Storming & Event Modeling
- Command/Event Sequence Mapping & Operational Timeline Tracing
- State Machine Specification (Tracking State Mutations)

## ❓ Core Conversational Targets (Milestones)

_Translate these abstract systemic archetypes dynamically into the specific narrative of the active business context:_

- **Milestone 1 (The Trigger, Command & Decision Ownership Target):** The entry point command that kicks off the workflow, identifying exactly _who_ initiates it, _what_ information is required, and _which_ specific business rule governs the decision.
- **Milestone 2 (The Happy Path Event Timeline Target):** The linear, step-by-step chronology of meaningful Domain Events required to successfully push value through the system under optimal conditions.
- **Milestone 3 (The Consistency & Asynchronous Reality Target):** Identifying steps that require absolute **immediate consistency** versus operations that can tolerate **eventual consistency** or asynchronous processing (e.g., separating real-time ledger writes from delayed gateway transfers).
- **Milestone 4 (The Exceptional/Failure & Notification Target):** The explicit modeling of downstream failures, timeouts, or rejections—including exactly _what_ compensating actions occur and _who_ needs to be notified when things break.

## 🚫 Common Pitfalls (Calibration Triggers)

- **Technical Piping (The API/Screen Illusion)** ──> Modeling the timeline using software components, UI screens, or technical API endpoints instead of meaningful business events (e.g., tracking `POST /payment` instead of `Settlement Initiated`).
- **The Synchronous Illusion** ──> Assuming every step in the timeline happens instantly or demanding immediate data consistency across the entire workflow, completely ignoring network and batch system realities.
- **Happy-Path Blindness** ──> Ignoring negative paths, edge cases, or external gateway rejections, leaving the business state corrupted and actors unnotified when a transaction fails.
