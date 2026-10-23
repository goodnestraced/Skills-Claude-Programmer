---
name: refactor-safe
description: "Refactor code while preserving externally observable behavior."
---

# refactor-safe

## Purpose
Refactor code while preserving externally observable behavior.

## When to use
Activate when the user asks to: refactor this; clean up code; simplify without changing behavior.

Category: Writing / code quality.

## Workflow
1. Inspect callers, public interfaces, tests, and invariants.
2. Make one cohesive transformation at a time.
3. Preserve error behavior, ordering, side effects, and edge cases.
4. Run focused tests after each step and review the final diff for unrelated changes.

## Output expectations
- Keep the response aligned with the requested scope and repository conventions.
- Support project-specific claims with concrete files, commands, test output, or observed behavior.
- Distinguish verified results from recommendations, assumptions, and unknowns.
- Prefer actionable findings and specific next steps over generic advice.

## Guardrails
Avoid combining refactors with speculative redesign or feature changes.
- Inspect the working tree before editing and preserve unrelated user changes.
- Do not perform destructive, irreversible, or externally visible actions without explicit authorization.
- Never claim tests, builds, deployments, or audits succeeded unless they were actually run and their results inspected.

## Completion checklist
- [ ] The scope and expected outcome are understood.
- [ ] Relevant repository context and conventions were inspected.
- [ ] The analysis or smallest appropriate change is complete.
- [ ] Relevant verification was run, or its absence and reason are stated.
- [ ] Risks, limitations, and follow-up actions are clear.
