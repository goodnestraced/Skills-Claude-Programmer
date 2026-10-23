---
name: pr-description
description: "Prepare a review-friendly pull request description with scope, rationale, and verification."
---

# pr-description

## Purpose
Prepare a review-friendly pull request description with scope, rationale, and verification.

## When to use
Activate when the user asks to: PR description; pull request body.

Category: Git / workflow.

## Workflow
1. Inspect diff, issue context, and PR template.
2. Explain what changed and why, user impact, risks, migration concerns, and checks actually run.
3. Include screenshots or links only when available and follow repo conventions.

## Output expectations
- Keep the response aligned with the requested scope and repository conventions.
- Support project-specific claims with concrete files, commands, test output, or observed behavior.
- Distinguish verified results from recommendations, assumptions, and unknowns.
- Prefer actionable findings and specific next steps over generic advice.

## Guardrails
Never claim tests passed if they were not run; do not invent ticket numbers.
- Inspect the working tree before editing and preserve unrelated user changes.
- Do not perform destructive, irreversible, or externally visible actions without explicit authorization.
- Never claim tests, builds, deployments, or audits succeeded unless they were actually run and their results inspected.

## Completion checklist
- [ ] The scope and expected outcome are understood.
- [ ] Relevant repository context and conventions were inspected.
- [ ] The analysis or smallest appropriate change is complete.
- [ ] Relevant verification was run, or its absence and reason are stated.
- [ ] Risks, limitations, and follow-up actions are clear.
