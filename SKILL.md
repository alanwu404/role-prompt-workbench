---
name: role-prompt-workbench
description: Use when someone needs a reusable AI prompt tailored to a job, business task, audience, inputs, constraints, or deliverable.
---

# Role Prompt Workbench

Create a task-specific prompt that helps an AI produce useful work from the user's real context. Treat role and industry as context, not as a substitute for the actual goal, source material, or decision criteria.

## Build the prompt

1. Clarify the desired outcome and who will use it. Use details already provided; ask only for information that would change the result.
2. Name the available inputs and how to treat them. Do not imply the AI has seen files, data, policies, or current events that were not supplied or verified.
3. State constraints that matter for this task: scope, tone, format, length, tools, jurisdiction, platform, or deadline. Include only relevant constraints.
4. Define the deliverable in observable terms. Prefer a specific structure, fields, calculations, or decision criteria over vague requests such as “analyze deeply.”
5. Add checks proportional to the stakes: verify calculations, cite current sources where needed, label assumptions, protect sensitive information, and route consequential decisions to a qualified human.
6. Return a ready-to-use prompt. Keep any missing facts as clear placeholders; do not silently fill them in.

## Reusable prompt skeleton

```text
Help me achieve: [desired outcome].
Context and intended audience: [relevant context].
Use these inputs: [materials or data]. If something is missing, identify it instead of inventing it.
Constraints: [scope, format, tone, timing, policies, or other task-specific limits].
Deliver: [concrete output and required sections].
Before finalizing: [checks, sources, calculations, privacy or review requirements].
Separate verified information, assumptions, and recommendations.
```

Adapt or omit fields that do not help the specific task. Do not force the skeleton into every prompt.

## Risk-sensitive handling

- For current claims, market trends, platform rules, laws, medical or financial questions, use authoritative up-to-date sources when available and show source dates. If verification is unavailable, say so.
- For hiring, evaluation, or other decisions about people, use only job-relevant, user-provided criteria; avoid sensitive traits and unsupported inferences. Keep the output advisory and require human review.
- For customer, employee, financial, health, or account data, request the minimum necessary and prefer redacted inputs.
- For public content, prefer original wording and verify rights for supplied media, quotations, brand assets, and examples. If a license is involved, list the proposed uses that need checking (such as posting, adaptation, attribution, monetization, or redistribution) instead of treating a short label like “free” as blanket permission.
- Never promise that a prompt ensures legal, policy, or factual compliance.

## Output

Give the prompt first, ready to copy. Follow with brief notes only when assumptions, placeholders, or verification steps need the user's attention. If the user asked for a prompt library, organize original prompts around their requested tasks and do not reproduce a third-party catalog without permission or a compatible license.
