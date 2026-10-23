---
name: readme-writer
description: "Write a practical README for installation, configuration, usage, and contribution."
---

# readme-writer

## Purpose
Write a practical README for installation, configuration, usage, and contribution.

## When to use
Activate when the user asks to: write README; improve README; project docs.

Category: Documentation.

## Workflow
Inspect repo structure, manifests, scripts, entry points, and existing docs. Identify audience and purpose. Document prerequisites, setup, configuration, minimal usage, tests, troubleshooting, contribution, and license only when supported. Validate commands and links.

## Output expectations
- Follow the requested scope and repository conventions.
- Support project-specific claims with files, commands, test output, or observed behavior.
- Distinguish verified results from assumptions and recommendations.
- Prefer actionable findings and concrete next steps.

## Guardrails
Do not fabricate capabilities, compatibility, badges, license terms, or commands.
- Preserve unrelated user changes and inspect the working tree before editing.
- Do not perform destructive or externally visible actions without authorization.
- Never claim checks succeeded unless they were run and their results inspected.

## Completion checklist
- [ ] Scope and expected outcome are understood.
- [ ] Relevant repository context was inspected.
- [ ] Analysis or smallest appropriate change is complete.
- [ ] Verification was run or its absence is stated.
- [ ] Risks and follow-up actions are clear.
