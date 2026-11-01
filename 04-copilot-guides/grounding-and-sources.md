# Copilot Grounding and Sources

## What grounding means

Grounding is the information an AI response is based on beyond the model's general learned patterns. Depending on the Copilot surface and configuration, this can include public web content, files supplied in the prompt, content open in an app, or permitted organisational data accessed through Microsoft 365.

## Ask these questions before relying on an answer

- Which Copilot experience am I using, and what sources can it access?
- Did I attach or reference the correct file, meeting, email or workbook?
- Is it using the current version or a stale copy?
- Does the user have permission to view the source?
- Can I open the cited source and confirm the answer?
- Could the answer have omitted relevant content because it was out of scope, not indexed or inaccessible?

## Useful source-bounded prompt

> Answer using only `[named document/library/meeting/date range]`. Cite the source for each material claim. If you cannot find the information in those sources, say `Not found in the supplied sources`. Do not fill gaps using general knowledge. Tell me if the sources conflict or appear out of date.

## For web research

> Search for current information about `[topic]` as of `[date]`. Prioritise official and primary sources. Give publication/update dates and direct links. Separate what the sources say from your synthesis. Flag any claim that could not be confirmed from the underlying page.

## Source hygiene for SMEs

- Use an agreed SharePoint or document-library location as the source of truth where practical.
- Name files clearly and maintain owner, version and review dates.
- Avoid broad, inherited or anonymous access where it is not needed.
- Review old sharing links, guest access and overshared sites before enabling broad work-data discovery.
- Keep authoritative policies separate from informal notes and drafts.

Official starting point: [Data, Privacy, and Security for Microsoft Copilot](https://learn.microsoft.com/en-us/deployoffice/privacy/microsoft-365-copilot).
