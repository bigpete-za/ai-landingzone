# Contributing

The goal is a useful, low-friction library for non-developer knowledge workers. Prefer a small number of tested, high-value items over a large collection of generic prompt filler.

## Before adding content

1. Search the repository and linked galleries for duplicates.
2. Define the task and the user who benefits.
3. Check that the example is safe to publish and contains no real personal, customer, employee, confidential or proprietary information.
4. Prefer original wording. Link to third-party material rather than copying it wholesale unless its licence clearly permits reuse and attribution requirements are met.
5. Test the prompt in at least one target AI product. Record the product and review date where behaviour is product-specific.

## Prompt asset format

Use `resources/templates/prompt-template.md`. Each asset should identify:

- **Purpose** — task and expected benefit.
- **Best for** — likely audience and when to use it.
- **Inputs** — required sources and placeholders.
- **Prompt** — copy-ready instruction.
- **Follow-ups** — useful second-turn refinements.
- **Verification** — what a human must check.
- **Data considerations** — what must not be supplied or what tool is required.
- **Metadata** — owner, status, last reviewed, applicable tools and risk level.

## Skill asset format

Use `resources/templates/skill-template.md`. A skill is a repeatable procedure, not just a long prompt. It should have a clear trigger, prerequisites, steps, decision points, output format, quality checks and human approval points. Keep the `SKILL.md` portable and avoid assuming a platform-specific skill runtime.

## Content principles

- Use plain language and short, direct instructions.
- Use placeholders such as `[audience]`, `[source document]`, `[date range]`.
- Do not instruct a model to invent facts, citations, metrics, commitments or policy.
- Make the permitted source set explicit for factual or organisational work.
- Include a safe fallback: ask a question, state uncertainty or stop when required input is missing.
- Avoid requesting hidden chain-of-thought. Ask for a concise rationale, assumptions, evidence or checks instead.
- Separate draft generation from external actions such as sending, publishing, approving, deleting or purchasing.
- Do not claim that AI output is accurate, compliant or secure by default.

## Review checklist

- [ ] One clear job-to-be-done.
- [ ] Copy-ready and placeholders clearly marked.
- [ ] No sensitive example data or embedded secrets.
- [ ] Source and context boundaries are clear.
- [ ] Output format and audience are specified.
- [ ] Human verification and approval are stated.
- [ ] Tested with at least one current tool, or marked `untested`.
- [ ] Product/licensing caveats and source links are current.
- [ ] Owner and `last_reviewed` date recorded.

## Suggested commit style

Use concise messages, for example `docs: add meeting follow-up prompt` or `feat: add research brief skill`.
