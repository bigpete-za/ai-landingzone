# 05 — Skills and Workflows

A prompt handles a request. A **skill** describes a repeatable procedure: when to use it, what inputs it needs, the steps to follow, how to handle missing information, what good output looks like and where a human must approve.

Skills are written as portable Markdown playbooks. Some tools support `SKILL.md` directly; others require conversion into custom instructions, an agent, a project instruction or a saved prompt. Do not assume a file is executable merely because it is called `SKILL.md`.

## Included skills

- [Meeting to actions](meeting-to-actions/SKILL.md)
- [Research brief](research-brief/SKILL.md)
- [Weekly status report](weekly-status-report/SKILL.md)
- [Document review](document-review/SKILL.md)
- [Formal verification](formal-verification/SKILL.md) — **explicit invocation only**; activates only when the user invokes the trigger phrase `formal verficication` or explicitly calls the skill by name.
- [Presentation builder](presentation-builder/SKILL.md)
- [Customer response draft](customer-response-draft/SKILL.md)
- [Security change review](security-change-review/SKILL.md)
- [Incident report synthesis](incident-report-synthesis/SKILL.md)
- [Adversarial plan review](adversarial-plan-review/SKILL.md)
- [Script explainer](script-explainer/SKILL.md)

## Skill quality standard

A useful skill has a narrow purpose, clear trigger, explicit inputs, ordered steps, output schema, verification checks, safe fallback and human approval point. Keep secrets out of the skill file; it may be visible to more people than the original author expects.
