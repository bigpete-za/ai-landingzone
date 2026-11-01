# Context and Memory

AI output is shaped by the current prompt, conversation, supplied files, connected data and product-specific settings. Do not assume the assistant knows your organisation, remembers a previous chat, or can access a file just because it exists somewhere in your tenant.

## Context layers

| Layer | What it means | Practical rule |
|---|---|---|
| Current prompt | Instructions and content in this request | Put the task and constraints here |
| Conversation context | Earlier turns still available in the chat | Start a new chat when the topic or assumptions change |
| Uploaded/attached material | Files explicitly supplied to the session | Name the source and say how it should be used |
| Connected work data | Mail, meetings, documents or other content available through a product integration | Confirm the app, user permissions and grounding scope |
| Custom instructions/profile | Persistent preferences or role guidance supported by the product | Keep stable preferences, not sensitive records or changing project facts |
| Knowledge base / project files | Curated reference material made available to an assistant or agent | Maintain ownership, access controls and version dates |

Names and capabilities differ by vendor. Some products have memory; others use project spaces, notebooks, agents, custom instructions or connected knowledge. These are not interchangeable.

## Build a context packet

For a recurring task, maintain a small approved brief:

- Organisation/team: `[high-level description]`
- Role and audience: `[who is doing the work and for whom]`
- Objective: `[what good looks like]`
- Terminology: `[preferred names, acronyms, definitions]`
- Constraints: `[policies, tone, jurisdiction, scope]`
- Authoritative sources: `[links/files and owners]`
- Known exclusions: `[what must not be assumed or included]`
- Last reviewed: `[date and owner]`

Avoid copying an entire company drive into a prompt. Supply only relevant, permission-appropriate material.

## Memory hygiene

- Treat model memory as convenience, not as a records system or system of record.
- Do not store passwords, access tokens, personal identifiers or sensitive employee/customer facts in prompts or persistent memory.
- Correct outdated context explicitly; do not assume the model notices changes.
- Distinguish verified facts from preferences, hypotheses and temporary project details.
- When precision matters, restate the critical context in the current task.

## Context hand-off prompt

> Before doing the task, summarise the context you believe is relevant, identify which source each key fact came from, and list any important gaps or conflicting information. Do not infer missing facts. Ask me to correct the summary before proceeding.
