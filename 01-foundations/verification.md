# Verification

AI can produce fluent, plausible and incorrect content. The more consequential the output, the stronger the verification must be.

## The verification loop

1. **Trace:** What source supports each important factual claim?
2. **Check:** Open the source. Confirm names, dates, figures, quotations and context.
3. **Compare:** Look for contradictory evidence and missing perspectives.
4. **Recalculate:** Independently check totals, percentages, formulas and units.
5. **Assess:** Does the output actually answer the question and suit the audience?
6. **Approve:** A person with the right authority owns the final decision or communication.

## Ask the model to expose uncertainty

Useful instruction:

> Separate sourced facts, your analysis and assumptions. For each material factual claim, cite the supplied source and indicate where it appears. If you cannot support a claim from the sources, label it `unverified` or omit it. List conflicting evidence and unresolved questions. Do not invent citations.

For a more structured review, use [Formal Verification Mode](../02-prompt-patterns/formal-verification-mode.md). For draft-quality feedback, use the [Critic Pattern](../02-prompt-patterns/critic.md).

## Check more carefully when

- The information is recent, regulated, contractual or policy-related.
- The output includes financial figures, calculations or forecasts.
- The output names a person, customer, product, law, standard or supplier.
- A claim could affect someone's rights, safety, employment or finances.
- The content will be public, customer-facing or used by leadership to decide.

## Source-quality checklist

- Is the source authoritative for this claim?
- Is it current and applicable to the right date, region, product and version?
- Is the full source available, or only a snippet or summary?
- Does the source actually support the statement being made?
- Is there a second independent source for a high-impact claim?

## Never accept as evidence

A citation that does not resolve, a quotation you cannot find, a calculation without inspectable inputs, or a confident statement without supporting evidence.

**Remember:** an AI's review of its own answer is not independent verification. Check critical claims against primary sources, original records or independently validated calculations.
