# Material Language

Use this gate for every generation. The project is defined by simplified expressive masses physically transformed by screen-print or Riso behavior: geometry controls mass organization, never edge finish.

## Non-negotiable visual result

- MUST use a neutral natural-white paper base. Do not warm the paper toward cream, beige, yellow, sepia, or aged stock; change the paper color only when the user explicitly requests a different paper color.
- Build every major person, animal, object, and environmental carrier from readable color shapes. Allow subject-specific curves, blunt angles, leaning axes, asymmetry, and intentional awkwardness; do not reduce everything to boxes, polygons, or icons.
- Keep the primary silhouette continuous with a crisp, hard-edged printed boundary and plainly visible broad, low-frequency irregular contour wobble. The wobble changes contour location, not edge sharpness: it should read as uneven ink contact or slight registration, not blur, feathering, fuzzy halo, wet bleed, brush-built softness, or polished vector-smoothness.
- Make every major color junction participate in one shared registration-boundary system: a narrow irregular paper/light-color gap, slight overlap, or offset registration sliver. Vary the behavior by junction; do not make all joins edge-to-edge, uniformly outlined, or separated by equal wide gutters.
- Let large and medium color fields carry the image. Ink contact, edge wobble, junction gaps, halftone, and registration are local supporting evidence; they must not compete with or replace the silhouettes.
- For people, color masses must carry anatomy and identity. A figure should survive as a small set of abstract blocks without relying on line drawing.
- Preserve a clear large/medium/small hierarchy at thumbnail size.
- Use one declared user-board image as the palette authority. Copy its ink families, dominance order, approximate area ratios, and contrast pattern; do not synthesize a hybrid from several references. A separate material reference may refine print behavior only; it never overrides the palette authority.
- Preserve the selected palette anchor's saturation and contrast. If that anchor is pop-leaning, keep one large high-contrast relationship and one or two high-chroma accents already present in it; do not wash the anchor into near-neutrals.
- Allow black only as a controlled ink: keep it at or below 25% of the canvas, with a target below 20%, and prefer deep plum, deep cobalt, or deep green for large dark fields.

## Dominant surface: screen-print / risograph

- Use the ink families present in the selected palette anchor. Do not impose a fixed color count.
- Place concentrated local halftone fields, ink-density shifts, missing-ink rubs, and registration offsets inside selected shapes and meaningful color boundaries. Use roughly 5–15% visible local ink-event coverage as a starting guide, adjusting only when the declared board reference clearly supports denser evidence.
- Include localized halftone clusters, uneven ink density, and a few small missing-ink rubs where they support form or junctions; keep some large fields almost clean and never simulate the material as one uniform full-frame grain filter.
- Keep dots local and intentional. Do not cover the whole image with uniform distress.
- Let pop energy come first from color clash, scale, crop, flat contrast, and mass relationships; dot fields are secondary evidence, not the source of the composition.
- Let junctions feel stamped by hand while preserving hierarchy. Strong connected fields may remain connected; registration behavior belongs at meaningful color boundaries, not as a grid that fragments every internal detail.
- Do not use cut-paper material, pasted seams, visible paper thickness, cast/contact shadows, photographed craft texture, watercolor, gouache, or heavy dry-brush.

## Expressive mass construction

- Build the image from simple assembled masses, bands, panels, circles, arches, tilted slabs, irregular organic silhouettes, and subject-specific curves. Mix geometry with awkward drawn forms; do not force a rigid modular grid.
- Show overlap and depth through color boundaries, occlusion, stacking, and shallow enclosure.
- Keep object recognition tied to a few diagnostic features, not many small rendered details.
- Avoid long runs of perfectly horizontal or vertical junctions unless they are needed for signage, panels, or typography. Break them with slight offsets, uneven margins, or small negative-space slivers.

## Pencil or crayon accent

- Use pencil only for sparse internal marks, pattern, lettering, face, or motion.
- Do not fill major masses with dense scribbling, and do not let sketch lines replace the silhouette system.
- Do not use pencil or ink lines as a full contour system around bodies, clothing, hair, shoes, fingers, or accessories. If a line is not needed after the color masses are readable, remove it.

## Forbidden surface behavior

- watercolor bloom, translucent wash, wet-on-wet blending, tide marks, or soft color bleeding;
- gouache buildup, opaque paint daubs, thick pigment, scumbling, or visible bristle direction;
- heavy dry-brush fill, fuzzy brushed contours, rubbed edges, or paint strokes used to construct the object;
- cut-paper craft, pasted paper seams, visible paper thickness, contact shadows, or photographed handmade collage;
- all-over paper noise, vintage distress, or grain strong enough to compete with the shapes;
- soft painterly shading, realistic light modeling, glossy volume, or airbrushed gradients.

## Reference attachment gate

Before attaching any optional style image, inspect it at thumbnail size and answer. Always attach `reference_images/material-calibration-riso-edge.png` separately as the mandatory material calibration:

1. Are the main subjects readable primarily through decisive color masses rather than detailed linework?
2. Do their outer edges visibly show broad print wobble and uneven ink contact rather than vector smoothness?
3. Does the palette resemble the project board more than the source photo?
4. Would the generator still understand the reference if its texture were removed?

Attach the image only if all answers are yes. If the image is valuable for action, relationship, or subject analysis but fails the material gate, analyze it offline and encode only the semantic observation in the blueprint. Do not attach it to the generator.

## Prompt lock

Use the complete mandatory material lock in `generation-path.md` verbatim as the final paragraph of every render prompt. Do not replace it with a shorter sentence such as `clean geometric masses`, `subtle texture`, or `slight RISO effect`; those formulations allow vector-smooth edges and weak filter-like grain to override the intended physical print behavior.

Do not use vague phrases such as `handmade`, `rough`, `organic`, or `paper texture` without the mandatory lock's explicit crisp boundary, contour wobble, junction, registration, halftone, ink-density, missing-ink, and paper-base requirements.

## Review gate

Reject the image when it has no visible broad contour wobble, no tactile ink breakup, or no unequal paper gaps at major color junctions. Reject any major edge that looks blurry, feathered, fuzzy, soft-focus, watercolor-wet, furry, pasted, brush-built, or polished vector-smooth. Reject it when the palette has no exact user-board source, blends several references into an invented relationship, or follows the source photo without authorization. Reject it when black dominates more than roughly one quarter of the canvas. Reject it when major color junctions are perfectly snapped everywhere, or when equal wide gaps fragment the composition. Reject it when the surface reads as paper craft, watercolor, gouache, generic vector, or full-frame noise rather than a physically imperfect screen-print/Riso impression.
Reject it when a human figure still reads as a detailed character illustration because hair strands, clothing seams, shoe details, fingers, jewelry, or continuous contour lines are doing the work that large color masses should do.
