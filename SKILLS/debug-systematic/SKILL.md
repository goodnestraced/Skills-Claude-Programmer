---
name: debug-systematic
description: "Diagnose failures with reproducible experiments rather than guesswork."
---

# debug-systematic

## Purpose
Diagnose failures with reproducible experiments rather than guesswork.

## When to use
Activate when the user asks to: debug this; investigate error; troubleshoot.

Category: Debugging.

## Workflow
1. Capture exact symptoms and environment.
2. Reproduce or record why not.
3. Inspect traces, logs, recent changes, and the smallest relevant path.
4. Rank hypotheses, run discriminating experiments, confirm the cause, add a regression guard, and report evidence.

## Output expectations
- Keep the response aligned with the requested scope and repository conventions.
- Support project-specific claims with concrete files, commands, test output, or observed behavior.
- Distinguish verified results from recommendations, assumptions, and unknowns.
- Prefer actionable findings and specific next steps over generic advice.

## Guardrails
Separate facts, hypotheses, and conclusions; avoid several speculative changes at once.
- Inspect the working tree before editing and preserve unrelated user changes.
- Do not perform destructive, irreversible, or externally visible actions without explicit authorization.
- Never claim tests, builds, deployments, or audits succeeded unless they were actually run and their results inspected.

## Completion checklist
- [ ] The scope and expected outcome are understood.
- [ ] Relevant repository context and conventions were inspected.
- [ ] The analysis or smallest appropriate change is complete.
- [ ] Relevant verification was run, or its absence and reason are stated.
- [ ] Risks, limitations, and follow-up actions are clear.
