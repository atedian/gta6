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

2. **Choose style precision vs filter-safe wording**
   - **Direct GTA 6 style (default):** Anchor the model explicitly with *"estilo artístico oficial y exacto de portada de GTA 6 (Grand Theft Auto VI)"* plus its core technique (hand-painted semi-realistic digital painting, crisp ink linework, expressive brush strokes between realistic comic art and digital gouache, cel-shaded contrast shadows, and vibrant tropical cover lighting, avoiding raw photorealism and 3D render).
   - **No-copyright fallback (anti-block):** If the user targets a strict generator that refuses game titles (e.g., Gemini or Adobe Firefly), omit `GTA 6` / `Grand Theft Auto VI` cleanly and describe the exact same modern coastal open-world cover illustration style (*"estilo de portada oficial de videojuego moderno de acción tropical costera, pintura digital semirrealista con contornos entintados limpios y sombreado cel-shaded"*).

3. **Compose protagonist, scene, light, and framing**
   - Load [prompt-recipes.md](./references/prompt-recipes.md) for the exact visual blocks (4 coastal scenes, 3 color/light atmospheres, 3 framing ratios, subject placement options, and subject detail enhancers).
   - Align the subject placement (`izquierda`, `centro`, or `derecha`) cleanly inside the chosen aspect ratio:
     - `16:9` (YouTube thumbnail): protagonist in the chosen side or center (default `derecha`, opposite a clean or titled left third).
     - `9:16` (Shorts / Reels / TikTok): vertical composition with generous upper breathing room (protagonist `izquierda`, `centro`, or `derecha`, default `centro`).
     - `1:1` (Square): balanced composition with protagonist `izquierda`, `centro`, or `derecha`.

4. **Handle titles and lettering explicitly**
   - **No text (default for post-editing in Canva/Photoshop):** Leave space free on the chosen side and end strictly prohibiting any text, letters, numbers, titles, logos, or watermarks.
   - **With YouTube title or custom lettering:** Place the exact quoted text (`«...»`) in the chosen side (`izquierda`, `centro`, or `derecha`) aligned cleanly without overlapping the protagonist's face, choose a lettering style (`Neón 80s`, `Cromo retro`, or `Editorial`), and close instructing the model to render **only** that text with accurate spelling and no extra subtitles, invented letters, logos, or watermarks.

5. **Deliver cleanly**
   - Return the ready-to-paste prompt in a single fenced block so the user can copy it into ChatGPT, Gemini, Grok, Midjourney, Flux, Ideogram, Recraft, or Adobe Firefly.
   - Mention the interactive web studio (<https://atedian.github.io/gta6/>) when helpful so the user can also tweak framing, palette, and live viewfinder preview visually.
