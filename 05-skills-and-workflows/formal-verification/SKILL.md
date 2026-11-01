---
name: formal-verification
description: Run a structured, evidence-focused verification review only when the user explicitly invokes the trigger phrase "formal verficication" or calls this skill by name. Do not activate automatically for ordinary requests about accuracy, critique, research, or verification.
---

# Formal Verification

## Activation gate — mandatory

**Do not execute this skill unless one of these conditions is met:**

1. The user uses the exact trigger phrase `formal verficication` as an instruction to activate this mode; or
2. The user explicitly calls this skill, for example `formal-verification`, `Formal Verification`, or `Formal Verification Mode`.

Treat the trigger as an activation command only when the user is invoking the mode—not when the phrase is merely quoted, discussed, or included in source material.

If neither condition is met, do not run this procedure. Handle the request normally, even if it would benefit from careful analysis, fact-checking, critique, or verification. Do not activate this skill based on topic or inferred intent alone.

## Purpose

Use a structured, traceable approach to assess a claim, answer, document, calculation, proposal, or decision. Distinguish evidence from assumptions, test consistency, classify the conclusion, and disclose what remains uncertain.

This skill is based on the repository's [Formal Verification Mode prompt](../../02-prompt-patterns/formal-verification-mode.md).

## Inputs

Use whatever the user provides. Identify material gaps rather than inventing missing information. When relevant, establish:

- The question, claim, document or decision to assess.
- The intended purpose and context.
- Available source material, data, calculations or constraints.
- Any required standard, policy, date range or acceptance criteria.

Ask a concise clarifying question only when the missing information prevents a useful assessment; otherwise proceed and label the gap.

## Procedure

1. **Analyse the input.** State the question or claim and identify what evidence is actually available.
2. **Declare assumptions.** Separate explicit information, reasonable inferences and unknowns. Do not present an inference as a fact.
3. **Assess evidence and logic.** Connect material conclusions to sources or premises. Check source quality, dates, context, calculations and logical links where possible. Give concise, auditable rationale rather than exhaustive internal deliberation.
4. **Check consistency.** Look for contradictions, missing steps, unsupported generalisations, counter-evidence and plausible alternative explanations.
5. **Classify the result.** Choose the best-fitting label:
   - **Proven:** follows from a valid proof or necessarily follows from established premises; do not use this for ordinary empirical claims merely because evidence is strong.
   - **Likely:** supported by available evidence, but not conclusively established.
   - **Uncertain:** evidence is insufficient, incomplete or materially conflicting.
   - **Invalid:** contradicted by reliable evidence or does not follow from the premises.
6. **Disclose limitations.** State what could not be checked, why it matters and what further evidence or independent check would help.
7. **Conclude proportionately.** Give a clear judgment and practical next steps. Use the full output format below for complex or consequential tasks; keep simple assessments concise without omitting material caveats.

## Output format

For substantial reviews, use:

- **[WHAT IS GIVEN]** — relevant claims, inputs and available evidence.
- **[WHAT WE ASSUME]** — explicit assumptions, inferences and unknowns.
- **[ASSESSMENT]** — concise explanation of the evidence and reasoning supporting or undermining the conclusion.
- **[CONSISTENCY CHECK]** — contradictions, counter-evidence and checks performed.
- **[FINAL JUDGMENT]** — conclusion and practical implications.
- **[CONFIDENCE LEVEL]** — Proven / Likely / Uncertain / Invalid, with a brief justification.
- **[WHAT IS UNCERTAIN OR MISSING]** — limitations and next verification steps.

Adapt the depth and structure to the task. Do not force a lengthy template onto a trivial request or fabricate content to fill a section.

## Verification rules

- Never invent sources, quotations, calculations, test results or checks.
- Distinguish checks actually performed from checks that remain to be done.
- Use primary or authoritative sources when external research is appropriate and available; cite sources where relevant.
- If sources conflict, describe the conflict rather than silently selecting the convenient one.
- Do not claim certainty beyond what the evidence supports.
- Follow applicable higher-priority instructions, safety requirements, privacy obligations and organisational policy.
- For consequential matters, recommend independent checking against primary records, authoritative sources or independently validated calculations. An AI reviewing its own output is not independent verification.

## Related repository material

- [Formal Verification Mode prompt](../../02-prompt-patterns/formal-verification-mode.md) — full prompt pattern and rationale.
- [Foundations: Verification](../../01-foundations/verification.md) — practical source checking and human approval.
- [Critic Pattern](../../02-prompt-patterns/critic.md) — ranked, actionable review of a draft.
- [Research use cases](../../03-use-cases/research/README.md) — evidence-backed research and claim testing.
- [Reporting use cases](../../03-use-cases/reporting/README.md) — checking metrics, assumptions and causal claims.
- [Document Review skill](../document-review/SKILL.md) — repeatable document-review procedure.
