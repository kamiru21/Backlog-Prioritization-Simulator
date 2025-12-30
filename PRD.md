# Product Requirements Document (PRD)
## Backlog Prioritization Simulator (RICE vs MoSCoW)

---

## 1. Problem Statement

Product teams frequently struggle with backlog prioritization due to:
- Conflicting stakeholder opinions
- Lack of transparency in decision-making
- Over-reliance on a single prioritization framework

Different prioritization frameworks (e.g. RICE, MoSCoW) often produce very different outcomes, yet teams rarely compare them side-by-side.

As a result:
- Teams argue *what* to build instead of *why*
- Leadership decisions feel arbitrary
- Agile ceremonies become performative rather than outcome-driven

---

## 2. Product Goal

Provide a simple, transparent simulator that:
- Applies **RICE** and **MoSCoW** to the same backlog
- Visualizes how priorities change across frameworks
- Surfaces insights to support better product and stakeholder conversations

---

## 3. Target Users

### Primary Users
- Product Managers
- Agile Coaches
- Scrum Masters
- Delivery Leads

### Secondary Users
- Engineering Managers
- Business Stakeholders involved in prioritization decisions

---

## 4. Use Cases

1. Compare prioritization outcomes across different frameworks
2. Facilitate backlog refinement or prioritization workshops
3. Coach teams on trade-offs and prioritization biases
4. Explain prioritization decisions clearly to leadership

---

## 5. In Scope (v1)

### 5.1 Backlog Input

Users can:
- Upload a CSV file, or
- Edit backlog items directly in a table UI

**Backlog Fields**
- Feature name
- Description
- Reach (numeric)
- Impact (numeric, normalized scale)
- Confidence (percentage)
- Effort
- MoSCoW category (Must / Should / Could / Won’t)

---

### 5.2 RICE Prioritization

The system calculates RICE scores using the formula:

