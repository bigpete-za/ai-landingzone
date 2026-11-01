# Data and Spreadsheets

## Understand a workbook

> Inspect the workbook structure before analysing it. Describe worksheets, columns, units, date ranges, formulas, missing values and obvious data-quality issues. Ask questions about ambiguous fields. Do not make business conclusions until the data structure is understood.

## Find trends and exceptions

> Analyse `[dataset/workbook]` for `[business question]`. Explain the method, filters and calculations used. Identify meaningful trends, outliers and segments. Show the underlying figures and distinguish observations from possible explanations. State any limits caused by sample size or missing data.

## Combine automated extraction with AI analysis

Use a flow or script to extract telemetry into a consistent table, then use AI to interpret the validated output. Keep these as separate steps.

**Extraction / validation step**

- Select the source, time window and fields explicitly.
- Normalise timestamps, field names and units; record source and extraction time.
- Validate row counts, required fields, duplicates, parse failures and expected ranges.
- Preserve the raw export and log errors rather than silently dropping bad records.

**Analysis prompt**

> Analyse this validated telemetry table for `[question]`. First summarise its scope, fields, time window and known quality limitations. Identify unusual patterns and supporting counts or examples. Separate observed anomalies from possible explanations. Suggest follow-up checks; do not claim a security incident or root cause from a pattern alone. If the dataset is incomplete or validation failed, explain how that limits the analysis.

Automation can make extraction repeatable, but only if permissions, failures, transformations and validation are designed and monitored. AI interpretation remains probabilistic and should be checked against the underlying records.

## Design a dashboard brief

> Propose a simple dashboard for `[audience]` monitoring `[process/outcome]`. Define each proposed measure, calculation, unit, reporting frequency, data owner, target source and likely limitation. Avoid vanity metrics. Do not invent targets.

## Explain a formula

> Explain this spreadsheet formula in plain language: `[formula]`. Identify inputs, logic, assumptions and likely edge cases. Give a small worked example and suggest tests for blank, invalid and boundary values. Do not claim the formula is correct without checking the workbook context.

**Human check:** source data, formulas, ranges, hidden rows, filters, duplicates, units, date parsing and whether correlation is being mistaken for causation.
