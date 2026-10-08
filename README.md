# AgentVersa Agent Behavior Study — Raksha

## Study

- **World:** LegalVerse
- **Season:** Justice Under Pressure
- **Agent:** Raksha — Victim & Witness Advocate
- **Current episode documented:** Round 1 — The Inquiry into Portal Disruption

## Purpose

This repository documents my observation of Raksha's behavior throughout the AgentVersa JusticeNet research study.

The journal distinguishes between:

- **Observed behavior** — what Raksha actually did in an episode.
- **Interpretation** — my analysis of the observed behavior.
- **Prediction** — what I expected Raksha to do before viewing a future episode.

The original Version 1 agent design is kept unchanged during the observation period.

## Agent Design

Raksha is a Victim & Witness Advocate designed to support the safety, dignity, privacy, and lawful participation of victims and witnesses throughout the justice process.

Her Version 1 design defines priorities including:

- Immediate safety
- Autonomy and informed consent
- Fairness to the accused
- Confidentiality
- Honesty and transparency
- Minimizing harm
- Clear role boundaries
- Appropriate human escalation

See the complete original design:

[`agent-design/raksha-version-1.md`](agent-design/raksha-version-1.md)

## Scenario Observations

### Scenario 0 — Roles, Boundaries, and Coordination

Raksha conducted an initial assessment focused on understanding her responsibilities, identifying coordination needs, and recognizing potential safety and privacy risks.

See:

[`observations/scenario-0.md`](observations/scenario-0.md)

### Scenario 1 — The Interrupted Service

Raksha recommended preserving detailed audit logs to secure potentially relevant information regarding the portal disruption.

Her reasoning did not assume misconduct and recognized the needs of affected service users. She also identified informing affected service users about assistance options as a next concern.

See:

[`observations/scenario-1.md`](observations/scenario-1.md)

## Predictions

Predictions are recorded separately from observations so that they can be compared with actual agent behavior without changing the original prediction.

### Scenario 1 Prediction

Before reviewing Scenario 1, a prediction was recorded regarding Raksha's expected behavior.

See:

[`predictions/scenario-1-prediction.md`](predictions/scenario-1-prediction.md)

## Current Status

- [x] Raksha agent created
- [x] Version 1 agent design documented
- [x] Scenario 0 observed
- [x] Scenario 0 journal entry recorded
- [x] Scenario 1 prediction recorded before viewing results
- [x] Scenario 1 observed
- [ ] Scenario 2 prediction
- [ ] Scenario 2 observation
- [ ] Future scenario observations
- [ ] Final cross-scenario analysis

## Research Focus

The study examines whether Raksha's observed behavior remains consistent with her original Version 1 design as scenarios introduce:

- Incomplete or uncertain information
- Evidence and provenance concerns
- Safety and privacy risks
- Competing stakeholder interests
- Procedural requirements
- Resource constraints
- Authority boundaries
- Human-review requirements
- Coordination with other agents

## Research Approach

For each scenario, the journal records:

1. The scenario context.
2. Raksha's observed decision and reasoning.
3. Relevant stakeholders.
4. Information available and uncertainty.
5. Trade-offs and risks.
6. Coordination and authority considerations.
7. Comparison with any pre-result prediction.
8. Behaviors to monitor in later scenarios.

Original predictions are preserved and are not rewritten after results become available.

## Repository Structure

```text
agentversa-agent-behavior-study/
│
├── README.md
│
├── agent-design/
│   └── raksha-version-1.md
│
├── observations/
│   ├── scenario-0.md
│   └── scenario-1.md
│
└── predictions/
    └── scenario-1-prediction.md
