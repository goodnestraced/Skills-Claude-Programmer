---
name: estimate-work
description: "Estimate engineering work with breakdown, assumptions, uncertainty, and validation effort."
---

# estimate-work

## Purpose
Estimate engineering work with breakdown, assumptions, uncertainty, and validation effort.

## When to use
Activate when the user asks to: estimate task; effort estimate; project breakdown.

Category: Stack-specific / Productivity.

## Workflow
Clarify scope and acceptance criteria. Break down implementation, integration, tests, review, rollout, and docs. Give ranges with assumptions, identify unknowns and discovery steps, include dependencies and risk buffers, and state confidence.

## Output expectations
- Follow the requested scope and repository conventions.
- Support project-specific claims with concrete files, commands, test output, or observed behavior.
- Distinguish verified results from assumptions and recommendations.
- Prefer actionable findings and concrete next steps.

## Guardrails
Do not promise dates as certainties; distinguish effort from calendar time.
- Preserve unrelated user changes and inspect the working tree before editing.
- Do not perform destructive or externally visible actions without authorization.
- Never claim checks succeeded unless they were run and their results inspected.

## Completion checklist
- [ ] Scope and expected outcome are understood.
- [ ] Relevant repository context was inspected.
- [ ] Analysis or smallest appropriate change is complete.
- [ ] Verification was run or its absence is stated.
- [ ] Risks and follow-up actions are clear.
