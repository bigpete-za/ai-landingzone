---
name: script-explainer
description: Explain an existing script using supplied code and approved technical references without rewriting or executing it.
---

# Script Explainer

## Use when

An administrator needs to understand an existing script, its dependencies, authentication model and potential impact before running or maintaining it.

## Required inputs

- Complete script or the relevant files, including referenced modules where possible.
- Approved repository documentation, runbooks, infrastructure diagrams or product references.
- Intended execution context, if known: host, identity, permissions, schedule and target environment.
- Any known output, logs or error messages.

## Procedure

1. Identify the language, entry point, major functions, imports and external dependencies.
2. Trace the script's flow in execution order, including conditions, loops, error handling and side effects.
3. Identify files, services, APIs, tenants, systems or data it reads and changes.
4. Explain authentication and privilege requirements only where supported by the code or supplied references. Distinguish observed behaviour from inferred intent.
5. Highlight destructive or broad-impact operations, external destinations, credential handling, privilege elevation and security-sensitive assumptions.
6. Map key claims to code locations and supplied references.
7. List unknown variables, environment-specific values, dynamic calls and dependencies that prevent a confident assessment.
8. Suggest safe inspection or test steps, without modifying the script.

## Output

- Plain-language purpose and execution summary
- Function / component breakdown
- Inputs, outputs and dependencies
- Authentication and permission requirements
- Potential blast radius and side effects
- Evidence table: claim | code location / reference | confidence
- Unknowns, risks and questions to resolve before execution

## Failure behaviour

Do not rewrite, execute or silently fix the script. Do not guess what an unresolved variable, endpoint or dynamic command does. Flag it as unknown and explain what evidence is needed. Treat comments as claims to verify against actual code. Avoid reproducing secrets found in the source.

## Human approval

The responsible administrator validates the explanation against the environment and reviews the script in a safe test context before execution. This skill is explanatory, not a security certification.
