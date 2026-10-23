---
name: api-docs
description: "Document API operations, schemas, examples, authentication, and failures accurately."
---

# api-docs

## Purpose
Document API operations, schemas, examples, authentication, and failures accurately.

## When to use
Activate when the user asks to: API docs; OpenAPI; endpoint documentation.

Category: Documentation.

## Workflow
Inspect routes, schemas, middleware, and specs. Document method/path, auth, parameters, request/response schemas, grounded success/error examples, pagination, limits, and versioning. Keep specs aligned and validate examples.

## Output expectations
- Follow the requested scope and repository conventions.
- Support project-specific claims with files, commands, test output, or observed behavior.
- Distinguish verified results from assumptions and recommendations.
- Prefer actionable findings and concrete next steps.

## Guardrails
Do not expose internal/secret fields or document unsupported behavior.
- Preserve unrelated user changes and inspect the working tree before editing.
- Do not perform destructive or externally visible actions without authorization.
- Never claim checks succeeded unless they were run and their results inspected.

## Completion checklist
- [ ] Scope and expected outcome are understood.
- [ ] Relevant repository context was inspected.
- [ ] Analysis or smallest appropriate change is complete.
- [ ] Verification was run or its absence is stated.
- [ ] Risks and follow-up actions are clear.
