---
name: commit-message
description: "Write concise commit messages aligned with repository conventions."
---

# commit-message

## Purpose
Write concise commit messages aligned with repository conventions.

## When to use
Activate when the user asks to: commit message; commit title; conventional commit.

Category: Git / workflow.

## Workflow
1. Inspect recent messages and conventions.
2. Identify the diff's primary intent.
3. Use an imperative concise subject; use Conventional Commits only if requested or established.
4. Add a body for motivation, tradeoffs, or breaking changes when useful.

## Output expectations
- Keep the response aligned with the requested scope and repository conventions.
- Support project-specific claims with concrete files, commands, test output, or observed behavior.
- Distinguish verified results from recommendations, assumptions, and unknowns.
- Prefer actionable findings and specific next steps over generic advice.

## Guardrails
Do not stage, amend, or commit unless explicitly requested.
- Inspect the working tree before editing and preserve unrelated user changes.
- Do not perform destructive, irreversible, or externally visible actions without explicit authorization.
- Never claim tests, builds, deployments, or audits succeeded unless they were actually run and their results inspected.

## Completion checklist
- [ ] The scope and expected outcome are understood.
- [ ] Relevant repository context and conventions were inspected.
- [ ] The analysis or smallest appropriate change is complete.
- [ ] Relevant verification was run, or its absence and reason are stated.
- [ ] Risks, limitations, and follow-up actions are clear.
