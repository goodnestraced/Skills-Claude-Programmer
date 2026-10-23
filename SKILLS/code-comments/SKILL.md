---
name: code-comments
description: "Add comments that explain intent, invariants, and non-obvious decisions."
---

# code-comments

## Purpose
Add comments that explain intent, invariants, and non-obvious decisions.

## When to use
Activate when the user asks to: add comments; explain tricky code.

Category: Documentation.

## Workflow
Prefer clearer naming/structure before comments. Explain why, invariants, edge cases, external constraints, and tradeoffs. Keep comments concise and nearby; remove stale or redundant ones and verify against final code.

## Output expectations
- Follow the requested scope and repository conventions.
- Support project-specific claims with files, commands, test output, or observed behavior.
- Distinguish verified results from assumptions and recommendations.
- Prefer actionable findings and concrete next steps.

## Guardrails
Do not narrate obvious syntax or duplicate code in prose.
- Preserve unrelated user changes and inspect the working tree before editing.
- Do not perform destructive or externally visible actions without authorization.
- Never claim checks succeeded unless they were run and their results inspected.

## Completion checklist
- [ ] Scope and expected outcome are understood.
- [ ] Relevant repository context was inspected.
- [ ] Analysis or smallest appropriate change is complete.
- [ ] Verification was run or its absence is stated.
- [ ] Risks and follow-up actions are clear.
