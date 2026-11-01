---
name: incident-report-synthesis
description: Synthesize supplied incident evidence into a consistent post-incident report with traceable claims and explicit uncertainty.
---

# Incident Report Synthesis

## Use when

An incident owner needs to turn approved notes, timelines, alerts, tickets and follow-up records into a post-incident report (PIR).

## Required inputs

- Incident timeline and evidence, with timestamps and time zones where available.
- Impact, scope, detection, response and recovery information.
- Approved report template or a small set of prior reports used as formatting examples.
- Intended audience and any handling or redaction requirements.

## Procedure

1. Confirm the incident identifier, reporting period, audience and permitted sources.
2. Extract events, impact statements, actions, decisions and unresolved questions with source references.
3. Build a chronological timeline; preserve time zones and mark conflicting timestamps.
4. Use the approved template or prior examples to match structure and level of detail. Treat examples as formatting guidance, not as evidence about this incident.
5. Draft the report using only supplied evidence. Distinguish confirmed facts, hypotheses, contributing factors and unknowns.
6. Check that each material claim can be traced to a source and that causal conclusions are supported.
7. Identify missing evidence, contradictions, sensitive details and actions without an owner or due date.
8. Produce a draft for the incident owner to validate.

## Output

- Executive summary
- Incident scope and impact
- Detection and response timeline with source references
- Confirmed cause and contributing factors, or explicit unknowns
- What worked / what did not
- Corrective actions: action | owner | due date | evidence of completion
- Open questions and evidence gaps

## Failure behaviour

Do not invent root cause, impact, timestamps, owners or lessons learned. If evidence conflicts, report the conflict instead of silently reconciling it. Redact secrets and unnecessary personal data. Similar prior incidents do not prove the same cause occurred here.

## Human approval

The incident owner and relevant technical or business stakeholders verify the report before it is circulated. Any security, privacy or contractual notification decision remains with the authorised owner.
