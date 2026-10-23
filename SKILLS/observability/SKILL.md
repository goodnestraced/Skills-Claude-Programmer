---
name: observability
description: "Improve logs, metrics, traces, and alerts for detection and diagnosis."
---

# observability

## Purpose
Improve logs, metrics, traces, and alerts for detection and diagnosis.

## When to use
Activate when the user asks to: observability; logging; metrics; tracing; alerting.

Category: DevOps.

## Workflow
Identify critical journeys and failure modes. Choose actionable signals for latency, traffic, errors, saturation, and outcomes. Add structured logs, bounded-cardinality metrics, trace context, redaction, and alert ownership/runbook links. Verify instrumentation.

## Output expectations
- Follow the requested scope and repository conventions.
- Support project-specific claims with concrete files, commands, test output, or observed behavior.
- Distinguish verified results from assumptions and recommendations.
- Prefer actionable findings and concrete next steps.

## Guardrails
Avoid credentials/PII in logs, unbounded labels, and alerts with no action.
- Preserve unrelated user changes and inspect the working tree before editing.
- Do not perform destructive or externally visible actions without authorization.
- Never claim checks succeeded unless they were run and their results inspected.

## Completion checklist
- [ ] Scope and expected outcome are understood.
- [ ] Relevant repository context was inspected.
- [ ] Analysis or smallest appropriate change is complete.
- [ ] Verification was run or its absence is stated.
- [ ] Risks and follow-up actions are clear.
