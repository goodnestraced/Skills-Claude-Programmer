---
name: sql-optimizer
description: "Optimize SQL using execution plans, indexes, and measured workload evidence."
---

# sql-optimizer

## Purpose
Optimize SQL using execution plans, indexes, and measured workload evidence.

## When to use
Activate when the user asks to: optimize SQL; slow query; query plan.

Category: Stack-specific / Productivity.

## Workflow
Identify engine/version, schema, parameters, and target. Capture query and safe execution plan. Inspect scans, joins, estimates, sorting, filters, and indexes. Make targeted changes, compare plans/timing on representative data, and check result equivalence and write/storage tradeoffs.

## Output expectations
- Follow the requested scope and repository conventions.
- Support project-specific claims with concrete files, commands, test output, or observed behavior.
- Distinguish verified results from assumptions and recommendations.
- Prefer actionable findings and concrete next steps.

## Guardrails
Preserve NULL, ordering, and duplicate semantics; do not run mutating production experiments without approval.
- Preserve unrelated user changes and inspect the working tree before editing.
- Do not perform destructive or externally visible actions without authorization.
- Never claim checks succeeded unless they were run and their results inspected.

## Completion checklist
- [ ] Scope and expected outcome are understood.
- [ ] Relevant repository context was inspected.
- [ ] Analysis or smallest appropriate change is complete.
- [ ] Verification was run or its absence is stated.
- [ ] Risks and follow-up actions are clear.
