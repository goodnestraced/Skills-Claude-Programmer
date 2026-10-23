---
name: test-coverage-gap
description: "Find important untested behavior and add risk-focused tests."
---

# test-coverage-gap

## Purpose
Find important untested behavior and add risk-focused tests.

## When to use
Activate when the user asks to: test gaps; improve coverage; missing tests.

Category: Writing / code quality.

## Workflow
1. Map changed behavior to existing tests.
2. Prioritize boundaries, errors, permissions, retries, and regression risks.
3. Add tests that would catch plausible bugs, reuse fixtures, run them, and summarize residual gaps.

## Output expectations
- Keep the response aligned with the requested scope and repository conventions.
- Support project-specific claims with concrete files, commands, test output, or observed behavior.
- Distinguish verified results from recommendations, assumptions, and unknowns.
- Prefer actionable findings and specific next steps over generic advice.

## Guardrails
Do not optimize for coverage percentage alone or invent metrics.
- Inspect the working tree before editing and preserve unrelated user changes.
- Do not perform destructive, irreversible, or externally visible actions without explicit authorization.
- Never claim tests, builds, deployments, or audits succeeded unless they were actually run and their results inspected.

## Completion checklist
- [ ] The scope and expected outcome are understood.
- [ ] Relevant repository context and conventions were inspected.
- [ ] The analysis or smallest appropriate change is complete.
- [ ] Relevant verification was run, or its absence and reason are stated.
- [ ] Risks, limitations, and follow-up actions are clear.
