---
name: threat-model-lite
description: "Create a lightweight threat model of assets, trust boundaries, abuse cases, and mitigations."
---

# threat-model-lite

## Purpose
Create a lightweight threat model of assets, trust boundaries, abuse cases, and mitigations.

## When to use
Activate when the user asks to: threat model; abuse cases; attack surface.

Category: Security.

## Workflow
1. Describe system, assets, users, entry points, and trust boundaries.
2. Sketch data flow.
3. Enumerate plausible system-specific abuse cases, identify existing controls and gaps, prioritize mitigations, and record assumptions and open questions.

## Output expectations
- Keep the response aligned with the requested scope and repository conventions.
- Support project-specific claims with concrete files, commands, test output, or observed behavior.
- Distinguish verified results from recommendations, assumptions, and unknowns.
- Prefer actionable findings and specific next steps over generic advice.

## Guardrails
Distinguish confirmed weaknesses from hypothetical scenarios.
- Inspect the working tree before editing and preserve unrelated user changes.
- Do not perform destructive, irreversible, or externally visible actions without explicit authorization.
- Never claim tests, builds, deployments, or audits succeeded unless they were actually run and their results inspected.

## Completion checklist
- [ ] The scope and expected outcome are understood.
- [ ] Relevant repository context and conventions were inspected.
- [ ] The analysis or smallest appropriate change is complete.
- [ ] Relevant verification was run, or its absence and reason are stated.
- [ ] Risks, limitations, and follow-up actions are clear.
