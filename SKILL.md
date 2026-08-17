---
name: rustfield-riso-graphic-redesign
description: Use when generating or redesigning any reference image, prompt, or established theme in Rustfield's editorial geometric RISO and screen-print language, including people, groups, animals, food, still life, products, landscapes, interiors, posters, films, games, and abstract subjects.
---

# Rustfield RISO Graphic Redesign

Transform any subject through one reusable pop-leaning visual grammar. Preserve what makes the input specific; change how it is organized and rendered. Build every delivered image as one complete render rather than a stack of corrective edits.

## Route by user input

- `IF` the user supplied at least one image, select the image-input route and use [references/subject-extraction.md](references/subject-extraction.md).
- `IF` the user supplied no image, select the text-only route and use [references/text-to-image-path.md](references/text-to-image-path.md), including theme-reference research before composition design and explicit visual identity anchors before rendering.
- Images selected by this Skill from the project board or web are supporting references only; they never change a text-only request into an image-input request.

## Rule status and mandatory reading order

Interpret every instruction using these statuses:

- `MUST` — a hard requirement; a candidate that fails it is rejected.
- `IF` — a conditional requirement; apply it only when the stated condition is true.
- `SELECT` — choose exactly one recorded option before writing the prompt.
- `GUIDANCE` — a planning aid; it never overrides the user's exact content, count, text, or explicit material request.

When statements appear to conflict, use this priority order: the current user's explicit instruction; exact facts in the supplied image or researched subject; the shared visual contract; then `GUIDANCE`. If two requirements at the same priority level conflict, stop and ask the user. Do not invent an unrecorded requirement.

`IF` the user does not specify a variant count, generate and deliver exactly one image. Generate multiple images only when the user explicitly requests a number or distinct directions.

Read the following files in this exact order for every generation:

1. [references/rustfield-visual-contract.md](references/rustfield-visual-contract.md) — shared visual rules;
2. [references/generation-path.md](references/generation-path.md) — route, reference roles, blueprint, prompt, and restart sequence;
3. [references/material-language.md](references/material-language.md) — mandatory print-surface lock;
4. exactly one route file: [references/subject-extraction.md](references/subject-extraction.md) for image input, or [references/text-to-image-path.md](references/text-to-image-path.md) for text-only input;
5. [references/reference-board-analysis.md](references/reference-board-analysis.md) — select the current palette and any supporting board references;
6. [references/external-reference-routing.md](references/external-reference-routing.md) — only when an active `reference_images/ref-###-*` or web-derived external image is being used;
7. [references/production-protocol.md](references/production-protocol.md) — final preflight, review, and restart.

Do not skip steps 1, 2, 3, 5, or 7. Do not read both route files for one request. `agents/openai.yaml` is interface metadata and `evals/evals.json` is validation data; neither is part of the runtime generation path.

## Fixed production order

The runtime sequence is not interchangeable: route → title decision gate → meaning → visual thesis → large subject-specific silhouettes → title-aware redesigned composition → role-separated references and one palette anchor → text/stamps → global gaps/overlaps/registration → local RISO evidence → one frozen render contract → one short prompt → one complete render. Never begin with texture, never let a material reference choose the composition, and never treat a source-photo trace with a print filter as a redesign.

## Title decision gate

Resolve whether the image needs a new text title before choosing topology, negative space, typography reference, or composition. If the user already required a title or no title, use that answer. Otherwise ask one concise question: **“这张图需要加入文字标题吗？请选择：需要标题 / 不需要标题 / 只保留输入图已有文字、不新增标题。”**

An explicit `海报`/`poster` request remains a title request unless the user explicitly overrides it. Once the answer is recorded, use it for the complete render; do not infer, randomize, or change it later.

## Render contract gate

Before writing the prompt, freeze one compact contract from [references/generation-path.md](references/generation-path.md): route; title mode and exact copy when applicable; source/identity kernel; topology/energy/density; one primary and one secondary structural change; one palette-anchor file with roles and area relationship; paper substrate versus colored field; dominant silhouettes and diagnostics; boundary behavior; gap/overlap/registration behavior; local print evidence; and stamp strategy. Every field must have one value. Do not carry unresolved alternatives into the prompt.

## Core contract

For image input, `IF` the user did not explicitly request another route, select `identity-preserving redesign`:

- Preserve subject type and count, defining appearance, action/state, relationship topology, setting function, atmosphere, and indispensable text.
- Rebuild scale, crop, coordinates, depth, shape construction, palette, and material.
- Simplify construction, not meaning. Fewer shapes per object must not become fewer source-specific ideas.
- Let the input control content. Let the project reference board control palette and the mandatory RISO print language unless the user explicitly requests source-color preservation.
- Treat any named color, label, product form, uniform, landmark, or species marking as a possible identity anchor before replacing it.

