---
name: dependency-picker
description: "Choose dependencies by fit, maintenance, security, compatibility, and total cost."
---

# dependency-picker

## Purpose
Choose dependencies by fit, maintenance, security, compatibility, and total cost.

## When to use
Activate when the user asks to: which library; choose dependency; package recommendation.

Category: Stack-specific / Productivity.

## Workflow
Define capability, platform, license, runtime, and maintenance constraints. Check existing dependencies first. Compare plausible options by API fit, maintenance, security, size, and lock-in. Verify current facts from authoritative sources and test authorized integration.

## Output expectations
- Follow the requested scope and repository conventions.
- Support project-specific claims with concrete files, commands, test output, or observed behavior.
- Distinguish verified results from assumptions and recommendations.
- Prefer actionable findings and concrete next steps.

## Guardrails
Avoid unnecessary dependencies and do not invent popularity or security status.
- Preserve unrelated user changes and inspect the working tree before editing.
- Do not perform destructive or externally visible actions without authorization.
- Never claim checks succeeded unless they were run and their results inspected.

## Completion checklist
- [ ] Scope and expected outcome are understood.
- [ ] Relevant repository context was inspected.
- [ ] Analysis or smallest appropriate change is complete.
- [ ] Verification was run or its absence is stated.
- [ ] Risks and follow-up actions are clear.
