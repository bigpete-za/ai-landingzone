---
name: adversarial-plan-review
description: Stress-test a plan by generating distinct failure scenarios, assessing plausibility and proposing mitigations.
---

# Adversarial Plan Review

## Use when

A project, rollout, migration, policy or operational plan needs a structured challenge before a decision.

## Required inputs

- Plan or proposal and desired outcome.
- Constraints, dependencies, assumptions and acceptance criteria.
- Relevant environment, operational history or risk criteria, if available.
- Scope of review and acceptable level of detail.

## Procedure

1. Summarise the plan, objective and critical assumptions.
2. Generate distinct failure scenarios across relevant areas such as people, process, technology, dependencies, timing, security and adoption.
3. For each scenario, explain the trigger, plausible path to failure, observable warning signs and likely consequence.
4. Assess likelihood and impact using an explicitly stated scale. Mark assessments as estimates when evidence is limited.
5. Identify existing controls and their evidence; do not assume a control works merely because it is mentioned.
6. Propose proportionate mitigations, owners or decisions needed, and tests that would reduce uncertainty.
7. Prioritise the few scenarios that most affect the decision and state what evidence would change the assessment.

## Output

- Critical assumptions
- Prioritised scenario table: scenario | trigger | likelihood | impact | warning sign | existing control | mitigation
- Missing information and decision questions
- Recommended pre-mortem actions
- Short overall assessment with rationale and uncertainty

## Failure behaviour

Avoid repeating the same scenario in different wording or inventing evidence about the environment. Do not present speculative likelihood scores as measured probabilities. Provide a concise explanation of conclusions, not private chain-of-thought. A second AI review is not independent assurance.

## Human approval

The plan owner and relevant subject-matter experts decide which risks to accept, mitigate or escalate.
