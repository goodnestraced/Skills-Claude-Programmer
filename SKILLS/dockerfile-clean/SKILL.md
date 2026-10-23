---
name: dockerfile-clean
description: "Improve Dockerfiles for security, reproducibility, caching, and small runtime images."
---

# dockerfile-clean

## Purpose
Improve Dockerfiles for security, reproducibility, caching, and small runtime images.

## When to use
Activate when the user asks to: clean Dockerfile; optimize image; container security.

Category: DevOps.

## Workflow
Inspect runtime, build context, manifests, and deployment needs. Check base images, multi-stage builds, layer order, non-root user, minimal packages, secret handling, signals, health checks, and copied files. Build/lint when possible.

## Output expectations
- Follow the requested scope and repository conventions.
- Support project-specific claims with concrete files, commands, test output, or observed behavior.
- Distinguish verified results from assumptions and recommendations.
- Prefer actionable findings and concrete next steps.

## Guardrails
Do not copy secrets into layers or change runtime assumptions blindly.
- Preserve unrelated user changes and inspect the working tree before editing.
- Do not perform destructive or externally visible actions without authorization.
- Never claim checks succeeded unless they were run and their results inspected.

## Completion checklist
- [ ] Scope and expected outcome are understood.
- [ ] Relevant repository context was inspected.
- [ ] Analysis or smallest appropriate change is complete.
- [ ] Verification was run or its absence is stated.
- [ ] Risks and follow-up actions are clear.
