---
name: legacy-rescue
description: "Stabilize unfamiliar legacy code through low-risk incremental changes."
---

# legacy-rescue

## Purpose
Stabilize unfamiliar legacy code through low-risk incremental changes.

## When to use
Activate when the user asks to: legacy code; stabilize module; hard to maintain.

Category: Writing / code quality.

## Workflow
1. Map entry points, runtime, dependencies, and undocumented contracts.
2. Add characterization tests, identify one high-risk defect or seam, change incrementally, verify, and document hazards and next steps.

## Output expectations
- Keep the response aligned with the requested scope and repository conventions.
- Support project-specific claims with concrete files, commands, test output, or observed behavior.
- Distinguish verified results from recommendations, assumptions, and unknowns.
- Prefer actionable findings and specific next steps over generic advice.

## Guardrails
Avoid broad rewrites, mass formatting, and dependency upgrades as a first step.
- Inspect the working tree before editing and preserve unrelated user changes.
- Do not perform destructive, irreversible, or externally visible actions without explicit authorization.
- Never claim tests, builds, deployments, or audits succeeded unless they were actually run and their results inspected.

## Completion checklist
- [ ] The scope and expected outcome are understood.
- [ ] Relevant repository context and conventions were inspected.
- [ ] The analysis or smallest appropriate change is complete.
- [ ] Relevant verification was run, or its absence and reason are stated.
- [ ] Risks, limitations, and follow-up actions are clear.
