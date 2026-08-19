# Generation Path

This is the runtime order for every render. Do not reorder the stages and do not let a later material or style decision rewrite an earlier content decision.

## Processing order (MUST)

1. **Route first** — determine image-input or text-only route and output count.
2. **Multi-image gate when applicable** — for `N ≥ 2` user sources, resolve batch mode and whether each source gets an independent or shared series solution.
3. **Title decision gate** — resolve whether a new title is needed before topology, negative space, typography reference, or composition.
4. **Meaning** — identify the exact subject, count, action/state, relationships, setting function, atmosphere, and required information.
5. **Visual thesis** — state what the image is about and the one dominant spatial, relational, or scale device that expresses it.
6. **Shape first** — reduce the source to readable subject-specific silhouettes and a small diagnostic set, then complete the abstraction and detail-compression gates below. Do not add texture before the silhouettes and relationships read at thumbnail size.
7. **Title-aware composition** — write the original arrangement and the planned arrangement, reserve the resolved title block only when the user selected a title, then choose one primary and one secondary structural change: crop, scale, rotation, asymmetry, overlap, viewpoint, depth order, enclosure, or negative-space pattern. The primary change alters hierarchy; the secondary changes relation or rhythm. A filter over the original coordinate graph is a failure.
8. **Reference roles** — choose only the references needed for content, composition, shape, palette, material, and typography. Each reference has one role.
9. **Palette and information** — select one exact project-board palette authority, then bind the resolved title/copy mode and source-derived stamp(s) without changing the subject or importing reference content.
10. **Printed surface last** — write the global gap/overlap/registration behavior and local RISO evidence after the mass plan. Texture must support the shapes, never construct them.
11. **Freeze the render contract** — record one value for every required decision below. Do not carry alternatives into the prompt.
12. **One short prompt and one complete render** — compile the ordered prompt below, generate once from the original source and approved references, inspect, and restart from the original if a gate fails.

## 1. Declare the route and output

Record:

- route: `identity-preserving redesign`, `layout-preserving restyle`, `free semantic translation`, or `local edit`;
- batch mode: `single`, `逐图独立重构`, `统一系列重构`, or `合成一张图`;
- source index and total source count when `N ≥ 2`;
- intended use, aspect ratio, and output count (`N` final images for `N` source images unless the batch mode is `合成一张图`; multiply by `K` only when the user requested `K` distinct directions);
- title decision: `需要标题`, `不需要标题`, or `只保留输入图已有文字、不新增标题`;
- text strategy: preserve required copy, resolved title, stamp-only, or no text;
- stamp strategy: source-derived stamp(s), or no stamp when explicitly prohibited or unsupported;
- exact title/copy only when the resolved answer requires or preserves it.

## 2. Multi-image gate (MUST happen before per-image planning)

When `N ≥ 2` user source images are present, record the selected batch mode before writing any source blueprint:

- `逐图独立重构` → create one independent blueprint and one complete final render per source. Recompute topology, composition, palette anchor, title mode, mass budget, and stamp for each source.
- `统一系列重构` → create one shared family contract for material and any intentionally shared palette/typography, then create a separate source blueprint and separate composition for every image.
- `合成一张图` → create one relational blueprint that names each source's role in the combined composition; output exactly one final image.

Never return one representative image for a multi-image request unless `合成一张图` was selected. Never show intermediate drafts or duplicate retries. If the user requests multiple directions, each direction is a separate complete blueprint and final render, not a sequence of edits.

## 3. Title decision gate (MUST happen before composition)

If the user explicitly required a title or no title, record that answer. Otherwise invoke a structured choice dialog before composition planning. For one source, show `需要新增标题`, `不新增标题`, and `只保留输入图已有文字`. For multiple sources, first show `逐图自定义`, `全部新增标题`, and `全部不新增标题`; when `逐图自定义` is selected, invoke the three-choice dialog once per source image. Do not ask the user to type a sentence or an option number.

The word `海报`/`poster` is treated as a title request unless the user explicitly overrides it. Do not choose the title block, typography reference, negative-space target, or composition until the answer is recorded. Once recorded, the answer is fixed for the complete render.

For supplied images, use `identity-preserving redesign` unless the user explicitly selects another route. Project-board or web references selected by the Skill never become the content source.

## 4. Build the meaning packet

Write four compact statements:

