---
name: rustfield-riso-graphic-redesign
description: Use when generating or redesigning any reference image, prompt, or established theme in Rustfield's editorial geometric RISO and screen-print language, including people, groups, animals, food, still life, products, landscapes, interiors, posters, films, games, and abstract subjects.
---

# Rustfield RISO Graphic Redesign

Transform any subject through one reusable pop-leaning visual grammar. Preserve what makes the current input specific; change how it is organized and rendered. Every delivery is one complete render, never a stack of corrective edits.

## Runtime contract

The causal order is `identity → form → composition → surface`. Typography, stamps, palette, gaps, registration, and halftone support those decisions; they never replace an unresolved form or composition.

Interpret `MUST` as a hard requirement, `IF` as conditional, `SELECT` as one recorded choice, and `GUIDANCE` as non-overriding planning help. Priority is: current user instruction → supplied/researched facts → [runtime.md](references/runtime.md) → guidance. Ask only when a conflict changes identity, count, action, relationship, setting function, required copy, route, or material.

Read these files in this order for every generation:

1. [references/runtime.md](references/runtime.md) — the sole source of truth for route gates, render contract, prompt compiler, print language, and review;
2. exactly one route file: [references/subject-extraction.md](references/subject-extraction.md) for supplied image input, or [references/text-to-image-path.md](references/text-to-image-path.md) for text-only input;
3. [references/reference-board-analysis.md](references/reference-board-analysis.md) — choose one palette authority and any needed composition, shape, or typography authority;
4. [references/external-reference-routing.md](references/external-reference-routing.md) — only when using an active `ref-###` or web-derived image.

Do not read both route files. `agents/openai.yaml` and `evals/evals.json` are metadata and validation, not runtime instructions.

## Input route

- `IF` the user supplied at least one image, use the image-input route. The default is identity-preserving redesign: retain the subject, count, action/state, relationship, setting function, atmosphere, and indispensable information while rebuilding the visual construction.
- `IF` the user supplied no image, use the text-only route. Research named/established themes before composition so their visual identity is retained rather than replaced by genre shorthand.
- Project-board and web images are supporting references only. They never change a text-only request into an image-input request.

## Output count and title gate

Produce one final image per supplied image unless the user explicitly requests variants or a combined composition. For `N ≥ 2`, plan and render each source independently; do not ask the user to choose a batch mode, a series mode, or a combined output.

Resolve title need before composition. A poster/`海报` request needs a title unless overridden. When the host supports structured choices, use the required title dialog; otherwise ask one explicit title question instead of inventing an answer. Literal title copy is not globally fixed: user-supplied wording takes precedence, then indispensable source copy, then a short title derived from the current subject or visual thesis. Once written into this render's contract, the exact copy is fixed for that render.

## Delivery

Generate from the original content and approved role references in one complete pass. If a candidate fails review, discard it and generate a fresh complete candidate from the original input; never use masking, inpainting, recoloring, overlays, texture passes, or separate typography.

Deliver only reviewed final candidates. Return the image/path plus the compact render contract and final prompt unless the user requested image-only.
