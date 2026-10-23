---
name: diff-minimal
description: "Keep changes within requested scope and avoid unrelated churn."
---

# diff-minimal

## Purpose
Keep changes within requested scope and avoid unrelated churn.

## When to use
Activate when the user asks to: minimal diff; only change what's needed.

Category: Productivity / meta-skills.

## Workflow
Inspect request and working tree. Identify smallest file/line set. Preserve style, avoid unrelated renames/formatting/dependency changes, separate follow-ups, and review final diff/status for accidental changes.

## Output expectations
- Follow the requested scope and repository conventions.
- Support project-specific claims with concrete files, commands, test output, or observed behavior.
- Distinguish verified results from assumptions and recommendations.
- Prefer actionable findings and concrete next steps.

## Guardrails
Never overwrite existing user changes or silently discard untracked files.
- Preserve unrelated user changes and inspect the working tree before editing.
- Do not perform destructive or externally visible actions without authorization.
- Never claim checks succeeded unless they were run and their results inspected.

## Completion checklist
- [ ] Scope and expected outcome are understood.
- [ ] Relevant repository context was inspected.
- [ ] Analysis or smallest appropriate change is complete.
- [ ] Verification was run or its absence is stated.
- [ ] Risks and follow-up actions are clear.
