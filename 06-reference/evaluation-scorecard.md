# Prompt and Workflow Evaluation Scorecard

Rate each dimension from 1 (poor) to 5 (excellent). Test on realistic, anonymised examples, including edge cases.

| Dimension | What to assess |
|---|---|
| Task fit | Does it solve the real job-to-be-done? |
| Accuracy | Are factual claims and calculations correct? |
| Grounding | Does it use the right sources and cite them correctly? |
| Completeness | Does it cover the required points without key omissions? |
| Clarity | Is the output understandable and well structured? |
| Consistency | Does it produce an acceptable result across different inputs? |
| Safety | Does it respect data boundaries and avoid unauthorised commitments/actions? |
| Usability | Does it reduce effort after including review and correction time? |
| Maintainability | Is an owner assigned and is the content easy to review/update? |

## Suggested acceptance rule

Do not approve a prompt because it worked once. Define a minimum score for the task and treat accuracy, grounding and safety as mandatory gates for consequential work. Record failure examples and improve the prompt or workflow. Some tasks may be unsuitable for AI even after prompt refinement.

## Test cases

- Normal, complete input.
- Missing or ambiguous information.
- Conflicting sources.
- Outdated source material.
- Incorrect assumptions in user-provided text.
- Request for sensitive or unauthorised information.
- Output that could create a commercial or legal commitment.

## Record

Prompt/skill name · version · owner · product tested · test date · examples used · score · known limitations · next review date.
