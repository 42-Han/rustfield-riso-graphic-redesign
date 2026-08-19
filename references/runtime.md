# Runtime

This is the single source of truth for every Rustfield render. It contains the production order, visual contract, Prompt compiler, and review gates. The causal order is `identity → form → composition → surface`. Route files add only source-specific extraction or research rules.

## 1. Production order

Use this exact order:

1. Select the route and output count.
2. Resolve title need before topology, negative space, typography, or composition.
3. Extract meaning and identity anchors.
4. Write the visual thesis.
5. Convert identity into broad subject-specific masses.
6. Design a new title-aware composition.
7. Assign role-separated references and one palette authority.
8. Resolve copy, stamps, and palette roles.
9. Apply the global junction system and selected local print evidence.
10. Freeze one render contract, compile one execution Prompt, and generate one complete image.

Never begin with texture. Never use a source-photo trace plus a print filter as a redesign.

### Multi-image default

When `N ≥ 2` user images are supplied, create one independent blueprint and one final image for each source. Do not ask a batch-mode question or offer series/combined modes. Combine sources only when the user explicitly asks for a combined composition.

### Title decision gate

Use the user's explicit title/no-title instruction when present. Otherwise ask before composition, once for each final image: `不加标题` / `自动生成标题` / `自定义标题`. Ask for exact wording only when `自定义标题` is selected.

`海报`/`poster` means `自动生成标题` unless the user overrides it. Do not randomize this decision. If the host lacks a structured dialog, ask the same question in one short sentence; do not silently choose for the user. Indispensable source copy is preserved automatically and is not a title-choice option.

## 2. Meaning and identity

Record a source/brief sentence naming exact subject, count, action/state, relationship or setting function, atmosphere, and required information. Then classify visible or researched facts:

- `identity anchor` — removing it breaks recognition;
- `relationship anchor` — removing it breaks scene logic;
- `atmosphere carrier` — preserve its effect through rhythm, color, scale, or density;
- `style surface` — replace with this project language;
- `noise` — discard.

Write one visual thesis:

```text
This image is about [specific meaning or tension], expressed through [one dominant spatial, relational, or scale device], not through a collection of explanatory icons.
```

For image input, preserve identity by default. For text-only named works, the route file must establish concrete visual identity anchors before composition. Never import a subject, prop, wording, title, or layout from a previous task.

## 3. Form: direct object conversion

For each main subject and setting carrier, record:

- one dominant silhouette;
- two to five diagnostic features;
- one permitted proportion or viewpoint shift;
- the source detail removed;
- the broad mass or structural band that carries the same identity after removal.

Reduce hair, fur, foliage, folds, seams, reflections, repeated patterns, and line inventories into broad masses, one to three needed internal forms, or nothing. People are faceless unless the user explicitly requires facial features. A printed version of a fine detail remains fine detail and must not be used to retain photographic construction.

Geometry organizes mass, hierarchy, and scale. It is not a demand for boxes, icons, rigid grids, or vector-smooth paths. Use subject-specific curves, blunt angles, leaning axes, asymmetry, awkward proportion, crop, overlap, and only the functional perspective planes necessary for recognition.

At thumbnail size, the result must read as one visual anchor plus supporting mass groups. Texture must never be the reason the subject is recognizable.

## 4. Composition: an explicit new arrangement

For every render, write these concrete fields before selecting surface treatment:

```text
Visual anchor: [source form] becomes [new dominant mass] at [location/scale].
Counterweight(s): [mass] at [location] and its relationship to the anchor.
Open-space / enclosure: [specific field, margin, horizon, frame, or void].
Original arrangement: [source crop, viewpoint, depth order, negative space].
Planned arrangement: [new crop, placement, overlap, depth order, and negative space].
Primary structural change: [crop, scale, viewpoint, or depth-order change].
Secondary structural change: [asymmetry, overlap, rotation, enclosure, module rhythm, or negative-space change].
```

The first two fields are mandatory graphic construction. An optional composition or shape reference may refine them, but they cannot be left to the renderer. Unless layout preservation was explicitly requested, the planned arrangement must visibly change both hierarchy and relation/rhythm from the source; recolor, texture, small crop, or unchanged coordinates do not count.

### Title-aware composition

When a title is selected, reserve its module inside this planned arrangement before selecting typography. Decide whether it is a primary display mass or supporting information, then choose one module:

- bottom title band;
- side information block;
- integrated display-type block;
- quiet outer-margin caption.

The title's literal words come from: user-supplied copy → indispensable source copy → short phrase derived from the current subject or visual thesis. The words are fixed only in this render contract, not across future images or unrelated themes.

Record exact wording, module location, width/height relationship, line breaks, alignment, baseline/rotation, spacing, ink/paper relationship, and whether image masses stop at, pass behind, or overlap the type. Type is never a label dropped onto an already finished image.

## 5. Reference roles

Assign every attached image one narrow role:

- `content` — identity, action, relationship, setting, and atmosphere;
- `composition` — hierarchy, crop, scale, spacing, asymmetry, and depth order;
- `shape` — diagnostic simplification and proportion logic for the same subject type;
- `palette` — one exact board image controls only ink families, dominance order, area relationship, saturation, and contrast;
- `material` — `reference_images/material-calibration-riso-edge.png` is mandatory and controls only print behavior;
- `typography` — font construction and type/image geometry for selected or required text.

