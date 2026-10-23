---
name: performance-profile
description: "Measure performance, locate bottlenecks, and validate improvements."
---

# performance-profile

## Purpose
Measure performance, locate bottlenecks, and validate improvements.

## When to use
Activate when the user asks to: slow code; optimize; profile; latency.

Category: Debugging.

## Workflow
1. Establish workload and baseline.
2. Use available profilers.
3. Identify dominant costs by evidence, change the smallest relevant area, rerun comparable measurements and correctness tests, then report methodology and limitations.

## Output expectations
- Keep the response aligned with the requested scope and repository conventions.
- Support project-specific claims with concrete files, commands, test output, or observed behavior.
- Distinguish verified results from recommendations, assumptions, and unknowns.
- Prefer actionable findings and specific next steps over generic advice.

## Guardrails
Do not report speedups from incomparable runs or optimize by intuition alone.
- Inspect the working tree before editing and preserve unrelated user changes.
- Do not perform destructive, irreversible, or externally visible actions without explicit authorization.
- Never claim tests, builds, deployments, or audits succeeded unless they were actually run and their results inspected.

## Completion checklist
- [ ] The scope and expected outcome are understood.
- [ ] Relevant repository context and conventions were inspected.
- [ ] The analysis or smallest appropriate change is complete.
- [ ] Relevant verification was run, or its absence and reason are stated.
- [ ] Risks, limitations, and follow-up actions are clear.
