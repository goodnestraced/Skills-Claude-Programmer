---
name: changelog-writer
description: "Turn verified changes into clear, categorized release notes."
---

# changelog-writer

## Purpose
Turn verified changes into clear, categorized release notes.

## When to use
Activate when the user asks to: changelog; release notes; changelog entries.

Category: Git / workflow.

## Workflow
Inspect format and release scope. Gather verified changes from commits/PRs. Group by user impact, explain changes plainly, include breaking changes and migration notes when supported, and check duplicates/version ordering.

## Output expectations
- Follow the requested scope and repository conventions.
- Support project-specific claims with files, commands, test output, or observed behavior.
- Distinguish verified results from assumptions and recommendations.
- Prefer actionable findings and concrete next steps.

## Guardrails
Do not invent features, fixes, issue links, or release dates.
- Preserve unrelated user changes and inspect the working tree before editing.
- Do not perform destructive or externally visible actions without authorization.
- Never claim checks succeeded unless they were run and their results inspected.

## Completion checklist
- [ ] Scope and expected outcome are understood.
- [ ] Relevant repository context was inspected.
- [ ] Analysis or smallest appropriate change is complete.
- [ ] Verification was run or its absence is stated.
- [ ] Risks and follow-up actions are clear.
