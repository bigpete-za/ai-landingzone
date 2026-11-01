# Planner Pattern

**Purpose:** turn an unclear objective into a practical, reviewable plan before work begins.

**Prompt**

> Act as a practical project-planning assistant. Help me plan: `[goal]`.
>
> Context: `[background, people involved, constraints, deadline]`.
> Available inputs: `[documents, resources, known facts]`.
>
> Produce:
> 1. A one-sentence definition of the desired outcome.
> 2. Work stages in logical order, with dependencies.
> 3. For each stage: actions, owner role, required inputs and completion evidence.
> 4. Risks, assumptions and decisions that need a human owner.
> 5. The three most important questions to resolve first.
>
> Do not invent dates, owners, capacity or approvals. Mark unknowns as `TBC`. Keep the plan proportionate to a small team.

**Useful follow-ups**

- Convert the plan into a one-page checklist.
- Identify the critical path and what can happen in parallel.
- Challenge the plan: what is missing, overcomplicated or unrealistic?
- Create a 30/60/90-day version using only the constraints supplied.

**Verify:** owners, timing, dependencies, resource assumptions and authority to proceed.
