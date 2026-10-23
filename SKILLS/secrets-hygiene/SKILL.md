---
name: secrets-hygiene
description: "Prevent credentials and sensitive configuration leaking into code, logs, commits, or artifacts."
---

# secrets-hygiene

## Purpose
Prevent credentials and sensitive configuration leaking into code, logs, commits, or artifacts.

## When to use
Activate when the user asks to: API key; credentials; secrets hygiene; leaked secret.

Category: Security.

## Workflow
1. Inspect diffs and configs for tokens, passwords, keys, and sensitive logs.
2. Use approved secret managers or environment variables; keep examples as placeholders.
3. Check logs/build artifacts.
4. If exposed, advise rotation and assess history; run available scans.

## Output expectations
- Keep the response aligned with the requested scope and repository conventions.
- Support project-specific claims with concrete files, commands, test output, or observed behavior.
- Distinguish verified results from recommendations, assumptions, and unknowns.
- Prefer actionable findings and specific next steps over generic advice.

## Guardrails
Never repeat discovered secrets. Removing a secret from a file does not revoke it or erase Git history.
- Inspect the working tree before editing and preserve unrelated user changes.
- Do not perform destructive, irreversible, or externally visible actions without explicit authorization.
- Never claim tests, builds, deployments, or audits succeeded unless they were actually run and their results inspected.

## Completion checklist
- [ ] The scope and expected outcome are understood.
- [ ] Relevant repository context and conventions were inspected.
- [ ] The analysis or smallest appropriate change is complete.
- [ ] Relevant verification was run, or its absence and reason are stated.
- [ ] Risks, limitations, and follow-up actions are clear.
