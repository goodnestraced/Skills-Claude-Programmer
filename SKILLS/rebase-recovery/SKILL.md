---
name: rebase-recovery
description: "Recover safely from rebase conflicts while protecting user work."
---

# rebase-recovery

## Purpose
Recover safely from rebase conflicts while protecting user work.

## When to use
Activate when the user asks to: rebase conflict; undo rebase; git recovery.

Category: Git / workflow.

## Workflow
Inspect status, branch, reflog, and operation state. Identify uncommitted work. Preserve work with a backup when appropriate. Resolve semantics rather than blindly choosing ours/theirs. Verify history and tests after recovery.

## Output expectations
- Follow the requested scope and repository conventions.
- Support project-specific claims with files, commands, test output, or observed behavior.
- Distinguish verified results from assumptions and recommendations.
- Prefer actionable findings and concrete next steps.

## Guardrails
Do not run destructive reset, clean, or force-push without understanding consequences and authorization.
- Preserve unrelated user changes and inspect the working tree before editing.
- Do not perform destructive or externally visible actions without authorization.
- Never claim checks succeeded unless they were run and their results inspected.

## Completion checklist
- [ ] Scope and expected outcome are understood.
- [ ] Relevant repository context was inspected.
- [ ] Analysis or smallest appropriate change is complete.
- [ ] Verification was run or its absence is stated.
- [ ] Risks and follow-up actions are clear.
