# Curated Source Register

Last reviewed: 2026-11-01. These are starting points, not endorsements. Prefer official product documentation for feature, licensing, privacy and security questions. Browse community repositories for ideas, then adapt and test locally.

## 1. Prompt and skill libraries — primary inspiration

| Source | What it is useful for | How this repo should use it |
|---|---|---|
| [PnP Copilot Prompt Gallery repository](https://github.com/pnp/copilot-prompts) | Large community collection of Microsoft Copilot prompts, agent instructions and `SKILL.md` samples; documented sample structure and skill schema | The repository README currently reports 120 prompt samples, 31 agent instructions and 10 skills (counts will change). Browse for relevant business scenarios; link to canonical items; adopt the sample/skill metadata discipline. Do not bulk-copy. |
| [PnP Copilot Prompt Gallery website](https://pnp.github.io/copilot-prompts/) | Searchable and filterable gallery, with previews, metadata, setup and source/download links | Discover examples by product, task and audience. |
| [PnP Skill Schema](https://github.com/pnp/copilot-prompts/blob/main/SKILL-SCHEMA.md) | Describes the gallery's skill sample conventions | Use as a reference when adding Copilot-compatible skills; keep our base skill content portable. |
| [Liatrio Labs AI Prompts](https://github.com/liatrio-labs/ai-prompts) | Curated prompt and skill library with task-oriented folders and prompt-to-skill migration examples | Borrow the small, focused file approach and the distinction between a one-shot prompt and a repeatable skill. Its examples are mainly software-development oriented. |
| [Formal Verification Mode — prompts.chat](https://prompts.chat/prompts/cmois3iex0001ky0448nsw0aw_formal-verification-mode) | A prompt framework for explicit assumptions, consistency checks, conclusion classification and limitations | Adapted as [Formal Verification Mode](../02-prompt-patterns/formal-verification-mode.md), credited to Prompts Chat. This version adds evidence provenance, proportional output and an explicit warning that AI self-review is not independent verification. Check the source's applicable licence before further redistribution. |

## 2. Microsoft Copilot prompting and adoption

| Source | What it is useful for |
|---|---|
| [Get started writing prompts in Microsoft Copilot](https://support.microsoft.com/en-us/microsoft-365-copilot/get-started-writing-prompts-in-microsoft-365-copilot) | Prompt basics; Goal, Context, Source and Expectations; product-wide examples. |
| [Write a great prompt in Microsoft 365 Copilot](https://support.microsoft.com/en-us/microsoft-365-copilot/write-a-great-prompt-in-microsoft-365-copilot) | Practical prompt ingredients and iterative follow-ups. |
| [Microsoft Copilot Prompts](https://m365.cloud.microsoft/copilot-prompts) | Current prompt examples across Word, Excel, PowerPoint, Outlook and other Copilot experiences; availability varies. |
| [Microsoft Adoption Prompt Gallery](https://adoption.microsoft.com/en-us/copilot/prompt-gallery/) | Prompts filtered by task, product and function. |
| [Microsoft 365 Copilot adoption guide](https://adoption.microsoft.com/en-us/copilot/essential-guide/) | Planning, implementation, adoption, management and improvement. |
| [Microsoft Copilot adoption hub](https://adoption.microsoft.com/en-us/Copilot/) | End-user, champion, leader and IT-admin enablement materials. |
| [Overview of Microsoft Copilot Chat](https://learn.microsoft.com/en-us/copilot/overview) | Distinguishes Copilot Chat experiences and their grounding context. |
| [Microsoft 365 Copilot Chat requirements](https://learn.microsoft.com/en-us/microsoft-365/copilot/microsoft-365-copilot-chat-requirements) | Dependencies and service requirements; useful for admin readiness. |
| [Microsoft Copilot Chat considerations](https://learn.microsoft.com/en-us/microsoft-365/copilot/microsoft-365-copilot-chat-considerations) | Current product boundaries and ways to provide organisational context. |
| [Data, Privacy, and Security for Microsoft Copilot](https://learn.microsoft.com/en-us/deployoffice/privacy/microsoft-365-copilot) | Data handling, permissions, privacy and security commitments for Microsoft 365 commercial experiences. Check current scope and contract. |

## 3. Cross-platform prompting

| Source | What it is useful for |
|---|---|
| [OpenAI — Prompt engineering best practices for ChatGPT](https://help.openai.com/en/articles/10032626-prompt-engineering-best-practices-for-chatgpt) | Clear instructions, specificity and iterative refinement for everyday ChatGPT use. |
| [OpenAI — Best practices for prompt engineering](https://help.openai.com/en/articles/6654000-best-practices-for-prompt-engineering-with-the-openai-api) | Prompt structure, delimiters, context and output expectations; some examples are API-oriented. |
| [OpenAI API — Prompt engineering](https://developers.openai.com/api/docs/guides/prompt-engineering) | More detailed prompt design and evaluation concepts; adapt concepts to end-user chat rather than copying API mechanics. |
| [Anthropic — Prompt engineering overview](https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/overview) | Prompt iteration, testing and criteria-led improvement. |
| [Anthropic — Prompting best practices](https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/prompt-templates-and-variables) | Clear instructions, examples, structure, output formatting and tool-use considerations. |
| [Google AI — Prompt design strategies](https://ai.google.dev/gemini-api/docs/prompting-strategies) | Context, examples, structured prompts and iterative refinement. |

## 4. Responsible use, risk and security

| Source | What it is useful for |
|---|---|
| [NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework) | Voluntary risk-management framework for AI systems. Useful for governance discussions. |
| [NIST Generative AI Profile (AI 600-1)](https://www.nist.gov/publications/artificial-intelligence-risk-management-framework-generative-artificial-intelligence) | Risk considerations and actions tailored to generative AI. |
| [OWASP GenAI Security Project — LLM Top 10](https://genai.owasp.org/initiatives/top-10-for-llm-and-genai/) | Current awareness of prompt injection, sensitive-information disclosure, excessive agency and other LLM risks. The project is security-oriented, but its user-facing risks are relevant to safe adoption. |
| [UNESCO AI competency framework for students](https://www.unesco.org/en/articles/ai-competency-framework-students) | Human-centred mindset, AI ethics, AI techniques and critical judgement; an education framework that can inspire literacy outcomes, not a workplace standard. |
| [UNESCO AI competency framework for teachers](https://www.unesco.org/en/articles/ai-competency-framework-teachers) | Human agency, ethics, foundations and professional learning; useful as an additional literacy reference. |

## 5. Ongoing curation

When adding a source, record its purpose, publisher, last-checked date, intended audience, licence (for reusable content), and whether it is primary or secondary. Prefer canonical links. Keep a source when it materially improves learning, prompt quality, adoption or safe use; avoid link dumping.
