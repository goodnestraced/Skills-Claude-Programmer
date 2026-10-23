---
name: root-cause
description: "Trace symptoms to underlying causes and distinguish them from contributing conditions."
---

# root-cause

## Purpose
Trace symptoms to underlying causes and distinguish them from contributing conditions.

## When to use
Activate when the user asks to: root cause; recurring bug; why is this happening.

Category: Debugging.

## Workflow
1. Define the failure and observation point.
2. Trace data/control flow backward across boundaries.
3. Test assumptions, build a causal chain, validate or falsify the suspected cause, then fix the right layer and add a regression guard.

## Output expectations
- Keep the response aligned with the requested scope and repository conventions.
- Support project-specific claims with concrete files, commands, test output, or observed behavior.
- Distinguish verified results from recommendations, assumptions, and unknowns.
- Prefer actionable findings and specific next steps over generic advice.

## Guardrails
Do not stop at the first stack frame or patch only symptoms unless containment is the goal.
- Inspect the working tree before editing and preserve unrelated user changes.
- Do not perform destructive, irreversible, or externally visible actions without explicit authorization.
- Never claim tests, builds, deployments, or audits succeeded unless they were actually run and their results inspected.

## Completion checklist
- [ ] The scope and expected outcome are understood.
- [ ] Relevant repository context and conventions were inspected.
- [ ] The analysis or smallest appropriate change is complete.
- [ ] Relevant verification was run, or its absence and reason are stated.
- [ ] Risks, limitations, and follow-up actions are clear.
