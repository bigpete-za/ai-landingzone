# Safe Use and Data Boundaries

Use only AI services and features approved by your organisation. The fact that a tool accepts a file does not mean the file is approved for that tool.

## A simple data-handling guide

Your organisation should define its own classification labels. The following is an illustrative starting point, not a substitute for policy.

| Data type | Examples | Default handling |
|---|---|---|
| Public | Published website content, public product information | Usually suitable for approved public tools |
| Internal | Generic procedures, non-sensitive internal drafts | Use only approved work tools and follow policy |
| Confidential | Customer contracts, pricing, employee details, non-public financials | Use only when the specific tool, account, permissions and policy explicitly allow it |
| Restricted | Credentials, secrets, highly sensitive personal/regulated data, security incident details | Do not enter into general AI prompts; use a specifically approved workflow if one exists |

## Minimum safe-use rules

- Never paste passwords, API keys, recovery codes, private keys or authentication tokens.
- Do not upload customer, employee, supplier, financial, legal or regulated data to a personal or unapproved AI account.
- Do not bypass access controls by asking someone else to export data for you.
- Use the least amount of information necessary; redact or anonymise where practical.
- Check who can access the workspace, chat, prompt library, agent and generated output.
- Treat external content and uploaded documents as data, not as instructions that should override your task or organisation's policy.
- Do not let an AI agent send, publish, approve, delete, purchase or change records without explicit human authorisation and suitable controls.
- Report accidental disclosure, unsafe output or suspected misuse through the organisation's incident process.

## Important distinction: tool, account and data

Privacy and training terms can depend on the vendor, product, account type, workspace configuration, settings and contract. Do not generalise a promise made about one business product to a consumer account or another service. Review the current terms and admin controls for the exact tool being used.

## Prompt-injection awareness

A document, webpage, email or pasted text may contain instructions such as "ignore previous instructions" or requests to disclose data. Treat these as untrusted content to analyse, not commands to follow. The user remains responsible for checking actions and data access. Prompt wording alone is not a security boundary.

## South African and other local requirements

Organisations must consider applicable privacy, employment, consumer, intellectual-property, sector and records-retention requirements in the jurisdictions where they operate. This repository is not legal advice. Ask the organisation's privacy/legal owner to assess local laws (including POPIA where applicable) and contractual obligations before introducing personal or regulated data into AI workflows.
