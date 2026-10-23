---
name: ts-strict-mode
description: "Improve TypeScript strictness and remove unsafe typing with maintainable types."
---

# ts-strict-mode

## Purpose
Improve TypeScript strictness and remove unsafe typing with maintainable types.

## When to use
Activate when the user asks to: TypeScript strict mode; remove any; type errors.

Category: Stack-specific / Productivity.

## Workflow
Inspect tsconfig, TypeScript version, and compiler errors. Tighten options incrementally. Replace any with precise types or unknown plus narrowing; model nullability and validate untrusted inputs. Avoid blanket suppressions; run tsc and tests.

## Output expectations
- Follow the requested scope and repository conventions.
- Support project-specific claims with concrete files, commands, test output, or observed behavior.
- Distinguish verified results from assumptions and recommendations.
- Prefer actionable findings and concrete next steps.

## Guardrails
Do not change runtime semantics just to silence the compiler without understanding behavior.
- Preserve unrelated user changes and inspect the working tree before editing.
- Do not perform destructive or externally visible actions without authorization.
- Never claim checks succeeded unless they were run and their results inspected.

## Completion checklist
- [ ] Scope and expected outcome are understood.
- [ ] Relevant repository context was inspected.
- [ ] Analysis or smallest appropriate change is complete.
- [ ] Verification was run or its absence is stated.
- [ ] Risks and follow-up actions are clear.
