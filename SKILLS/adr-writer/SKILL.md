---
name: adr-writer
description: "Record architecture decisions with context, alternatives, consequences, and status."
---

# adr-writer

## Purpose
Record architecture decisions with context, alternatives, consequences, and status.

## When to use
Activate when the user asks to: write ADR; architecture decision; technical choice.

Category: Design / architecture.

## Workflow
1. Identify decision and constraints.
2. Summarize context, compare realistic alternatives against criteria, state the chosen option and rationale, document tradeoffs and follow-ups, and use repository numbering/status conventions.

## Output expectations
- Keep the response aligned with the requested scope and repository conventions.
- Support project-specific claims with concrete files, commands, test output, or observed behavior.
- Distinguish verified results from recommendations, assumptions, and unknowns.
- Prefer actionable findings and specific next steps over generic advice.

## Guardrails
Do not present preferences as facts or omit meaningful tradeoffs.
- Inspect the working tree before editing and preserve unrelated user changes.
- Do not perform destructive, irreversible, or externally visible actions without explicit authorization.
- Never claim tests, builds, deployments, or audits succeeded unless they were actually run and their results inspected.

## Completion checklist
- [ ] The scope and expected outcome are understood.
- [ ] Relevant repository context and conventions were inspected.
- [ ] The analysis or smallest appropriate change is complete.
- [ ] Relevant verification was run, or its absence and reason are stated.
- [ ] Risks, limitations, and follow-up actions are clear.
