---
name: ci-config
description: "Build or review CI workflows that are secure, deterministic, and efficient."
---

# ci-config

## Purpose
Build or review CI workflows that are secure, deterministic, and efficient.

## When to use
Activate when the user asks to: CI pipeline; GitHub Actions; CI config.

Category: DevOps.

## Workflow
Inspect provider, triggers, scripts, and conventions. Define required checks and platform matrix. Minimize token permissions, pin actions according to policy, use sound cache keys, protect secrets, validate syntax, and run checks where possible.

## Output expectations
- Follow the requested scope and repository conventions.
- Support project-specific claims with concrete files, commands, test output, or observed behavior.
- Distinguish verified results from assumptions and recommendations.
- Prefer actionable findings and concrete next steps.

## Guardrails
Do not disable tests to make CI green or claim remote success without a run.
- Preserve unrelated user changes and inspect the working tree before editing.
- Do not perform destructive or externally visible actions without authorization.
- Never claim checks succeeded unless they were run and their results inspected.

## Completion checklist
- [ ] Scope and expected outcome are understood.
- [ ] Relevant repository context was inspected.
- [ ] Analysis or smallest appropriate change is complete.
- [ ] Verification was run or its absence is stated.
- [ ] Risks and follow-up actions are clear.
