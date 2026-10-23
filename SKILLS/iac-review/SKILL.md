---
name: iac-review
description: "Review infrastructure-as-code for security, reliability, cost, and destructive changes."
---

# iac-review

## Purpose
Review infrastructure-as-code for security, reliability, cost, and destructive changes.

## When to use
Activate when the user asks to: Terraform review; IaC security; cloud config.

Category: DevOps.

## Workflow
Identify provider, environment, state, and intent. Inspect plan for exposure, IAM, encryption, networking, backups, replacements/deletions, secrets, drift, availability, and cost. Run validation/plan only when safe and configured.

## Output expectations
- Follow the requested scope and repository conventions.
- Support project-specific claims with concrete files, commands, test output, or observed behavior.
- Distinguish verified results from assumptions and recommendations.
- Prefer actionable findings and concrete next steps.

## Guardrails
Never apply changes or expose sensitive state without explicit authorization.
- Preserve unrelated user changes and inspect the working tree before editing.
- Do not perform destructive or externally visible actions without authorization.
- Never claim checks succeeded unless they were run and their results inspected.

## Completion checklist
- [ ] Scope and expected outcome are understood.
- [ ] Relevant repository context was inspected.
- [ ] Analysis or smallest appropriate change is complete.
- [ ] Verification was run or its absence is stated.
- [ ] Risks and follow-up actions are clear.
