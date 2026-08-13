# Generation Path

Use this workflow for any input category. Fill it from the current source; never reuse subject nouns, props, layout devices, or palette words from a prior task.

## 1. Declare the route and output

Record:

- route: identity-preserving redesign, layout-preserving restyle, free semantic translation, or local edit;
- intended use and aspect ratio;
- output count;
- text strategy: preserve required copy, required title, optional title, or no text; for a non-poster request with no explicit text instruction, record one unbiased 50/50 random draw between optional title and no text before selecting references;
- stamp strategy: one or more input-derived stamps, or no stamp when explicitly requested or when a stamp would become template-like decoration;
- exact title/copy when required or selected.

## 2. Build the identity packet

Write four compact statements:

1. `source sentence` — exact subject, count, action/state, relationship or setting function, and atmosphere;
2. `identity kernel` — indispensable appearance, action, setting, relationship, and information anchors;
3. `atmosphere kernel` — energy, density, emotional temperature, contrast, social/environmental scale, and era cue;
4. `discard list` — source rendering, exact coordinates, redundant detail, unauthorized marks, watermarks, and noise.

The discard list may not contain an identity or relationship anchor.

## 3. Select the structural axes

Choose independently:

| Axis | Options |
|---|---|
| Topology | single emblem, relational cluster, single figure, group system, shallow scene, taxonomy/grid, all-over field, typography-led poster, abstract force field |
| Energy | still, warm, lively, kinetic, maximal-controlled |
| Density | sparse, medium, dense, tiled |
| Shape | geometric mass, geometric block, stepped modular mass, mixed clean shape-line |
| Surface | clean flat print, screen print/Riso, restrained pencil accent, xerox-halftone |
| Information | none, caption, labels, title, full hierarchy |

Do not infer one axis from another. A quiet still life need not be pastel; a dense scene need not become a poster; a person-led image need not be centered.

## 4. Assign reference roles

Label each image before attachment:

```text
Reference 1 — content: preserve its subject identity, count, action, relationships, setting function, and atmosphere.
Reference 2 — composition: use hierarchy, crop, scale, spacing, and depth order only.
Reference 3 — shape: use simplification and diagnostic construction only; preserve source-specific anatomy/form.
Reference 4 — palette: copy this exact user-board image's ink families, dominance order, approximate area ratios, and contrast only.
Reference 5 — mandatory material calibration: always attach `reference_images/material-calibration-riso-edge.png`; use only its coarse ink contact, low-frequency edge wobble, unequal paper gaps, halftone clusters, missing-ink rubs, and registration offsets; never use its colors, grid, or abstract block composition.
Reference 6 — typography: use its recorded font skeleton, weight/width, size hierarchy, line breaks, alignment, spacing, baseline/rotation, and image-type interlock only; preserve the planned wording exactly.
```

Attach only the roles actually needed, except Reference 5, which is required for every render. Count it within the four-reference limit.

Selection gates:

- Match the shape reference to the subject category and subtype.
- Match composition to topology, energy, density, and output ratio—not to a shared decorative motif.
- Let one exact user-board image control the complete palette relationship. Record its file name, 4–8 ink families, dominance order, and approximate area percentages before prompt writing.
- Do not average, interpolate, or freely combine palette colors from multiple references. A composition, shape, material, or typography reference contributes no color unless it is separately declared as the sole palette anchor.
- The mandatory material calibration controls print behavior only. It cannot be omitted because the written prompt seems sufficient. Reject any additional material reference dominated by watercolor, gouache, dry brush, fuzzy pigment, pasted craft, or realistic modeling.
- Do not import subjects, clothing, accessories, text, props, or exact object coordinates from supporting references. A composition reference may contribute abstract hierarchy, crop, scale, spacing, and depth-order mechanisms only.
- Use no typography reference when text is absent.

## 5. Lock the blueprint

The blueprint must resolve:

- what remains recognizable;
- what changes structurally;
- exact subject/object count and relationship graph;
- setting carriers and support/ground/enclosure structure;
- large, medium, and small mass placement;
- crop, overlap, rotation, asymmetry, and depth order;
- open-space or crowding target;
- exact palette-anchor file, ink families, dominance order, approximate area ratios, and any identity-critical source-color exception;
- diagnostic features and allowable simplification for each main subject;
- one global boundary plan for every major color junction: irregular narrow gap, exposed paper/light sliver, overlap, or registration offset;
- texture type and intensity;
- text strategy, exact required/selected title or copy, and typography placement;
- for posters, one exact typography-reference file plus its recorded font construction, size relationships, line breaks, alignment, spacing, baseline/rotation, and image-type interlock;
- one or more stamp plans derived from visible source elements for image input, or concrete brief/identity anchors for text-only input, normally occupying 3–10% of the canvas in total;
- independent text strategy and stamp strategy.

