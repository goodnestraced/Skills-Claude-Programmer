---
name: verify-before-claim
description: "Verify commands, tests, and outputs before claiming completion."
---

# verify-before-claim

## Purpose
Verify commands, tests, and outputs before claiming completion.

## When to use
Activate when the user asks to: verify before claim; confirm it works; tests pass.

Category: Stack-specific / Productivity.

## Workflow
Define observable completion checks. Inspect scripts/tools, run relevant checks, inspect exit codes and output, investigate failures, and distinguish verified facts from partial checks. Report exact commands and outcomes.

## Output expectations
- Follow the requested scope and repository conventions.
- Support project-specific claims with concrete files, commands, test output, or observed behavior.
- Distinguish verified results from assumptions and recommendations.
- Prefer actionable findings and concrete next steps.

## Guardrails
Never claim a test, build, deployment, or runtime behavior was verified unless actually checked.
- Preserve unrelated user changes and inspect the working tree before editing.
- Do not perform destructive or externally visible actions without authorization.
- Never claim checks succeeded unless they were run and their results inspected.

## Completion checklist
- [ ] Scope and expected outcome are understood.
- [ ] Relevant repository context was inspected.
- [ ] Analysis or smallest appropriate change is complete.
- [ ] Verification was run or its absence is stated.
- [ ] Risks and follow-up actions are clear.
