---
name: api-design
description: "Design evolvable APIs with clear contracts, errors, and compatibility."
---

# api-design

## Purpose
Design evolvable APIs with clear contracts, errors, and compatibility.

## When to use
Activate when the user asks to: design API; endpoint design; API contract.

Category: Design / architecture.

## Workflow
1. Identify consumers and use cases.
2. Define operations, schemas, validation, errors, auth, pagination, idempotency, and rate limits where relevant.
3. Follow naming conventions; consider versioning, deprecation, observability, and docs.
4. Give success/failure examples.

## Output expectations
- Keep the response aligned with the requested scope and repository conventions.
- Support project-specific claims with concrete files, commands, test output, or observed behavior.
- Distinguish verified results from recommendations, assumptions, and unknowns.
- Prefer actionable findings and specific next steps over generic advice.

## Guardrails
Do not add endpoints without a consumer need or leak implementation details.
- Inspect the working tree before editing and preserve unrelated user changes.
- Do not perform destructive, irreversible, or externally visible actions without explicit authorization.
- Never claim tests, builds, deployments, or audits succeeded unless they were actually run and their results inspected.

## Completion checklist
- [ ] The scope and expected outcome are understood.
- [ ] Relevant repository context and conventions were inspected.
- [ ] The analysis or smallest appropriate change is complete.
- [ ] Relevant verification was run, or its absence and reason are stated.
- [ ] Risks, limitations, and follow-up actions are clear.