No unresolved optional-text choice may remain. The prompt must state the completed random result, not ask the image model to decide whether text appears.

Unless the route preserves layout, name at least one meaningful structural change. Do not force every image to use an enclosure, central subject, three supports, or square format. The stamp is a small supporting information element, not a fixed composition template.

## 6. Compile the render prompt

Keep the source-specific portion concise, but never shorten, paraphrase, or remove the mandatory material lock to meet a word target. Use four ordered blocks.

### Identity lock

Name the source-specific invariants first: subject type and count, defining features, action/state, relationship, setting function, atmosphere, and exact information.

### Composition

State topology, output ratio, large/medium/small hierarchy, subject placement, crop, overlap, context carriers, and deliberate structural change.

### Treatment

Name the exact palette-anchor file and state its ink families, area relationship, and contrast pattern. Then state diagnostic shape simplification, independent stamp and resolved text strategies, black limit, and conditional rules such as featureless faces only when people appear. Geometry controls hierarchy, scale, and abstraction only; it must not produce rigid rectangles, ruler-straight joins, polished vector curves, or generic icon reduction.

Paste the following material lock verbatim as the final paragraph of every render prompt:

Compatibility terms that must remain literal inside the lock: `neutral natural-white paper base`; `clearly visible low-frequency irregular contour wobble`; `narrow unequal gaps, exposed paper slivers, slight overlaps, and registration offsets`; `localized halftone clusters, uneven ink density, and small missing-ink rubs`.

```text
MANDATORY MATERIAL LOCK — Attach material-calibration-riso-edge.png and copy only its physical print behavior, never its colors or layout. Use a neutral natural-white paper base with no yellowed or aged cast. Every major silhouette must have clearly visible low-frequency irregular contour wobble: broad and hand-pulled, readable but never vector-smooth, laser-cut, or digitally snapped. At every major color junction create narrow unequal gaps, exposed paper slivers, slight overlaps, and registration offsets; do not let large blocks meet in perfect seams. Show tactile not-fully-set ink through localized halftone clusters, uneven ink density, and small missing-ink rubs, plus a few short ink-drag marks. These effects must be visible at normal viewing size, not hidden as microscopic grain. Geometry controls mass organization, never edge finish. No polished vector art, rigid rectangular reduction, watercolor, gouache, cut paper, fuzzy brushwork, beige paper, or uniform full-frame distress.
```

### Avoid

Name three to five failures most likely for this source: wrong count/species/action, lost setting, imported motifs, wrong material, or text failure. Do not paste the full global exclusion list.

## 7. Generate and inspect

Use the original content source with the selected reference set. Generate each candidate as one complete image from those original inputs. A generated candidate is never an edit target or supporting reference for the next attempt.

Inspect at two scales:

- thumbnail: source recognition, hierarchy, count, topology, energy, density, palette;
- full size: diagnostic features, global boundary behavior, line/detail budget, text, accidental objects, logos, watermarks, and texture.

Selected typography, selected input-derived stamp(s), composition, palette, shapes, gaps, and print surface must all be present in this same render.

## 8. Restart by failure type

- Any failed candidate: discard it; never mask, inpaint, recolor, overlay, retexture, or separately typeset it.
- Identity failure: rebuild the identity packet and full blueprint, then generate fresh from the original inputs.
- Topology failure: restore count, relationship graph, setting skeleton, or composition structure in a new full prompt, then generate fresh.
- Palette/material failure: keep or replace the single palette anchor, rewrite the complete palette-area contract, then generate fresh.
- Text/stamp failure: rewrite the exact information plan in the complete prompt, then generate fresh; do not repair the old image.
- Repeated failure: report the exact mismatch instead of presenting or patching a failed candidate.

## Output record

```text
Image/path:
Route/topology:
Source sentence:
Identity kernel:
Reference roles:
Palette source and area relationship:
Information layer:
Blueprint summary:
Final prompt:
Identity review:
Atmosphere review:
Board-style review:
Remaining uncertainty:
```
