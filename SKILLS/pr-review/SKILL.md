---
name: pr-review
description: "Review a pull request for correctness, regressions, security, and maintainability."
---

# pr-review

## Purpose
Review a pull request for correctness, regressions, security, and maintainability.

## When to use
Activate when the user asks to: review PR; code review; inspect pull request.

Category: Git / workflow.

## Workflow
Read the full diff and surrounding code. Trace changed paths, permissions, errors, and compatibility. Prioritize actionable bugs with file/line, impact, conditions, and fixes. Note missing tests and residual risks.

## Output expectations
- Follow the requested scope and repository conventions.
- Support project-specific claims with files, commands, test output, or observed behavior.
- Distinguish verified results from assumptions and recommendations.
- Prefer actionable findings and concrete next steps.

## Guardrails
Avoid speculative findings stated as certainty and style-only noise.
- Preserve unrelated user changes and inspect the working tree before editing.
- Do not perform destructive or externally visible actions without authorization.
- Never claim checks succeeded unless they were run and their results inspected.

## Completion checklist
- [ ] Scope and expected outcome are understood.
- [ ] Relevant repository context was inspected.
- [ ] Analysis or smallest appropriate change is complete.
- [ ] Verification was run or its absence is stated.
- [ ] Risks and follow-up actions are clear.
