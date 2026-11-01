# Ways of Working with AI

There is more to working effectively with AI than asking a question and accepting the first answer. You can improve results by providing examples, narrowing the source material, splitting work into stages, challenging assumptions, checking against a rubric, or combining AI with ordinary automation.

This guide introduces reusable approaches. The detailed examples remain in the relevant [use-case collections](README.md); repeatable procedures live in [Skills and Workflows](../05-skills-and-workflows/README.md).

## Explore the approaches

| Approach | What it helps you do | Example |
|---|---|---|
| **Give examples, not just instructions** | Show the format, tone or quality expected | Turn incident evidence into a consistent post-incident report using approved examples |
| **Work in stages** | Separate extraction, analysis and presentation | Turn a meeting transcript into decisions, blockers and an action plan |
| **Ground work in trusted sources** | Compare a proposal with authoritative material | Review a proposed tenant or security change against supplied standards |
| **Challenge a plan** | Explore failure scenarios, assumptions and mitigations | Red-team a deployment plan before seeking approval |
| **Review against a rubric** | Evaluate against explicit criteria rather than vague instructions | Check a draft against a service-quality or communications rubric |
| **Critique, then revise** | Improve a draft through a separate review pass | Refine a difficult client response against empathy, firmness and commitment boundaries |
| **Combine automation with AI** | Use ordinary tools for structured processing and AI for interpretation | Analyse validated telemetry for anomalies worth investigating |
| **Bound the context** | Supply relevant material and explicit limits instead of inviting guesses | Explain a script using approved repository and infrastructure documentation |
| **Synthesize across sources** | Turn relevant task, email and meeting information into a focused brief | Prepare a daily priority list and meeting agendas from approved connected sources |

## Reusable skills

These procedures can be adapted to different approved AI tools. A skill describes a process; it does not automatically grant access to organisational data or perform actions.

- [Security change review](../05-skills-and-workflows/security-change-review/SKILL.md) — assess a proposed change against supplied standards and identify evidence gaps.
- [Incident report synthesis](../05-skills-and-workflows/incident-report-synthesis/SKILL.md) — turn incident evidence into a consistent, traceable report.
- [Adversarial plan review](../05-skills-and-workflows/adversarial-plan-review/SKILL.md) — generate distinct failure scenarios and practical mitigations.
- [Script explainer](../05-skills-and-workflows/script-explainer/SKILL.md) — explain behaviour, dependencies, authentication and potential impact without rewriting the script.

## Practical examples by task

- **Meetings:** use separate passes to extract decisions and actions, then format and verify the output.
- **Reporting:** use approved examples to guide structure, but derive facts only from the incident evidence.
- **Documents:** evaluate against a supplied rubric and require evidence for each material finding.
- **Email:** ask for a critique against explicit tone, service-level and commitment constraints before revising.
- **Data:** use automation for repeatable extraction and validation, then AI to interpret patterns and suggest what to investigate.
- **Planning:** synthesize task and meeting sources into a proposed daily plan, with source references and unresolved conflicts.

See the linked topic pages for copy-ready prompts. For product-specific capabilities, integrations and permissions, use the relevant tool guidance rather than assuming a prompt alone can access connected data.

## Rules of thumb

- Give examples when format and consistency matter; examples guide style, not factual truth.
- Break complex work into stages when extraction, analysis and drafting need different checks.
- Name authoritative sources when accuracy depends on organisational context.
- Ask for evidence, assumptions, uncertainty and alternatives—not just a confident answer.
- Use ordinary tools for deterministic operations and calculations where practical; validate outputs and handle failures.
- A self-review can improve a draft, but it is not independent verification.
- Keep human approval for consequential decisions and actions.

**The aim is not to use the most elaborate technique.** Choose the approach that makes the result more useful, repeatable and verifiable.
