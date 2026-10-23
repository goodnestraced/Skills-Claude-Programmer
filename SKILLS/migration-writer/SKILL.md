---
name: migration-writer
description: "Create safe, reversible migrations with explicit rollout and data handling."
---

# migration-writer

## Purpose
Create safe, reversible migrations with explicit rollout and data handling.

## When to use
Activate when the user asks to: write migration; schema migration; add column.

Category: Design / architecture.

## Workflow
1. Inspect migration framework and deployment model.
2. Define compatibility with old/new app versions.
3. Plan backfill, defaults, constraints, locks, indexes, and volume risks.
4. Use expand-migrate-contract when needed; provide rollback or forward recovery and test the migration.

## Output expectations
- Keep the response aligned with the requested scope and repository conventions.
- Support project-specific claims with concrete files, commands, test output, or observed behavior.
- Distinguish verified results from recommendations, assumptions, and unknowns.
- Prefer actionable findings and specific next steps over generic advice.

## Guardrails
Never silently drop/rewrite production data; rollback may not be safe after writes.
- Inspect the working tree before editing and preserve unrelated user changes.
- Do not perform destructive, irreversible, or externally visible actions without explicit authorization.
- Never claim tests, builds, deployments, or audits succeeded unless they were actually run and their results inspected.

## Completion checklist
- [ ] The scope and expected outcome are understood.
- [ ] Relevant repository context and conventions were inspected.
- [ ] The analysis or smallest appropriate change is complete.
- [ ] Relevant verification was run, or its absence and reason are stated.
- [ ] Risks, limitations, and follow-up actions are clear.
