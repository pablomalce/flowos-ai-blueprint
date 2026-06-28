# FlowOS Project Constitution

## 1. Purpose of this document

This document defines the immutable principles, constraints, and decision-making framework for FlowOS.

It overrides all future ambiguity in strategy, architecture, product design, and implementation.

If any future decision conflicts with this constitution, this document prevails.

---

## 2. Company Definition

FlowOS is an AI-native enterprise platform for automating complex business workflows.

It is NOT a single-product SaaS.

It is a multi-product platform where each product is a vertical layer built on shared infrastructure.

Initial product:
- TenderFlow

Future products:
- GrantFlow
- LegalFlow
- ContractFlow
- VendorFlow
- ComplianceFlow
- KnowledgeFlow

---

## 3. Core Principles

### 3.1 Platform First
All decisions must prioritize platform scalability over single-product optimization.

### 3.2 AI First
AI is not a feature. It is the core execution layer of the system.

### 3.3 Multi-Tenant by Design
The system must support multiple organizations from day one.

### 3.4 Enterprise Ready
The system must assume enterprise constraints:
- security
- auditability
- compliance
- reliability
- observability

### 3.5 Event Driven Architecture
All core workflows must be event-driven and asynchronously scalable.

---

## 4. Decision-Making Rules

Every major decision must include:

- Why this decision is made
- Alternatives considered
- Trade-offs
- Risks
- Long-term impact on platform scalability

No decision is valid if it only optimizes for short-term implementation speed.

---

## 5. Definition of “Done”

A feature is NOT done unless it satisfies:

- scalable architecture
- observable behavior
- test coverage
- multi-tenant compatibility
- extensibility for future products

---

## 6. AI System Principles

The AI layer must support:

- multi-agent orchestration
- RAG-based knowledge retrieval
- memory (short + long term)
- tool/function calling
- evaluation and feedback loops
- cost optimization per task
- safety and governance controls

AI outputs are treated as system-critical components, not auxiliary features.

---

## 7. Prohibited Actions

The following are NOT allowed:

- Designing systems only for MVP simplicity
- Hardcoding logic that should be abstracted into platform services
- Building single-product-specific infrastructure without reuse potential
- Ignoring multi-tenant requirements
- Skipping architectural documentation

---

## 8. Claude Code Restrictions

Claude Code must NEVER:

- redefine business strategy
- modify architecture without approval
- implement features not defined in TASKS_FOR_CLAUDE_CODE.md
- bypass review gates
- assume missing requirements

Claude Code is an execution engine only.

---

## 9. Quality Standard

All documentation and decisions must be:

- investment-grade quality
- VC-ready (Sequoia / a16z standard)
- structurally consistent across phases
- suitable for enterprise stakeholders

---

## 10. Success Definition

FlowOS is successful if:

- it becomes a category-defining enterprise AI platform
- it supports multiple independent product lines
- it scales to thousands of enterprise customers
- it enables rapid creation of new AI workflows with minimal engineering effort

---

## 11. Governance Hierarchy

Order of authority:

1. Project Constitution (highest authority)
2. Master Context
3. Phase Documents
4. Implementation Tasks

---

## 12. Final Rule

If there is uncertainty:

Default to long-term platform scalability over short-term implementation simplicity.
