---
name: db-schema-design
description: "Design relational schemas around integrity, query patterns, and evolution."
---

# db-schema-design

## Purpose
Design relational schemas around integrity, query patterns, and evolution.

## When to use
Activate when the user asks to: database schema; new table; data model.

Category: Design / architecture.

## Workflow
1. Clarify entities, ownership, lifecycle, cardinality, and query patterns.
2. Choose types, nullability, keys, constraints, and indexes from expected queries.
3. Consider transactions, concurrency, retention, privacy, and migrations.
4. Validate representative queries in the target dialect.

## Output expectations
- Keep the response aligned with the requested scope and repository conventions.
- Support project-specific claims with concrete files, commands, test output, or observed behavior.
- Distinguish verified results from recommendations, assumptions, and unknowns.
- Prefer actionable findings and specific next steps over generic advice.

## Guardrails
Avoid premature indexes, ambiguous nullable fields, and dialect assumptions.
- Inspect the working tree before editing and preserve unrelated user changes.
- Do not perform destructive, irreversible, or externally visible actions without explicit authorization.
- Never claim tests, builds, deployments, or audits succeeded unless they were actually run and their results inspected.

## Completion checklist
- [ ] The scope and expected outcome are understood.
- [ ] Relevant repository context and conventions were inspected.
- [ ] The analysis or smallest appropriate change is complete.
- [ ] Relevant verification was run, or its absence and reason are stated.
- [ ] Risks, limitations, and follow-up actions are clear.
