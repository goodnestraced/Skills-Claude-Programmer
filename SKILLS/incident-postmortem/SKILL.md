---
name: incident-postmortem
description: "Write a blameless, evidence-based incident review focused on system improvements."
---

# incident-postmortem

## Purpose
Write a blameless, evidence-based incident review focused on system improvements.

## When to use
Activate when the user asks to: postmortem; incident review; outage report.

Category: Debugging.

## Workflow
1. Build a verified timeline, quantify impact and duration, distinguish trigger from contributing factors, describe detection and recovery, and create owned actions with measurable criteria.
2. Mark unknowns and validate facts with participants.

## Output expectations
- Keep the response aligned with the requested scope and repository conventions.
- Support project-specific claims with concrete files, commands, test output, or observed behavior.
- Distinguish verified results from recommendations, assumptions, and unknowns.
- Prefer actionable findings and specific next steps over generic advice.

## Guardrails
Avoid blame, hindsight bias, and vague action items.
- Inspect the working tree before editing and preserve unrelated user changes.
- Do not perform destructive, irreversible, or externally visible actions without explicit authorization.
- Never claim tests, builds, deployments, or audits succeeded unless they were actually run and their results inspected.

## Completion checklist
- [ ] The scope and expected outcome are understood.
- [ ] Relevant repository context and conventions were inspected.
- [ ] The analysis or smallest appropriate change is complete.
- [ ] Relevant verification was run, or its absence and reason are stated.
- [ ] Risks, limitations, and follow-up actions are clear.
