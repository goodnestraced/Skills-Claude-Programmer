---
name: security-review
description: "Review code for exploitable weaknesses and prioritize actionable findings."
---

# security-review

## Purpose
Review code for exploitable weaknesses and prioritize actionable findings.

## When to use
Activate when the user asks to: security review; audit code; vulnerabilities.

Category: Security.

## Workflow
1. Map assets, trust boundaries, entry points, and sensitive operations.
2. Inspect authorization, validation, serialization, storage, and errors.
3. Check relevant vulnerability classes, validate reachability, rank findings by severity/confidence, and give evidence and remediation.

## Output expectations
- Keep the response aligned with the requested scope and repository conventions.
- Support project-specific claims with concrete files, commands, test output, or observed behavior.
- Distinguish verified results from recommendations, assumptions, and unknowns.
- Prefer actionable findings and specific next steps over generic advice.

## Guardrails
Do not claim a full security certification from a limited review or exploit live systems.
- Inspect the working tree before editing and preserve unrelated user changes.
- Do not perform destructive, irreversible, or externally visible actions without explicit authorization.
- Never claim tests, builds, deployments, or audits succeeded unless they were actually run and their results inspected.

## Completion checklist
- [ ] The scope and expected outcome are understood.
- [ ] Relevant repository context and conventions were inspected.
- [ ] The analysis or smallest appropriate change is complete.
- [ ] Relevant verification was run, or its absence and reason are stated.
- [ ] Risks, limitations, and follow-up actions are clear.
