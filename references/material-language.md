# Material Language

Use this gate for every generation. The project is defined by clean geometric color masses printed through screen-print or Riso logic.

## Non-negotiable visual result

- Build every major person, animal, object, and environmental carrier from closed, readable color shapes.
- Keep the primary silhouette crisp and continuous. Handmade irregularity may shift registration, edge alignment, or ink density, but it may not make the edge fuzzy, feathery, wet, pasted, or brush-built.
- Make every major color junction participate in one shared registration-boundary system: a narrow irregular paper/light-color gap, slight overlap, or offset registration sliver. Vary the behavior by junction; do not make all joins edge-to-edge, uniformly outlined, or separated by equal wide gutters.
- Let large and medium color fields carry the image. Texture, line, grain, halftone, and registration are secondary evidence.
- For people, color masses must carry anatomy and identity. A figure should survive as a small set of abstract blocks without relying on line drawing.
- Preserve a clear large/medium/small hierarchy at thumbnail size.
- Use one declared user-board image as the palette authority. Copy its ink families, dominance order, approximate area ratios, and contrast pattern; do not synthesize a hybrid from several references.
- Keep the result pop-leaning through one large high-contrast color relationship and one or two high-chroma accents already present in the palette anchor.
- Allow black only as a controlled ink: keep it below roughly 20–25% of the canvas, and prefer deep plum, deep cobalt, or deep green for large dark fields.

## Dominant surface: screen-print / risograph

- Use 3–6 opaque ink families for quiet or medium images, and 5–8 for high-energy posters or dense scenes.
- Place 5–15% local halftone dots, dot clusters, ink-density shifts, or small registration offsets inside closed shapes or along color boundaries.
- Keep dots local and intentional. Do not cover the whole image with uniform distress.
- Let pop energy come from color clash, scale, crop, flat contrast, and dot fields rather than random decoration.
- Let junctions feel stamped by hand while preserving hierarchy. Strong connected fields may remain connected; registration behavior belongs at meaningful color boundaries, not as a grid that fragments every internal detail.
- Do not use cut-paper material, pasted seams, visible paper thickness, cast/contact shadows, photographed craft texture, watercolor, gouache, or heavy dry-brush.

## Geometric construction

- Build the image from simple assembled masses, blocks, slabs, bands, panels, circles, arches, grids, and irregular-but-clean silhouettes.
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

Before attaching a style image, inspect it at thumbnail size and answer:

1. Are the main subjects readable primarily through closed geometric shapes?
2. Are their outer edges clean even if the interior contains print grain, dots, or pencil marks?
3. Does the palette resemble the project board more than the source photo?
4. Would the generator still understand the reference if its texture were removed?

Attach the image only if all answers are yes. If the image is valuable for action, relationship, or subject analysis but fails the material gate, analyze it offline and encode only the semantic observation in the blueprint. Do not attach it to the generator.

## Prompt lock

Include one positive material sentence and one short exclusion sentence. For example:

```text
Use palette anchor `<exact board file>` as opaque ink families, preserving its dominance order and approximate area ratios. Render all forms as clean geometric masses in flat screen-print/Riso style, with local halftone dots, subtle uneven ink density, and a global junction system of varied narrow paper gaps, slight overlaps, and small registration offsets across every major color relationship.
No cut-paper craft, watercolor, gouache, dry-brush fill, fuzzy painted edges, source-photo palette copying, pure-black dominance, perfectly tiled vector seams, uniform outlines, wide gutters, or all-over distress.
```

Do not use vague phrases such as `handmade`, `rough`, `organic`, or `paper texture` without defining the clean silhouette and exact print mechanism. These words otherwise encourage painterly noise.

## Review gate

Reject the image when any major object edge looks brushed, wet, furry, smudged, pasted, or rubbed. Reject it when the palette has no exact user-board source, blends several references into an invented relationship, or follows the source photo without authorization. Reject it when black dominates more than roughly one quarter of the canvas. Reject it when major color junctions are perfectly snapped everywhere, or when equal wide gaps fragment the composition. Reject it when the surface reads as paper craft, watercolor, gouache, generic vector, or full-frame noise rather than screen-print/Riso with local dot behavior.
Reject it when a human figure still reads as a detailed character illustration because hair strands, clothing seams, shoe details, fingers, jewelry, or continuous contour lines are doing the work that large color masses should do.
