---
name: security-change-review
description: Review a proposed tenant, identity or security change against supplied authoritative standards and identify evidence gaps.
---

# Security Change Review

## Use when

A proposed configuration, tenant, identity or security change needs a structured review before implementation or approval.

## Required inputs

- Change description, scope and intended outcome.
- Current state and proposed state, including relevant configuration evidence.
- Applicable internal baseline, standard, architecture decision or official product guidance.
- Environment, dependencies, impact and rollback details, if known.

## Procedure

1. Restate the proposed change and the systems, users or controls in scope.
2. Identify which supplied standards and requirements apply. Note missing or conflicting references.
3. Compare current and proposed states against each applicable requirement.
4. Separate evidenced compliance, evidenced gaps, unknowns and requirements that do not apply.
5. Assess likely security impact, affected trust boundaries, privileges, exposure and dependencies.
6. Identify verification tests, monitoring and rollback checks needed before and after implementation.
7. Recommend proceed, proceed with conditions, or hold for further evidence. Explain the basis and uncertainty concisely.

## Output

- Change summary and scope
- Standards / requirements reviewed
- Findings table: requirement | evidence | status | impact | recommended action
- Unknowns and questions for the change owner
- Pre-change checks, post-change validation and rollback considerations
- Recommendation with confidence and limitations

## Failure behaviour

Do not invent internal policy or claim a change is compliant without evidence. If a baseline or configuration export is missing, say what cannot be assessed. Treat general Zero Trust principles as context, not a substitute for the organisation's actual requirements. Do not expose private chain-of-thought; provide concise rationale, evidence and checks.

## Human approval

The authorised security or service owner reviews findings and approves the change through the organisation's normal change-control process. This skill does not make or apply configuration changes.
