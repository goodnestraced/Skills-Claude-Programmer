---
name: runbook-writer
description: "Write operational runbooks with symptoms, safe diagnostics, mitigation, and recovery verification."
---

# runbook-writer

## Purpose
Write operational runbooks with symptoms, safe diagnostics, mitigation, and recovery verification.

## When to use
Activate when the user asks to: runbook; incident procedure; troubleshooting guide.

Category: DevOps.

## Workflow
Define service, trigger symptoms, severity, access, and audience. Provide safe diagnostics with expected outputs, risk-labeled mitigations and approval gates, recovery/rollback, escalation, and verification. Link dashboards only when real links are known.

## Output expectations
- Follow the requested scope and repository conventions.
- Support project-specific claims with concrete files, commands, test output, or observed behavior.
- Distinguish verified results from assumptions and recommendations.
- Prefer actionable findings and concrete next steps.

## Guardrails
Do not invent contacts or dashboards; clearly flag destructive actions.
- Preserve unrelated user changes and inspect the working tree before editing.
- Do not perform destructive or externally visible actions without authorization.
- Never claim checks succeeded unless they were run and their results inspected.

## Completion checklist
- [ ] Scope and expected outcome are understood.
- [ ] Relevant repository context was inspected.
- [ ] Analysis or smallest appropriate change is complete.
- [ ] Verification was run or its absence is stated.
- [ ] Risks and follow-up actions are clear.
