---
name: go-concurrency
description: "Review Go concurrency for races, leaks, cancellation, synchronization, and bounded work."
---

# go-concurrency

## Purpose
Review Go concurrency for races, leaks, cancellation, synchronization, and bounded work.

## When to use
Activate when the user asks to: Go concurrency; goroutines; race; channels; deadlock.

Category: Stack-specific / Productivity.

## Workflow
Trace goroutine lifetimes and shared state. Check channel ownership/lifecycle, cancellation/deadlines, mutex scope, WaitGroup, error propagation, and bounded work. Run focused tests and go test -race where available; explain concrete paths.

## Output expectations
- Follow the requested scope and repository conventions.
- Support project-specific claims with concrete files, commands, test output, or observed behavior.
- Distinguish verified results from assumptions and recommendations.
- Prefer actionable findings and concrete next steps.

## Guardrails
Do not close channels from multiple owners or claim race-freedom from one test.
- Preserve unrelated user changes and inspect the working tree before editing.
- Do not perform destructive or externally visible actions without authorization.
- Never claim checks succeeded unless they were run and their results inspected.

## Completion checklist
- [ ] Scope and expected outcome are understood.
- [ ] Relevant repository context was inspected.
- [ ] Analysis or smallest appropriate change is complete.
- [ ] Verification was run or its absence is stated.
- [ ] Risks and follow-up actions are clear.