Never import a recurring subject, motif, layout, prop, or title from a previous task. Every image begins with a fresh extraction from its own source.

The accepted historical batches are evidence for the shared process, not a reusable subject template: recompute palette, topology, mass budget, title, stamps, and source-specific avoid items for every new input.

## Choose the route

Choose one route before planning:

1. `identity-preserving redesign` — selected for supplied image input unless the user explicitly requests another route; preserve identity and relational structure while changing visual construction.
2. `layout-preserving restyle` — use only when the user asks to keep the same composition or pose.
3. `free semantic translation` — use only when the user authorizes a more distant metaphor or abstraction.
4. `local edit` — use only when the user explicitly asks to edit an existing supplied image; complete the requested edit in one render.

IF an unresolved ambiguity changes subject identity, count, action, relationship, setting function, required text, paper/material, route, or reference role, ask the user before generating. Otherwise record one explicit assumption in the blueprint. Never leave a material choice implicit.

## Build the source model

Before choosing a composition, record:

| Field | Required observation |
|---|---|
| Subject | exact type, count band, and defining silhouette/features |
| Action/state | what each subject is doing or how it is positioned |
| Relationships | inside, around, touching, facing, sharing, holding, containing, supporting, or repeating |
| Setting function | the place or container and why it matters |
| Context carriers | minimum environmental cues needed to preserve the setting |
| Atmosphere | energy, density, emotional temperature, contrast, scale, and era cue |
| Information | exact text, labels, dates, signage, interface, or no text |
| Noise | duplicated detail, watermark, platform UI, unauthorized branding, and accidental clutter |

Classify visible features:

- `identity anchor` — removal breaks recognition;
- `relationship anchor` — removal breaks action or scene logic;
- `atmosphere carrier` — preserve its effect through rhythm, color, scale, or density;
- `style surface` — replace with the project language;
- `noise` — discard.

Write one specific source sentence and one planned-result sentence. They must name the same subject, action/state, relationship or setting function, and atmosphere unless the chosen route authorizes a change.

## Choose structure independently

Select each axis from the current source rather than as a bundled style preset:

- topology: single emblem, relational cluster, single figure, group system, shallow scene, taxonomy/grid, all-over field, typography-led poster, or abstract force field;
- energy: still, warm, lively, kinetic, or maximal-controlled;
- density: sparse, medium, dense, or tiled;
- shape: geometric mass, geometric block, stepped modular mass, or mixed clean shape-line;
- surface: screen print/Riso (MUST; pencil, xerox, or flat-ink variation may appear only as sparse sub-treatment, never as the dominant medium);
- information: none, caption, labels, title, or full hierarchy.

Unless layout preservation was requested, choose one primary and one secondary structural device from scale, crop, rotation, asymmetry, enclosure, overlap, viewpoint compression, module distribution, depth order, or negative-space pattern. The primary change must alter hierarchy; the secondary change must alter relation or rhythm. Do not use two changes merely to satisfy a count.

## Reference roles

Assign every attached image exactly one role:

- `content` — identity, action, relationships, setting, and atmosphere;
- `composition` — hierarchy, crop, scale, spacing, and depth order;
- `shape` — simplification and diagnostic construction for the same subject type;
- `palette` — one exact user-board image controls only ink families, dominance order, approximate area ratios, and contrast pattern;
- `material` — the project material calibration reference is mandatory for every render and controls only ink contact, halftone, density variation, registration behavior, gaps, and boundary character; it never contributes content, composition, or palette;
- `typography` — font skeleton, weight/width, size hierarchy, line breaks, alignment, baseline/rotation, spacing, and image-type interlock for preserved copy or a deliberately designed title.

Attach only references that change a real design decision, except that `reference_images/material-calibration-riso-edge.png` is always attached as the mandatory material reference. For image input, attach the supplied image plus the calibration; add supporting references only when they resolve a remaining content, composition, shape, palette, or typography decision. For text-only work, attach the calibration plus only the theme/project references needed to make the researched identity and the blueprint concrete. Stop attaching when every required external decision has one role-assigned source; there is no arbitrary attachment quota. Analyze additional sources in notes rather than attaching a mood board. Name one exact user-board file as the palette anchor. If several anchors fit, prefer the one matching the current energy and density; if still tied, choose the one whose color-area relationship is clearest to reproduce and record its file number. Record every visible ink family needed for that relationship and its approximate area proportions; do not blend several references into an invented palette. The material calibration may refine print behavior but may not change that palette. A style reference may not contribute new subjects, props, clothing, anatomy, wording, setting, or exact object coordinates. If no shape reference truly matches, let the content source control construction instead of attaching a misleading reference.