Attach the source image and mandatory material calibration for image input. Add a project or web reference only when it changes a recorded decision. The explicit graphic-construction fields above are always required; when an added composition/shape reference improves them, attach it as its own role. A palette, material, or typography reference must never introduce source content, object coordinates, wording, or a new palette.

Choose one exact board palette authority afresh for the current image. Record all necessary ink families, dominance order, approximate area relationship, contrast pattern, and any source-critical color exception. Do not blend palettes. The paper substrate is neutral natural-white; it is not a requirement for a white-dominant composition. Black remains secondary: at most 25% of the canvas, target below 20%.

For selected titles, choose typography after the title module is known. Copy the reference's observable font skeleton, weight/width, hierarchy, line breaks, alignment, rotation, spacing, and type/image interlock—not its wording, objects, palette, or exact layout. A fixed default font or title position is never valid.

## 6. Information and stamps

Preserve required source copy exactly. `不加标题` creates no new title; indispensable source copy remains preserved. When a title is required or selected, render its exact words in the same complete image and review legibility.

Select one source-derived stamp for every render and record its source, location, scale, and visual role. For image input, it comes from a visible prop, tool, landmark, ingredient, sign fragment, species feature, product detail, or silhouette. For text-only work, it comes from a concrete brief fact or declared identity anchor. Add one or two further stamps only when they improve the declared composition. Omit stamps only when the user explicitly requests an extremely minimal result or the source has no meaningful secondary anchor. Stamps remain secondary and compositionally connected; they are not generic decoration.

## 7. Surface: physical print behavior

Use screen-print/RISO, not watercolor, gouache, dry brush, craft collage, polished vector, or generic grain filter.

- Paper is neutral natural-white, never yellowed, cream, beige, sepia, or aged unless the user explicitly requests another substrate.
- Major silhouettes have crisp, hard printed edges with visible broad low-frequency contour wobble. Wobble changes contour location, never edge sharpness: it is not blur, feathering, fuzzy halo, wet bleed, or brush softness.
- Major color junctions share a varied system of narrow unequal gaps, exposed paper/light slivers, slight overlaps, and registration offsets. Strong fields can remain connected when hierarchy requires it; do not use uniform outlines or equal wide gutters.
- Keep most large fields clean. Name only a few local structural zones for concentrated halftone, uneven ink density, missing-ink rubs, short drags, overprint, or registration drift. These marks support form and junctions rather than constructing detail.
- Keep colors clean and separable. Preserve the selected palette's saturation and contrast; vivid anchors retain their high-chroma clash, while restrained anchors remain clear through distinct mass boundaries.

## 8. Render contract and compiler

Freeze one value for every field:

```text
Route / output count:
Title mode / exact copy / hierarchy / module / typography authority:
Source sentence / identity kernel / visual thesis:
Visual anchor / counterweights / open-space or enclosure:
Original arrangement / planned arrangement:
Primary structural change / secondary structural change:
Dominant silhouettes / diagnostics / removed-detail replacements:
Reference roles:
Palette authority / ink roles / area relationship / color exception:
Paper substrate / boundary and junction system:
Named local print zones:
Stamp strategy: source / location / scale / role, or recorded reason for omission:
Source-specific risks:
```

Compile one execution Prompt in this exact order. The compiler does not ask the renderer to make any unresolved design decision:

1. **Render and authorities** — one complete render; name content, graphic construction, palette, material, and typography authorities with their narrow roles.
2. **Identity lock** — subject, count, action/state, relationship, setting function, atmosphere, and indispensable information.
3. **Visual redesign** — visual anchor, counterweights, open space, planned arrangement, primary/secondary structural changes, and title module when selected.
4. **Object conversion** — specific closed masses and structural bands for every main subject; name the source detail removed.
5. **Palette and information** — actual ink families, dominance/area roles, exact title/copy, title geometry and typography construction, source-critical color exception, and selected stamps.
6. **Surface allocation** — neutral natural-white paper, clean large fields, crisp broad contour wobble, varied junction behavior, and only the named local print zones.
7. **Source-specific risks** — only likely identity, information, or material failures for this image.

State observable masses, locations, relationships, and physical effects. Do not append a generic style essay or universal negative list.

## 9. Review and restart

Review in this order:

1. identity, count, action, relationship, setting function, and indispensable copy;
2. thumbnail-scale anchor, broad masses, and genuinely redesigned coordinate graph;
3. declared palette relation and clean color separation;
4. title module, exact copy, typography hierarchy, and the recorded source-derived stamp;
5. enlarged print behavior at at least five major junctions.

At each enlarged junction, confirm at least two visible forms of print evidence: contour wobble, unequal gap, paper sliver, overlap, registration offset, halftone, missing ink, or short ink drag. Restart from the original when the candidate is a source-photo trace, retains photographic micro-detail, lacks the new composition, uses an untraceable palette, turns the substrate yellow, blurs the contour wobble, makes smooth vector seams, fragments into equal gutters, or lets texture outweigh mass hierarchy.

If the user explicitly asks to reproduce or refine a prior delivery, reuse that delivery's recorded render contract and references before changing only the requested field. Otherwise treat each new request as a new blueprint.
