---
name: test-first
description: "Implement behavior using a failing test first, then the smallest passing change."
---

# test-first

## Purpose
Implement behavior using a failing test first, then the smallest passing change.

## When to use
Activate when the user asks to: write tests first; TDD; implement with tests.

Category: Writing / code quality.

## Workflow
1. Inspect test conventions.
2. Translate requirements into observable examples and edge cases.
3. Add a focused test, run it to confirm the intended failure, implement the smallest fix, then refactor with tests green.
4. Run relevant suites and report exact outcomes.

## Output expectations
- Keep the response aligned with the requested scope and repository conventions.
- Support project-specific claims with concrete files, commands, test output, or observed behavior.
- Distinguish verified results from recommendations, assumptions, and unknowns.
- Prefer actionable findings and specific next steps over generic advice.

## Guardrails
Do not claim red-green completion if the initial failing test was not run.
- Inspect the working tree before editing and preserve unrelated user changes.
- Do not perform destructive, irreversible, or externally visible actions without explicit authorization.
- Never claim tests, builds, deployments, or audits succeeded unless they were actually run and their results inspected.

## Completion checklist
- [ ] The scope and expected outcome are understood.
- [ ] Relevant repository context and conventions were inspected.
- [ ] The analysis or smallest appropriate change is complete.
- [ ] Relevant verification was run, or its absence and reason are stated.
- [ ] Risks, limitations, and follow-up actions are clear.