Do not prompt for direct imitation of a living artist. Translate references into observable properties.

## Visual grammar

Apply these invariants to every subject category:

- Build every major subject and setting carrier from readable color masses with subject-specific curves, skew, asymmetry, and proportion shifts. Do not equate geometric simplification with rectangles, straight rulers, perfectly smooth vector curves, or minimal icon reduction.
- Use diagnostic features and intentional proportion shifts instead of realistic rendering.
- Compress depth through overlap, stacking, enclosure, panels, ground, horizon, or a support plane.
- Keep a clear large/medium/small hierarchy at thumbnail size.
- Copy the color relationship from one declared user-board palette anchor: ink families, dominance order, approximate area ratios, and contrast pattern. Do not synthesize an untraceable hybrid palette.
- Preserve the selected palette anchor's saturation and contrast. `IF` the anchor is pop-leaning, retain its exaggerated warm/cool or complementary clash, high-chroma accents, decisive scale, and flat area relationships; do not wash it into near-neutrals.
- Keep the output's colors clean and separable: each major mass has a readable dominant ink family, supporting colors have explicit roles, and adjacent masses do not dissolve into uncontrolled gray, brown, yellow, or muddy blends. Low-saturation anchors remain valid when their color boundaries, hierarchy, and contrast pattern are clear; do not force every source into a high-saturation palette.
- Treat neutral natural-white as the paper substrate and exposed slivers/margins; it does not require a white-dominant image when the selected palette uses a colored field.
- MUST keep black secondary: black may occupy at most 25% of the canvas, with a target below 20%; use deep colored inks for large dark fields.
- Make screen-print/Riso evidence visually unmistakable: tactile ink deposits, concentrated halftone clusters, uneven ink coverage, missing-ink rubs, and clearly visible registration drift.
- Make every major color junction participate in one global registration-boundary system: narrow irregular gaps, exposed paper/light slivers, slight overlaps, or offset joins. Vary the behavior by junction; do not create uniform outlines or wide tiled gutters. Strong connected fields may remain connected when needed for hierarchy.
- Keep the subject readable through crisp printed boundaries with clearly visible broad, low-frequency contour wobble. The wobble changes contour location, not edge sharpness; show uneven ink contact, slight registration, and small under-inked breaks without blur, feathering, fuzzy halos, wet watercolor bleeding, pasted craft edges, or polished vector contours.
- Use line only for necessary internal information such as motion, pattern, label, species mark, or sparse structural cue. Do not make continuous outline drawing the main construction system.
- Use a small subject-specific mass/detail budget before adding surface. The accepted batches often began around 6–18 major closed masses and, when the topology supported it, about 70–85% large readable masses; these are starting guides only, never a universal output quota.
- Preserve successful environmental structure, moderate block perspective, functional parts, and sparse structural lines when they carry identity. Geometric construction simplifies and reorganizes the image; it does not automatically erase architecture, context, or adult editorial density.

When people appear, preserve pose, body/crop identity, clothing blocks, action props, and social relationships. `MUST` remove facial features unless the current user explicitly requires them. Reduce hair strands, anatomy lines, seams, folds, fingers, laces, jewelry, and fashion-rendering detail until color masses carry the figure. This is a conditional figure rule, not a rule for non-human subjects.

## Information layer

Resolve the text strategy and stamp strategy independently before prompting.

- `text strategy` — preserve required source copy; use the user's resolved title answer; use stamp-only; or use no text. The title answer is recorded before topology and composition, then carried unchanged into reference selection and prompt writing.
- `stamp strategy` — IF the user explicitly requests no decoration, use no stamp. Otherwise SELECT either `input-derived stamp(s)` or `no stamp when no suitable source/brief element exists`; never use a generic decorative stamp. For image input, derive stamps from visible source elements. For text-only work, derive them from a concrete brief fact or declared identity anchor. Keep stamps visibly secondary.
- When the resolved title answer is `需要标题`, derive the shortest exact title from user-supplied wording, identity-critical source copy, or the named subject, in that precedence order.
- When the text strategy uses a title, inspect the project board and attach one exact typography reference unless the user supplied a complete typography system. Record its observable font construction and layout behavior before composing the image.
- If the resolved title answer is `需要标题`, resolve the title block before surface treatment: choose one role from a bottom title band, side information block, or integrated display-type block according to the topology and negative space; then record exact wording, line breaks, scale hierarchy, alignment, baseline/rotation, spacing, and overlap/interlock with image masses. If the answer is `不需要标题`, do not reserve a title block or attach a typography reference.
- Build titles with legible retro-poster display lettering: condensed, expanded, irregular, rotated, arched, or interlocked according to the selected typography reference. Irregularity belongs to the printed edge and spacing, not to casual handwritten or pseudo-text lettering.
- An explicit no-text request prohibits words but may still use a purely graphic input-derived stamp. An explicit no-decoration request prohibits stamps but does not by itself prohibit required text.
- Do not use generic stars, hearts, planets, flowers, badges, slogans, or pseudo-text when the source does not support them.

