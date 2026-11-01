# AI & Cowork Ecosystem Index

A curated directory of useful GitHub repositories for people exploring AI at work, Microsoft 365 Copilot Cowork, reusable prompts and skills, and agent-enabled workflows.

This is a **working reference index**, not a ranking or a list of endorsements. The descriptions below explain what each project is useful for and when to look at it. Most projects are external to this repository; browse and evaluate them before adopting anything.

> **Scope:** In this index, “Cowork” primarily refers to Microsoft 365 Copilot Cowork. The wider AI and agent resources are included where they offer transferable ideas or useful tools. A skill or agent definition is not automatically portable between products: check the target platform's format, permissions, connectors, licensing and policies.

## Start with these

| Need | Start here |
|---|---|
| Measure team adoption and reported time savings | [Microsoft CoworkDashboard](https://github.com/microsoft/CoworkDashboard) |
| Assess whether a workflow is a good fit for Cowork | [Copilot Cowork Investment Assessment](https://github.com/microsoft/cowork-investment-assessment) |
| Find practical M365 Copilot prompts and skills | [PnP Copilot Prompts](https://github.com/pnp/copilot-prompts) |
| Browse reusable skills across agent platforms | [Anthropic Skills](https://github.com/anthropics/skills) or [Awesome Agent Skills](https://github.com/VoltAgent/awesome-agent-skills) |
| Find task-oriented prompts usable in different AI tools | [Fabric](https://github.com/danielmiessler/Fabric) |

## 1. Cowork, workflow assessment and adoption

### [microsoft/CoworkDashboard](https://github.com/microsoft/CoworkDashboard)

A two-skill Microsoft Copilot Cowork sample: one skill lets team members review and submit de-identified summaries of their own Cowork activity; the other rolls up the submitted reports into a team dashboard.

**Use it when:** piloting Cowork with a team and looking for a practical way to collect opt-in productivity and adoption signals.

**Keep in mind:** the project README says this is not an official Microsoft Cowork skill. Review the privacy model and the current setup instructions with your organisation before using it. It reads reports submitted to the configured Teams channel, not team members' files directly.

### [microsoft/cowork-investment-assessment](https://github.com/microsoft/cowork-investment-assessment)

A toolkit that analyses Microsoft 365 work patterns to identify candidate workflows, classify their complexity, estimate Cowork credit consumption and ROI, and produce recommendations. It includes a reusable prompt, an Agent Builder approach and a pre-built agent path.

**Use it when:** deciding whether a process justifies agentic, cross-application orchestration and preparing an initial business case.

**Keep in mind:** treat estimates as planning inputs, not a financial or licensing quote. Validate assumptions, actual usage, pricing and permissions before making an investment decision.

## 2. Prompt, instruction and skill collections

### [pnp/copilot-prompts](https://github.com/pnp/copilot-prompts)

A community gallery of prompts, agent instructions and reusable skills for Microsoft 365 Copilot, Microsoft Copilot and GitHub Copilot.

**Use it when:** looking for ready-made examples for office work, Copilot scenarios, agents or skills; also useful as a model for how to document and contribute a prompt.

### [github/awesome-copilot](https://github.com/github/awesome-copilot)

GitHub's community collection of custom agents, instructions, skills, hooks, workflows and plugins, with a searchable gallery and learning hub.

**Use it when:** exploring how to customise GitHub Copilot or looking for structured examples of agents and skills. Much of the material is developer-oriented, so treat it as a source of patterns rather than a general office-worker prompt pack.

### [anthropics/skills](https://github.com/anthropics/skills)

Anthropic's public examples of Agent Skills: self-contained folders containing a **SKILL.md** plus optional scripts and supporting resources. Examples span documents, communications, creative tasks and technical workflows.

**Use it when:** learning how to turn a repeated task into a documented skill, or borrowing workflow ideas for document creation and knowledge work.

**Keep in mind:** it demonstrates Anthropic's implementation. Check compatibility and the licence of each skill; the repository notes that some document skills are source-available rather than open source.

### [VoltAgent/awesome-agent-skills](https://github.com/VoltAgent/awesome-agent-skills)

A large, community-maintained collection of Agent Skills from vendor teams and practitioners, intended for several agent environments including Claude Code, Codex, Gemini CLI, Cursor and GitHub Copilot.

**Use it when:** searching broadly for an existing skill before writing one from scratch, or comparing how different teams package repeatable tasks.

**Keep in mind:** a large directory is a discovery starting point, not a quality or security guarantee. Check the origin, maintenance, licence, dependencies and target-platform compatibility of each skill.

### [danielmiessler/Fabric](https://github.com/danielmiessler/Fabric)

An open-source framework and library of task-oriented AI prompts called **Patterns**. The patterns cover activities such as summarising, extracting insights, analysing content and transforming material for different audiences.

**Use it when:** you want reusable prompt patterns that can be adapted to ChatGPT, Copilot or another AI interface. You can browse the pattern files without adopting the command-line tool.

### [dair-ai/Prompt-Engineering-Guide](https://github.com/dair-ai/Prompt-Engineering-Guide)

A learning guide and reference collection covering prompt design, techniques, examples, papers, tools, retrieval-augmented generation and agents.

**Use it when:** moving beyond basic prompt templates and trying to understand why a prompting approach works, where it fails and which technique may suit a task.

## 3. Learning and building with AI

### [microsoft/generative-ai-for-beginners](https://github.com/microsoft/generative-ai-for-beginners)

Microsoft's multi-lesson course on generative AI concepts and building applications, with explanations and coding exercises.

**Use it when:** an interested learner or technical champion wants a structured introduction to how generative AI applications are built.

**Audience note:** this is primarily an app-builder/developer course, not a non-technical AI-at-work course.

### [microsoft/ai-agents-for-beginners](https://github.com/microsoft/ai-agents-for-beginners)

A course covering the concepts and implementation of AI agents, with lessons and examples for people learning to build agent-based solutions.

**Use it when:** an IT team, automation lead or technical champion needs to understand agent architecture, tool use and orchestration.

**Audience note:** more technical than the everyday knowledge-worker material in this landing zone.

### [microsoft/CopilotStudioSamples](https://github.com/microsoft/CopilotStudioSamples)

Samples and implementation artifacts for Microsoft Copilot Studio, including authoring examples, integrations, extensibility, infrastructure, SSO and testing.

**Use it when:** moving from personal Copilot use to building, testing or integrating a governed business agent with Copilot Studio or the Power Platform.

## 4. Plugins, integrations and technical utilities

### [openai/plugins](https://github.com/openai/plugins)

OpenAI's curated collection of Codex plugin examples. Plugins can bundle skills, MCP configuration, agents, hooks and other supporting resources; examples include planning, research, meetings and knowledge capture.

**Use it when:** exploring how Codex plugins package repeatable capabilities or building a more integrated developer/technical workflow.

**Audience note:** this is a Codex extension repository, not a general end-user prompt gallery.

### [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers)

Reference implementations for the Model Context Protocol (MCP), demonstrating ways to expose tools and data sources to AI applications.

**Use it when:** an IT or automation team needs to understand how an AI client can connect to systems through MCP.

**Keep in mind:** the repository explicitly describes these as educational reference implementations, not production-ready servers. For discovery, use the [MCP Registry](https://registry.modelcontextprotocol.io/) and apply your normal security and supplier review.

### [microsoft/markitdown](https://github.com/microsoft/markitdown)

A Python utility that converts documents and other file formats—including PDF, Word, PowerPoint and Excel—to Markdown for use in LLM and text-analysis workflows.

**Use it when:** preparing batches of documents for AI-assisted analysis or building a controlled document-ingestion process.

**Audience note:** useful to technical users and IT teams; it is a conversion utility, not a chat application or a high-fidelity document editor. Review its security considerations before processing untrusted files.

### [obra/superpowers](https://github.com/obra/superpowers)

A structured software-development methodology for coding agents, implemented through composable skills and workflows such as specification, planning, implementation and review.

**Use it when:** a software team wants disciplined, repeatable workflows for AI-assisted coding.

**Audience note:** included as a strong example of agent workflow design, but it is for software development rather than general business knowledge work.

## 5. Official product and standards references

GitHub projects are useful examples, but product behaviour and compatibility should be checked against primary documentation:

- [Microsoft Copilot Cowork overview](https://learn.microsoft.com/en-us/copilot/cowork) — capabilities, workflow model and skills.
- [Use Copilot Cowork](https://learn.microsoft.com/en-us/microsoft-365-copilot/cowork/use-cowork) — built-in and custom skills, including setup guidance.
- [Agent Skills standard](https://agentskills.io/) — format and concepts behind portable skill packages.
- [Model Context Protocol](https://modelcontextprotocol.io/) — protocol documentation and implementation guidance.

## How to evaluate a repository before using it

1. **Check purpose and fit:** does it solve the task you actually have, and is it intended for end users, makers or developers?
2. **Check compatibility:** confirm the product, plan/licence, skill format, operating environment and required connectors.
3. **Check trust:** review the maintainers, source, recent activity, issues, dependencies, scripts and permissions requested.
4. **Check the licence:** repository-level licences may not cover every asset or bundled skill; inspect the specific files you intend to reuse.
5. **Test safely:** use dummy or approved low-sensitivity data first. Do not install a skill, plugin or MCP server into a work environment without the appropriate review.
6. **Keep a record:** note the date reviewed, owner, version/commit, licence, intended use and any local modifications when adopting a resource.

## Maintenance

- **Last reviewed:** 2026-11-01
- **Review cadence:** revisit links and project status periodically; update entries when a repository changes purpose, becomes archived or is superseded.
- **Curation rule:** favour projects with clear documentation, a concrete use case and transparent ownership. A listing is not an endorsement, security assessment or guarantee of support.

Have a repository to suggest? Add it with a one-line description, its intended audience, when it is useful, and any compatibility or security caveats.
