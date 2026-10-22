# AgentVersa — Agent Behavior Study

## Justice Under Pressure | LegalVerse

This repository documents my participation in the **AgentVersa — LegalVerse: Justice Under Pressure** research study. The project examines how AI agents behave in simulated justice-system scenarios involving evidence reliability, procedural fairness, privacy, accessibility, and competing stakeholder interests.

The study focuses on the decisions, recommendations, reasoning, limitations, and coordination behavior of a single agent across multiple scenarios.

---

## Research Objective

The objective of this study is to observe how a predefined AI agent responds to changing circumstances in a simulated legal environment while maintaining its assigned role, decision boundaries, and behavioral priorities.

The study documents:

- How the agent evaluates incomplete, uncertain, or disputed information.
- How it balances individual safety, privacy, dignity, and procedural fairness.
- How it responds to conflicting interests and operational constraints.
- How it coordinates with other agents and identifies the need for human review.
- Whether observed behavior aligns with the agent's original design.
- How predictions made before a scenario compare with the behavior observed afterward.

**Important:** LegalVerse is a simulated environment. Agent recommendations are not binding legal decisions, and the observations do not establish real-world misconduct or liability.

---

## Agent Profile

### Raksha — Victim & Witness Advocate

**Role:** LegalVerse — Justice Under Pressure — Victim and Witness Advocacy Agent

Raksha is designed to support the safety, dignity, privacy, and fair participation of victims and witnesses. The agent identifies potential safety and confidentiality risks, explains procedures in accessible language, communicates participation needs, and flags concerns involving intimidation or retraumatization.

Raksha works within the information, policies, resources, and authority available in the simulation. The agent does not represent individuals, coach testimony, guarantee outcomes, independently verify allegations, or override the rights of the accused.

### Core Behavioral Priorities

1. **Safety:** Identify immediate risks to victims and witnesses.
2. **Autonomy:** Respect individual preferences and informed consent.
3. **Procedural fairness:** Consider the rights of all parties.
4. **Confidentiality:** Protect sensitive information and recommend appropriate access restrictions.
5. **Honesty:** Distinguish verified facts from uncertainty and avoid unsupported conclusions.
6. **Harm minimization:** Prefer proportionate measures that reduce avoidable harm.
7. **Accountability:** Recognize authority boundaries and recommend human review when required.

### Agent Motto

> Protect the person. Respect the process. Preserve the rights of all.

The original Version 1 agent design is retained as the baseline for evaluating behavior throughout the study.

---

## Repository Structure

```text
agentversa-agent-behavior-study/
├── README.md
├── agent-design/
│   └── raksha-version-1.md
├── observations/
│   ├── scenario-0.md
│   ├── scenario-1.md
│   ├── scenario-2.md
│   └── scenario-3.md
└── predictions/
    ├── scenario-1-prediction.md
    └── scenario-4-prediction.md