## Prompt and review

Follow [references/generation-path.md](references/generation-path.md) to compile a short prompt with five ordered blocks:

1. identity lock;
2. visual thesis and redesigned composition;
3. shape, exact palette provenance, and independent text/stamp strategies;
4. global boundary and local print behavior;
5. only the highest-risk avoid items for this source.

Keep the source-specific prompt concise and concrete (normally 90–200 words) before the fixed material lock. Do not append a mood-board essay or a universal negative list.

Review in this order:

1. source identity and count;
2. action, relationship, and setting function;
3. atmosphere, density, and era cue;
4. composition hierarchy and thumbnail read;
5. palette and material family;
6. subject-specific diagnostics;
7. exact text, unwanted text, logos, and watermarks.

Generate every candidate once from the original content source and approved role references. Never use a generated candidate as the input for masking, inpainting, recoloring, texture passes, regional repair, or separate typography. If review fails, discard that candidate, revise the complete blueprint/prompt, and start a fresh full render from the original inputs.

When only one layer fails, diagnose that layer before rewriting the complete blueprint. Simplify the failing subject or detail layer without flattening an already successful setting, spatial relationship, or information density. A more reduced candidate is not automatically a better candidate.

## Hard failures

Reject a candidate when any apply:

- It matches only a generic theme rather than the same specific source sentence.
- A text-only result for an established subject keeps only its broad genre while losing the declared visual identity anchors that make the named work, world, era, place, or product recognizable.
- It changes an indispensable count, action, relationship, setting, species, product form, or information anchor.
- It imports subjects or motifs from style references or previous tasks.
- It traces the source layout without meaningful redesign, unless layout preservation was requested.
- It preserves the source coordinate graph and only adds a material/filter treatment when layout preservation was not requested.
- It becomes a fixed poster template regardless of the input category.
- It removes necessary environment or group structure in the name of simplicity.
- Its stamp is not derived from a visible source element (image input) or a concrete brief/identity anchor (text-only input).
- Its palette cannot be traced to one declared user-board image and its area relationship.
- It was assembled through sequential edits or a separate text/material pass instead of one complete render.
- Its surface or construction contradicts the active RISO/graphic contract (for example, polished vector seams, full-frame filter grain, or brush-built material) rather than the current source-specific brief. Do not reject a candidate merely because the source requires perspective, functional parts, mature density, or moderate structural detail.
- It reads as polished vector geometry, over-reduced icon art, or rigid rectangular construction instead of tactile printed illustration.
- The mandatory material calibration was not attached, or the result shows no visible contour wobble, no irregular large-junction gaps, or no tactile ink evidence at normal viewing size.
- Color blocks are perfectly snapped everywhere, or the boundary treatment becomes uniform wide gutters.
- Texture, outline, gradient, or perspective overwhelms the large color masses.
- It contains too many micro-elements or uses texture to construct a shape that should have been designed as a large readable mass.
- It violates an explicit content requirement in the current user prompt.
- A prompt explicitly requesting a `海报` or poster whose resolved title answer is `需要标题` produces no title or the title does not identify the requested subject.
- A required or selected title has no declared typography reference or cannot be traced to that reference's recorded font construction, hierarchy, line breaking, alignment, spacing, and image-type relationship.
- Optional title presence, absence, wording, or quality is not a rejection or regeneration criterion. Never regenerate solely to add, remove, or improve optional text.
- User-required text is wrong, or an explicit no-text request contains text or pseudo-text.

## Delivery

Show only reviewed final candidates and only the requested number of variants. Keep rejected drafts and superseded repairs out of the final delivery.

Return the image/path plus a compact record of route, source sentence, identity kernel, reference roles, final prompt, and any remaining non-material uncertainty (or `none`). Return image-only when explicitly requested.
