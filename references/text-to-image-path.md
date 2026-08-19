# Text-to-Image Route

Use this route only when the user supplied no image. Follow the common production order in [runtime.md](runtime.md); this file adds only the research and identity rules that text-only work needs.

## Lock the brief

Extract the exact subject, count, defining features, action/state, relationship, setting, atmosphere, energy, density, era or regional cues, required text, and explicit exclusions. The user's wording is the content authority. Write:

- `brief sentence` — the planned subject, action/relationship, setting, and atmosphere;
- `identity kernel` — the minimum visible facts that keep the idea specific;
- `invention budget` — details not specified by the user that may be designed;
- `forbidden drift` — changes that would contradict the brief.

The runtime title decision gate applies before research-driven composition. A user who requests a poster has selected a title unless they explicitly override it.

## Theme reference packet

Research a named film, game, book, event, place, culture, era, profession, product category, or other established subject before composing. Research an ordinary theme only when the brief lacks enough concrete setting, activity, object, or relationship information to avoid a generic scene.

Collect the minimum non-duplicated evidence needed for:

- `content reality` — characteristic people, objects, environments, actions, proportions, and relationships;
- `setting structure` — the spatial skeleton, viewpoint, enclosure, route, support, foreground/background, or horizon;
- `thematic composition` — the relationship that expresses the idea beyond an object inventory;
- `era and atmosphere` — scale, density, gesture, light logic, social distance, and regional/historical cues.

For an established visual world, also record its identity grammar:

```text
Anchor ledger:
Primary anchor — evidence source; visible rule; how it survives; allowed translation.
Primary anchor — evidence source; visible rule; how it survives; allowed translation.
Supporting anchor — evidence source; visible rule; how it supports recognition.
Style-distance budget — surface properties that may change; identity structure that may not change.
```

Primary anchors cover, when relevant, character proportion/silhouette, viewpoint/spatial grammar, key-form grammar, and rhythm/atmosphere. A named work must remain recognizable through those anchors even after its logo, original rendering medium, and screenshot crop are gone. The RISO surface, selected board palette, geometric simplification, new crop, and new composition may change; characteristic body proportion, viewpoint, key silhouettes, world scale, relationships, and energy may not be silently replaced by generic genre substitutes.

## Use external images deliberately

Attach web imagery only when the generation model needs to see identity-critical subject construction, setting structure, action/relationship, or era geometry. Otherwise analyze it and write the resulting facts into the blueprint. For a visually distinctive named work, attach the minimum complementary primary references needed to cover subject/proportion, environment/viewpoint, and action/relationship/key forms.

Every web image is `content` only. It never controls palette, material, typography, wording, or exact coordinates. Project-board references remain responsible for composition, shape, palette, material, and typography according to [runtime.md](runtime.md).

## Route-specific quality gate

Before compiling the Prompt, verify that the planned visual anchor and mass plan visibly carry the anchor ledger. Reject a generic genre substitute: a named farm game cannot become generic agriculture, a cyberpunk game cannot become any neon city, and a film cannot become a poster for its broad genre alone.

At thumbnail and full size, reject a result that reads as juvenile or like a preschool worksheet because it relies on cute generic shorthand, evenly spaced icons, round doll anatomy, literal object-per-zone explanation, nursery color relations, or insufficient environmental and relational structure. Simplicity is valid when the theme remains specific and the composition remains editorial.
