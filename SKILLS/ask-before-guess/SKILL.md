---
name: ask-before-guess
description: "Ask focused clarification when missing information materially affects correctness, scope, or risk."
---

# ask-before-guess

## Purpose
Ask focused clarification when missing information materially affects correctness, scope, or risk.

## When to use
Activate when the user asks to: ask before guessing; unclear requirements; clarify first.

Category: Productivity / meta-skills.

## Workflow
Identify ambiguity and plausible interpretations. If it materially affects correctness, safety, scope, or irreversible actions, ask one concise question with options. Otherwise proceed with the least surprising reversible assumption and state it. Inspect repo evidence first.

## Output expectations
- Follow the requested scope and repository conventions.
- Support project-specific claims with concrete files, commands, test output, or observed behavior.
- Distinguish verified results from assumptions and recommendations.
- Prefer actionable findings and concrete next steps.

## Guardrails
Do not ask questions answerable by repository inspection or overwhelm the user with questionnaires.
- Preserve unrelated user changes and inspect the working tree before editing.
- Do not perform destructive or externally visible actions without authorization.
- Never claim checks succeeded unless they were run and their results inspected.

## Completion checklist
- [ ] Scope and expected outcome are understood.
- [ ] Relevant repository context was inspected.
- [ ] Analysis or smallest appropriate change is complete.
- [ ] Verification was run or its absence is stated.
- [ ] Risks and follow-up actions are clear.
