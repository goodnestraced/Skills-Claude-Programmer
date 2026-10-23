---
name: rust-unsafe-review
description: "Review Rust unsafe code for memory safety, aliasing, validity, and sound abstractions."
---

# rust-unsafe-review

## Purpose
Review Rust unsafe code for memory safety, aliasing, validity, and sound abstractions.

## When to use
Activate when the user asks to: Rust unsafe; FFI safety; soundness review.

Category: Stack-specific / Productivity.

## Workflow
Locate unsafe blocks, raw pointers, FFI, and unsafe traits. State safety preconditions. Check validity, alignment, initialization, lifetimes, aliasing, races, layout, and unwind boundaries. Ensure safe callers uphold invariants; isolate unsafe code and run Miri/sanitizers when available.

## Output expectations
- Follow the requested scope and repository conventions.
- Support project-specific claims with concrete files, commands, test output, or observed behavior.
- Distinguish verified results from assumptions and recommendations.
- Prefer actionable findings and concrete next steps.

## Guardrails
Compilation does not prove soundness; do not broaden unsafe scope to satisfy the borrow checker.
- Preserve unrelated user changes and inspect the working tree before editing.
- Do not perform destructive or externally visible actions without authorization.
- Never claim checks succeeded unless they were run and their results inspected.

## Completion checklist
- [ ] Scope and expected outcome are understood.
- [ ] Relevant repository context was inspected.
- [ ] Analysis or smallest appropriate change is complete.
- [ ] Verification was run or its absence is stated.
- [ ] Risks and follow-up actions are clear.
