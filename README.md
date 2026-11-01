# AI Landing Zone

A practical, vendor-neutral starting point for everyday AI use at work, with an additional Microsoft 365 Copilot guide. The intended audience is the knowledge worker in a typical small or medium-sized organisation: people who write, meet, research, analyse information, plan work and communicate with customers or colleagues.

This is a **working library**, not a course in machine learning and not a developer prompt collection. It brings together short learning notes, reusable prompts, repeatable workflows (`SKILL.md`), and carefully selected external references.

## Start here

1. Read [AI mindset](01-foundations/ai-mindset.md) and [safe use](01-foundations/safe-use.md).
2. Use the [prompt planning checklist](01-foundations/planning.md) and the [prompt patterns](02-prompt-patterns/README.md).
3. Browse [use cases](03-use-cases/README.md) and copy a prompt that matches a real task.
4. Use [Which Copilot tool when?](04-copilot-guides/which-tool-when.md) when working in Microsoft 365.
5. Explore [skills and workflows](05-skills-and-workflows/README.md) for repeatable, multi-step work.

## Repository map

| Area | What belongs here |
|---|---|
| [01 Foundations](01-foundations/README.md) | AI mindset, planning, context and memory, verification, safe use |
| [02 Prompt Patterns](02-prompt-patterns/README.md) | Planner, Analyst, Summarizer, Critic, Coach |
| [03 Use Cases](03-use-cases/README.md) | Email, meetings, research, reporting, presentations, plus adjacent office work |
| [04 Copilot Guides](04-copilot-guides/README.md) | M365 Copilot tool selection, grounding, app-oriented guidance and limitations |
| [05 Skills and Workflows](05-skills-and-workflows/README.md) | Portable `SKILL.md` playbooks for repeatable tasks |
| [06 Reference](06-reference/README.md) | Glossary, checklists, evaluation, adoption playbook |
| [07 Ecosystem](07-ecosystem/overview.md) | Curated GitHub repositories for Cowork, prompts, skills, learning, plugins and AI workflows |
| [resources](resources/README.md) | External sources, attribution, and contributor templates |

## Guiding principles

- **Start with work, not with AI.** Identify a real task, its inputs, its owner and its desired result.
- **Augment judgement; do not outsource accountability.** A person remains responsible for decisions and anything sent, published, approved or acted upon.
- **Use approved tools and data.** Tool choice, data sensitivity, tenant controls and organisational policy matter more than clever prompt wording.
- **Ground important work.** Supply or point to approved source material; ask for citations, evidence and explicit gaps.
- **Iterate.** Treat the first answer as a draft. Review, correct, refine and verify.
- **Prefer repeatable workflows.** A prompt is a starting instruction; a skill adds steps, checks, inputs and a defined output.
- **Keep examples generic.** Replace placeholders with approved information. Do not paste real personal, customer, employee, financial or confidential data into unapproved AI services.

## How to use this library

- Copy a prompt and replace every `[placeholder]`.
- Give the model the source material it is allowed to use. State when it must not use outside knowledge.
- Ask for assumptions, unknowns and missing inputs instead of letting the model fill gaps.
- Review outputs against the source and the intended audience before using them.
- Adapt prompts to your AI product. Features, connectors, context windows, privacy commitments and licensing differ.

## Suggested adoption path

1. Establish an approved-tool list, data rules and a route for questions or incidents.
2. Run a small pilot with a few common, low-risk tasks (email drafting, meeting follow-up, first drafts, summaries).
3. Collect useful prompts and repeatable workflows with an owner and review date.
4. Measure quality and rework as well as time saved; retire prompts that do not help.
5. Expand into higher-impact workflows only after controls, permissions and human review are understood.

See [the adoption playbook](06-reference/adoption-playbook.md) and [use-case discovery worksheet](06-reference/use-case-discovery.md).

## Content status

This repository is an evolving collection. Treat prompts as examples, not guarantees. Each contribution should state its purpose, prerequisites, data considerations, expected output and verification steps. Product-specific guidance must link to an official source and include a review date.

## Sources and inspiration

The structure is informed by the [Microsoft 365 & Power Platform Community Copilot Prompt Gallery](https://github.com/pnp/copilot-prompts) and [Liatrio Labs AI Prompts](https://github.com/liatrio-labs/ai-prompts). This repository adapts the idea of a browsable prompt/skill library for general business knowledge work; it does not mirror their developer-first scope. See [Sources](resources/SOURCES.md) and [licensing and attribution](resources/licensing-and-attribution.md).

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). Keep each prompt focused, tool-aware but not tool-dependent where possible, safe to share, and easy to test.

## Disclaimer

This material is educational and provided as-is. It is not legal, compliance, HR, financial, medical or security advice. Follow your organisation's policies, contractual obligations and applicable laws. Confirm current product behaviour and terms in vendor documentation.
