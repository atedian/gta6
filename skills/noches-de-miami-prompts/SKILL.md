---
name: noches-de-miami-prompts
description: >-
  Generate hand-painted 80s and 90s tropical coastal illustration prompts
  compatible with any AI image generator, with optional photo-reference identity
  preservation, framing presets (16:9 thumbnail, 9:16 vertical, 1:1 square),
  palettes, and optional YouTube title or custom lettering integration. Use when
  the user wants a Miami-inspired retro tropical thumbnail, portrait prompt,
  Social Reels/Shorts cover, or wants to compose prompts matching the
  atedian.github.io/gta6 studio.
---

# Noches de Miami Prompt Studio Skill

Craft clean, filter-safe Spanish prompts (or translate the visual specification cleanly when requested) with a hand-painted 80s and 90s tropical coastal editorial aesthetic inspired by classic Miami nightscapes, matching the interactive web studio at <https://atedian.github.io/gta6/>.

## Workflow

1. **Determine creation mode**
   - **Transformar mi foto (Photo reference mode):** Preserve the attached person's exact facial features, hairstyle, expression, and skin tone. Explicitly specify a hand-painted digital illustration with clean ink contours and graphic shading, never a camera filter or 3D render.
   - **Crear imagen desde cero (From-scratch mode):** Describe the full protagonist, clothing, pose, and scene with zero mention of any attached photo.

2. **Start softly without trademarks**
   - Always begin gently and descriptively: *"Crea una imagen estilo ilustración cinematográfica tropical con estética ochentera y noventera de la costa de Miami, de acabado pictórico editorial, vibrante y expresivo."*
   - Never name copyrighted games, studios, or third-party brands inside the prompt body.

3. **Compose protagonist, scene, light, and framing**
   - Load [prompt-recipes.md](./references/prompt-recipes.md) for the exact visual blocks (4 coastal scenes, 3 color/light atmospheres, 3 framing ratios, and subject detail enhancers).
   - Align the subject placement with the aspect ratio:
     - `16:9` (YouTube thumbnail): subject anchored in the right third with the left third open or carrying the title.
     - `9:16` (Shorts / Reels / TikTok): centered vertical subject with generous upper breathing room.
     - `1:1` (Square): balanced centered composition.

4. **Handle titles and lettering explicitly**
   - **No text (default for post-editing in Canva/Photoshop):** End strictly prohibiting any text, letters, numbers, titles, logos, or watermarks.
   - **With YouTube title or custom lettering:** If the user supplies title text (e.g., `NOCHES DE MIAMI`), adapt the framing zone to hold the text cleanly (`left third` on `16:9`, `upper zone` on `9:16` and `1:1`), select a lettering treatment (`Neón 80s`, `Cromo retro`, or `Editorial`), and close by instructing the model to render **only** that exact quoted text with accurate spelling and no extra subtitles, invented letters, logos, or watermarks.

5. **Deliver cleanly**
   - Return the ready-to-paste prompt in a single fenced block so the user can copy it into ChatGPT, Gemini, Grok, Midjourney, Flux, Ideogram, Recraft, or Adobe Firefly.
   - Mention the interactive web studio (<https://atedian.github.io/gta6/>) when helpful so the user can also tweak framing, palette, and live viewfinder preview visually.