1. `source sentence` — exact subject, count, action/state, relationship or setting function, and atmosphere;
2. `identity kernel` — indispensable appearance, action, setting, relationship, and information anchors;
3. `atmosphere kernel` — energy, density, emotional temperature, contrast, scale, and era cue;
4. `discard list` — source rendering, exact coordinates, redundant micro-detail, unauthorized marks, watermarks, and noise. The discard list may not contain an identity or relationship anchor.

Then write one `visual thesis`:

```text
This image is about [specific meaning or tension], expressed through [one dominant spatial, relational, or scale device], not through a collection of explanatory icons.
```

## 5. Build the shape plan before any surface plan

For each main subject, record:

- one dominant silhouette;
- two to five diagnostic features;
- one allowed proportion or viewpoint shift;
- only the internal lines required for action, pattern, label, species mark, or function.

Use the smallest subject-specific mass budget that preserves identity, relationship, setting function, and information. Do not impose a fixed whole-image shape count.

Remove photographic micro-detail: eyes, nose, mouth, hair strands, anatomy contours, seams, folds, fingers, laces, jewelry inventory, tiny reflections, repeated surface pattern, and decorative clutter when the subject remains identifiable without them. People are faceless by default unless the user explicitly requires facial features.

The shape must read before texture. Do not use dots, scratches, grain, or brush marks to make an otherwise generic silhouette recognizable.

### Abstraction and detail compression gate (MUST be complete before surface planning)

This is the single construction gate; it controls form and composition, not surface. For image input, the default redesign must visibly replace photographic construction with a small set of geometric/organic color masses in the first render. Form before surface is the only texture rule. Use a cut-paper-like simplification of the subject's forms without adding cut-paper craft texture:

- For every main subject, record a dominant silhouette, two to five diagnostics, and an explicit removed-detail list. The removed-detail list must name the source features that will not be drawn (for example hair strands, fur texture, cloth folds, seams, foliage texture, window grids, or repeated architectural lines).
- State how the same subject-specific information is carried by the new masses. If a subject is still recognizable only because of photographic micro-detail, the shape plan is incomplete.
- The planned arrangement must make **at least two visible structural changes** from the source: one changes hierarchy (crop, scale, viewpoint, or depth order) and one changes relation/rhythm (asymmetry, overlap, rotation, enclosure, module distribution, or negative-space pattern). A small crop or color swap alone is not a redesign.
- Before the prompt is written, compare the source and planned coordinate graphs. If the dominant subject placement, viewpoint, depth order, and surrounding negative space remain materially the same, return to the composition step and redesign it.
- Functional environments may remain, but translate dense texture or line inventory into a few broad planes, bands, or silhouette carriers. Keep only structural marks that are required to identify the setting or action.

- Replace individual strands, hairs, fur strokes, fabric patterns, or repeated texture lines with one broad silhouette, one to three flat internal masses, or nothing when the identity still reads; remove decorative marks unless they are identity-critical.
- A halftone, ink rub, or printed version of a fine detail is still fine detail. Do not use print marks to preserve photographic hair, fur, fabric, foliage, or pattern inventories.
- At thumbnail size, the composition must read as **one visual anchor plus supporting mass groups**. Preserve source-required counts and relationships inside those groups; large fields carry recognition and micro-detail never carries recognition.
- Keep most large fields clean. local print evidence serves only selected structural areas: reserve halftone clusters, ink-density changes, missing-ink rubs, and ink drags for a few deliberate zones after the masses read; never spread them across every subject or field.
- Record the removed-detail list and the broad mass that replaces each identity-bearing removal in the render contract. If the subject needs texture to be recognized, return to the shape plan and simplify again.

## 6. Redesign the composition explicitly

Record both sides of the redesign:

```text
Original arrangement: [source crop, dominant placement, viewpoint, depth order, and negative space].
Planned arrangement: [new crop, scale hierarchy, placement, overlap, rotation/viewpoint, depth order, and negative space].
Primary structural change: [one hierarchy change: crop, scale, viewpoint, or depth order].
Secondary structural change: [one relation/rhythm change: asymmetry, overlap, enclosure, rotation, module distribution, or negative-space pattern].
```

Preserve subject identity and relationship topology, but do not preserve the source's complete coordinate graph unless layout preservation was requested. Prefer one dominant relationship over an inventory of equally weighted objects. Use crop, unequal scale, off-center weight, overlap, enclosure, shallow perspective, and purposeful open space to make the redesign visibly new. The recomposed arrangement must be visibly different at thumbnail size and must make the dominant subject clearer; the planned arrangement must satisfy the abstraction and detail-compression gates before any material language is added.

