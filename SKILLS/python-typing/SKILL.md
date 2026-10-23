---
name: python-typing
description: "Improve Python annotations and type-checker compatibility without obscuring runtime behavior."
---

# python-typing

## Purpose
Improve Python annotations and type-checker compatibility without obscuring runtime behavior.

## When to use
Activate when the user asks to: Python types; mypy; pyright; type hints.

Category: Stack-specific / Productivity.

## Workflow
Inspect Python version, checker, and strictness. Annotate public APIs and boundaries. Use precise unions, generics, Protocol, TypedDict, or dataclasses when useful. Avoid Any leakage and unjustified casts; run configured checker/tests.

## Output expectations
- Follow the requested scope and repository conventions.
- Support project-specific claims with concrete files, commands, test output, or observed behavior.
- Distinguish verified results from assumptions and recommendations.
- Prefer actionable findings and concrete next steps.

## Guardrails
Do not imply static types prove runtime validity; use syntax supported by project Python.
- Preserve unrelated user changes and inspect the working tree before editing.
- Do not perform destructive or externally visible actions without authorization.
- Never claim checks succeeded unless they were run and their results inspected.

## Completion checklist
- [ ] Scope and expected outcome are understood.
- [ ] Relevant repository context was inspected.
- [ ] Analysis or smallest appropriate change is complete.
- [ ] Verification was run or its absence is stated.
- [ ] Risks and follow-up actions are clear.
