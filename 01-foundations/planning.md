# Planning an AI Task

## The four-part prompt frame

A useful default is **Goal · Context · Source · Expectations**. This reflects Microsoft's practical Copilot prompt guidance and works across most conversational AI tools.

| Part | What to specify | Example |
|---|---|---|
| Goal | The task and outcome | Draft a customer update |
| Context | Why, audience, situation, constraints | Project is delayed by one week; customer needs a clear, calm update |
| Source | Material to use | Use only the project notes pasted below |
| Expectations | Format, length, tone, criteria | 150 words, plain language, include impact and next update date |

## Before prompting

- What decision or task am I trying to move forward?
- What would a useful output look like?
- Who will read or use it?
- What information does the model need, and what is the authoritative source?
- What must it not assume or do?
- How important is correctness, freshness and confidentiality?
- What will I check before using the output?

## Copy-ready task brief

```text
Goal: [What do I need done?]
Context: [Audience, purpose, background and constraints]
Source: [Approved files, notes, data or links to use]
Expectations: [Format, tone, length, detail and success criteria]
Boundaries: [What not to assume, disclose, decide or do]
If information is missing: [Ask me / mark it unknown / provide options]
```

## Complex tasks: plan, then produce

For work that has several dependent steps, ask for a short plan first. Confirm the scope and missing inputs before asking for the final deliverable. Example:

> Break this task into logical stages. For each stage, list the input required, the intended output and a check that would show it is complete. Identify decisions I need to make before proceeding. Do not start the final deliverable until the plan and open questions are clear.

## Improve a weak first answer

Avoid repeating the whole prompt. Give targeted feedback: what is wrong, what is missing, which source to prioritise, or how to change the format. Ask the model to list assumptions and questions before revising when the gap is unclear.