## 7. Assign reference roles

Attach only references that change a real design decision, plus the mandatory material calibration:

```text
Reference — content: source identity, count, action, relationships, setting, atmosphere.
Reference — composition: hierarchy, crop, scale, spacing, asymmetry, depth order only.
Reference — shape: diagnostic simplification and proportion logic for the same subject type only.
Reference — palette: one exact project-board image controls ink families, dominance order, area relationship, and contrast pattern only.
Reference 5 — mandatory material calibration: `reference_images/material-calibration-riso-edge.png` controls physical print behavior only.
Reference 6 — typography: font skeleton, weight/width, hierarchy, line breaks, alignment, rotation, spacing, and image interlock only.
```

Never blend palettes from multiple references. Never import subjects, props, clothing, anatomy, wording, branding, or exact coordinates from a style reference. The material calibration contributes no colors, layout, or brush-stroke surface; use only its broad edge wobble, gaps, registration, halftone, ink-density, and missing-ink behavior.

## 8. Resolve palette, text, and stamps

Choose one exact palette anchor and record its file number, ink families, dominance order, approximate area relationship, and warm/cool or complementary contrast. If several anchors fit, choose the one matching the current energy and density; if still tied, choose the one whose color-area relationship is clearest to reproduce and record that choice. Preserve the anchor's own saturation level and high-chroma accents when present; do not force a muted anchor to become neon or a vivid anchor to become dull. Treat neutral natural-white as the paper substrate and visible paper slivers/margins, not as a requirement for a white-dominant image. Keep black secondary, at or below one quarter of the canvas and preferably below one fifth.

The palette output lock is independent of saturation: each major mass must read as a clean dominant ink family, supporting inks must have explicit roles, and adjacent masses must remain visibly separated rather than dissolving into uncontrolled gray, brown, yellow, or muddy mixtures. A restrained or near-monochrome anchor is valid when its hue, value structure, and color boundaries remain clear.

Resolve text and stamps independently:

- resolved answer `需要标题` → required exact title;
- resolved answer `只保留输入图已有文字、不新增标题` → preserve the exact identity-critical copy only;
- resolved answer `不需要标题` → no new title and no typography reference;
- optional title presence or absence is never a regeneration reason;
- source-derived stamp(s) must come from visible input elements or concrete brief anchors and remain secondary;
- no generic stars, hearts, stickers, badges, mascots, slogans, or pseudo-text without source support.

**Title is a planned layout decision.** Use this **Title plan sequence** before writing the prompt:

1. **copy source precedence** — when the user selected `需要标题`, use user-supplied wording first; otherwise preserve identity-critical source text; otherwise derive one short exact title from the named subject or visual thesis;
2. **information mode** — use the recorded answer exactly: `需要标题`, `不需要标题`, or `只保留输入图已有文字、不新增标题`;
3. **title block role** — choose one: **bottom title band, side information block, or integrated display-type block**, according to the planned negative space and mass hierarchy;
4. **typography construction** — only when the answer is `需要标题`, record the reference's font skeleton, weight/width, title-to-body scale, line breaks, alignment, baseline/rotation, spacing, and overlap/interlock with image masses;
5. **prompt binding** — include the exact wording and the resolved block geometry in the same one-pass prompt before adding local print evidence.

Use legible retro display lettering when the answer is `需要标题`; keep irregularity in the printed edge and spacing rather than casual handwriting or unresolved pseudo-text. If the answer is `不需要标题`, leave the render text-free. If the answer is `只保留输入图已有文字、不新增标题`, preserve only that recorded source copy.

## 9. Apply the global boundary system, then local RISO evidence

Every major color junction participates in one shared but varied system of narrow unequal gaps, exposed natural-white slivers, slight overlaps, and registration offsets. Do not use equal wide gutters, uniform outlines, or perfectly snapped seams. Some meaningful fields may remain connected.

After the color masses and composition are solved, add only local print evidence: uneven ink density, concentrated halftone clusters, small missing-ink rubs, a few short ink-drag marks, and selected registration drift. local print evidence serves only selected structural areas; keep most large fields clean and never use full-frame grain or texture to replace shape design.

### Render contract (MUST be complete before the prompt)

