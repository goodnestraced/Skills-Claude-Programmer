---
name: memory-leak-hunt
description: "Investigate growing memory use and identify retention paths or unbounded allocation."
---

# memory-leak-hunt

## Purpose
Investigate growing memory use and identify retention paths or unbounded allocation.

## When to use
Activate when the user asks to: memory leak; heap growth; out of memory.

Category: Debugging.

## Workflow
1. Reproduce memory growth and distinguish heap/native/cache/process memory.
2. Capture repeatable baselines and snapshots.
3. Inspect retention paths, listeners, timers, caches, closures, and lifecycle cleanup.
4. Fix and rerun the same workload.

## Output expectations
- Keep the response aligned with the requested scope and repository conventions.
- Support project-specific claims with concrete files, commands, test output, or observed behavior.
- Distinguish verified results from recommendations, assumptions, and unknowns.
- Prefer actionable findings and specific next steps over generic advice.

## Guardrails
Do not label allocator caching as a leak without evidence or expose sensitive heap data.
- Inspect the working tree before editing and preserve unrelated user changes.
- Do not perform destructive, irreversible, or externally visible actions without explicit authorization.
- Never claim tests, builds, deployments, or audits succeeded unless they were actually run and their results inspected.

## Completion checklist
- [ ] The scope and expected outcome are understood.
- [ ] Relevant repository context and conventions were inspected.
- [ ] The analysis or smallest appropriate change is complete.
- [ ] Relevant verification was run, or its absence and reason are stated.
- [ ] Risks, limitations, and follow-up actions are clear.
