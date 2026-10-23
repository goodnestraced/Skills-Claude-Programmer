---
name: dependency-audit
description: "Assess dependencies for vulnerabilities, maintenance risk, and unnecessary exposure."
---

# dependency-audit

## Purpose
Assess dependencies for vulnerabilities, maintenance risk, and unnecessary exposure.

## When to use
Activate when the user asks to: dependency audit; vulnerable package; supply chain.

Category: Security.

## Workflow
1. Inspect package managers, lockfiles, runtime constraints, direct/transitive dependencies, and advisories.
2. Separate confirmed vulnerabilities from general risk.
3. Recommend minimal compatible upgrades, assess breaking changes, rerun tests/audit if changes are authorized.

## Output expectations
- Keep the response aligned with the requested scope and repository conventions.
- Support project-specific claims with concrete files, commands, test output, or observed behavior.
- Distinguish verified results from recommendations, assumptions, and unknowns.
- Prefer actionable findings and specific next steps over generic advice.

## Guardrails
Do not invent advisory IDs or current security status; avoid blind major upgrades.
- Inspect the working tree before editing and preserve unrelated user changes.
- Do not perform destructive, irreversible, or externally visible actions without explicit authorization.
- Never claim tests, builds, deployments, or audits succeeded unless they were actually run and their results inspected.

## Completion checklist
- [ ] The scope and expected outcome are understood.
- [ ] Relevant repository context and conventions were inspected.
- [ ] The analysis or smallest appropriate change is complete.
- [ ] Relevant verification was run, or its absence and reason are stated.
- [ ] Risks, limitations, and follow-up actions are clear.