```text
Route:
Batch mode / source index:
Title mode / exact copy / title role:
Source sentence / identity kernel:
Topology / energy / density:
Primary structural change:
Secondary structural change:
Palette anchor file / ink roles / area relationship:
Paper substrate versus colored field:
Dominant silhouettes / diagnostics / mass budget:
Abstraction: removed-detail list + how each identity anchor is carried by the new masses:
Boundary: crisp edge + broad low-frequency wobble:
Junctions: unequal gaps + paper slivers + overlaps + registration:
Local print evidence:
Stamp strategy:
Source-specific avoids:
```

Every line must contain one resolved value. This record is the only bridge between planning and the final prompt; do not add a second style summary.

## 10. Compile the prompt in this exact order

Keep the source-specific portion short and concrete (normally 90–200 words). Use five blocks, in this order:

1. **Identity lock** — user/source subject, count, action/state, relationship, setting function, atmosphere, and required information;
2. **Visual thesis and redesigned composition** — planned dominant device, topology, ratio, placement, crop, scale, overlap, rotation/viewpoint, depth order, open space, and the recorded primary and secondary structural changes;
3. **Shape and palette** — dominant silhouettes, diagnostic features, mass budget, removed-detail list and their mass replacements, exact palette-anchor file, ink families, dominance order, area relationship, black limit, text strategy, and stamp strategy;
4. **Boundary and print behavior** — clean separable ink families with explicit dominance, crisp printed edges with broad contour wobble, global unequal gaps/slivers/overlaps/registration, local halftone and ink-density events, and neutral natural-white paper as substrate rather than a forced white field;
5. **Source-specific avoids only** — wrong count/species/action, lost setting, imported motifs, wrong text, or the one material failure most likely for this source.

Do not append a second mood-board description, a generic style essay, or a long universal negative list. State observable mechanisms rather than vague words such as `rough`, `organic`, `handmade`, or `textured`.

Paste the following material lock verbatim as the final paragraph of the prompt:

```text
MATERIAL LOCK — Use a neutral natural-white paper base. Build readable closed color masses first. Each subject must remain a few broad, cut-paper-like flat masses without cut-paper craft material: no individual strands, hairs, fur strokes, fabric patterns, or repeated texture lines; a printed version of a fine detail is still fine detail. At thumbnail size read one visual anchor plus supporting mass groups, preserving source-required counts and relationships inside those groups. Give every major silhouette a crisp, hard-edged printed boundary with clearly visible low-frequency irregular contour wobble, broad and uneven but still sharp; the wobble changes contour location, not edge sharpness, and never becomes blur, feathering, fuzzy halo, wet bleed, or brush-built softness. At meaningful color junctions use narrow unequal gaps, exposed paper slivers, slight overlaps, and registration offsets. Add localized halftone clusters, uneven ink density, and small missing-ink rubs only after the shapes read; keep most large fields clean and reserve print evidence for a few deliberate zones, never use uniform full-frame grain. No yellowed paper, polished vector seams, watercolor, gouache, cut-paper craft, or rigid rectangular reduction.
```

## 11. Generate, review, and restart

Generate the complete image once from the original content source and approved references. Never use a generated candidate as a mask, inpaint target, recolor source, texture pass, or typography input.

Review in this order:

1. identity, count, action, relationship, and setting;
2. visual thesis and genuinely redesigned composition;
3. large-mass hierarchy and shape diagnostics at thumbnail size;
4. palette provenance, saturation, and natural-white paper;
5. global gaps/overlaps/registration and local print evidence at normal size;
6. text, stamps, logos, pseudo-text, and watermarks.

Reject and regenerate from the original when the result is a source-photo trace with a print filter, has too many micro-elements, has no clear dominant silhouettes, fails the two visible structural changes, preserves the original coordinate graph, loses source identity, uses an untraceable palette, lets adjacent color masses dissolve into muddy uncontrolled mixtures, turns the paper substrate yellow, makes the contour wobble blurry, replaces unequal junction behavior with uniform outlines/gutters, or lets texture compete with shape. Optional title presence alone is never a failure.

## Output record

```text
Image/path:
Route/topology:
Source sentence:
Visual thesis:
Identity kernel:
Original arrangement:
Planned arrangement and structural changes:
Reference roles:
Palette source and area relationship:
Render contract:
Information layer:
Shape/mass budget:
Final prompt:
Identity review:
Composition review:
Shape-before-texture review:
Palette/material review:
Remaining non-material uncertainty (or `none`):
```
