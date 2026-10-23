---
name: boundary-check
description: "Check whether module, service, and domain boundaries are clear and respected."
---

# boundary-check

## Purpose
Check whether module, service, and domain boundaries are clear and respected.

## When to use
Activate when the user asks to: architecture boundaries; coupling; module boundaries.

Category: Design / architecture.

## Workflow
1. Map modules, ownership, interfaces, and dependency direction.
2. Trace imports, calls, shared data, and side effects.
3. Identify cycles, leaky abstractions, cross-layer shortcuts, and duplicated policy.
4. Recommend minimal corrections and enforceable checks.

## Output expectations
- Keep the response aligned with the requested scope and repository conventions.
- Support project-specific claims with concrete files, commands, test output, or observed behavior.
- Distinguish verified results from recommendations, assumptions, and unknowns.
- Prefer actionable findings and specific next steps over generic advice.

## Guardrails
Separate intentional coupling from accidental coupling; follow the project's actual architecture.
- Inspect the working tree before editing and preserve unrelated user changes.
- Do not perform destructive, irreversible, or externally visible actions without explicit authorization.
- Never claim tests, builds, deployments, or audits succeeded unless they were actually run and their results inspected.

## Completion checklist
- [ ] The scope and expected outcome are understood.
- [ ] Relevant repository context and conventions were inspected.
- [ ] The analysis or smallest appropriate change is complete.
- [ ] Relevant verification was run, or its absence and reason are stated.
- [ ] Risks, limitations, and follow-up actions are clear.
