# Prompt Presets and Visual Blocks

Reference blocks synchronized with the interactive studio (`index.html`).

## Opening & Technique Variants

- **Direct GTA 6 variant (default):**
  `Crea una ilustración con el estilo artístico oficial y exacto de portada de GTA 6 (Grand Theft Auto VI): arte digital pictórico semirrealista de estética tropical costera moderna, con contornos entintados limpios, pincelada marcada, sombras gráficas contrastadas y color cinematográfico vibrante.`
- **No-copyright variant (anti-block):**
  `Crea una ilustración artística con estilo de portada oficial de videojuego moderno de acción tropical costera: arte digital pictórico semirrealista de estética contemporánea de Miami, con contornos entintados limpios, pincelada marcada, sombras gráficas contrastadas y color cinematográfico vibrante.`

## Protagonist Templates

- **Photo mode (GTA 6):**
  `Toma como referencia a la persona de la foto adjunta y mantenla completamente reconocible conservando fielmente sus facciones, peinado, expresión y tono de piel. Reinterprétala como personaje protagonista ilustrado exactamente al estilo oficial de GTA 6 (ilustración digital pintada a mano tipo carátula de GTA VI con líneas de tinta definidas, pincelada pictórica expresiva entre cómic semirrealista y gouache digital, sombreado cel-shaded contrastado e iluminación dramática de portada, sin aspecto de fotografía ni render 3D). Sitúa a esa persona en la escena con esta apariencia y acción: <SUBJECT>.`
- **From-scratch mode (GTA 6):**
  `Ilustra la escena completa exactamente al estilo de arte promocional de portada de GTA 6 (Grand Theft Auto VI): pintura digital semirrealista pintada a mano con contornos entintados limpios, pincelada estilizada expresiva, sombreado gráfico contrastado e iluminación cinematográfica de portada costera, evitando el fotorrealismo crudo y el render 3D. Protagonista y acción principal: <SUBJECT>.`
- *(For the no-copyright fallback, swap explicit game titles for "carátula moderna de mundo abierto costero" / "arte conceptual oficial de portada de acción urbana costera contemporánea").*

## Scenes (`Escenario de fondo`)

- **Paseo marítimo (`boardwalk`):** Un paseo marítimo costero bordeado de palmeras altas recortadas contra el horizonte del atardecer, con reflejos suaves sobre el suelo, brisa marina y siluetas arquitectónicas de la costa en segundo plano.
- **Hoteles Art Déco (`artdeco`):** Una calle nocturna con hoteles de arquitectura Art Déco e iluminación decorativa de neón en formas geométricas abstractas sin rótulos legibles, aceras con reflejos de color y palmeras urbanas.
- **Deportivo clásico (`classic-car`):** Un automóvil deportivo clásico descapotable aparcado junto a la playa al anochecer, con carrocería brillante reflejando las luces del cielo, arena costera, palmeras y el océano detrás.
- **Azotea costera (`rooftop`):** Una azotea elevada con barandilla elegante y plantas tropicales, abierta hacia vistas panorámicas al skyline costero iluminado y reflejos sobre la bahía.
- **Cayos tropicales (`keys`):** Una cadena de cayos tropicales conectados por un largo puente costero sobre aguas turquesa cristalinas, muelles de madera desgastada, casas elevadas sobre pilotes, palmeras bajas y alguna lancha amarrada en el horizonte.
- **Pantanos y manglares (`wetlands`):** Extensos pantanos subtropicales con manglares densos, árboles cubiertos de musgo colgante, aguas quietas con reflejos cálidos, bruma húmeda baja y la silueta de un hidrodeslizador en la orilla.
- **Motel y puerto costero (`port`):** Una zona portuaria y costera algo decadente con un motel bajo de carretera, acera húmeda con reflejos de neón, muelles de carga, grúas portuarias en segundo plano y ambiente nocturno tenso.
- **Carretera e industria interior (`ambrosia`):** Una carretera abierta del interior soleado atravesando campos amplios hacia un complejo industrial con grandes torres y silos al fondo, aire polvoriento dorado, tendido eléctrico y nubes dramatizadas.
- **Parque nacional y montaña (`kalaga`):** Un parque nacional salvaje al norte con colinas escarpadas, bosque denso de pinos altos, río sinuoso cristalino en el valle y senderos de tierra bajo iluminación atmosférica entre los árboles.

## Palettes (`Paleta y luz`)

- **Atardecer cálido coral y magenta:** Atardecer cálido dominado por degradados en rosa coral, magenta y naranja cálido sobre cielo violáceo, con luz rasante dorada recortando al sujeto y sombras profundas saturadas.
- **Noche de neón turquesa y violeta:** Noche de neón con iluminación en turquesa eléctrico, cian y violeta profundo, reflejos vibrantes de alto contraste en bordes y cielo nocturno púrpura oscuro.
- **Sol tropical vibrante de mediodía:** Sol tropical vibrante de mediodía con cielo turquesa luminoso, colores saturados cálidos, brillos intensos y sombras gráficas nítidas.

## Subject & Title Placement (`Izquierda / Centro / Derecha`)

- **Subject positions:** `en el tercio izquierdo`, `en el centro del encuadre`, `en el tercio derecho` (default `derecha` on `16:9`, `centro` on `9:16` / `1:1`).
- **Title positions:** place the label in `el tercio izquierdo despejado`, `la zona central superior`, or `el tercio derecho despejado`. If protagonist and title share the same side, place the title cleanly in the upper zone above the protagonist so the face stays clear.

## Title Lettering Styles (Optional)

- **Neón 80s:** Rotulación tubular brillante estilo neón ochentero en cian eléctrico y magenta con halo luminoso definido.
- **Cromo retro:** Rotulación metálica retro cromada de bordes perfilados con reflejos coral, magenta y dorado cálido de atardecer.
- **Editorial:** Tipografía sans serif condensada en blanco puro de alto contraste editorial y sombra nítida marcada.

## Closing Rules

- **Without text:**
  `Regla final imprescindible: no incluyas texto, letras, números, títulos, logotipos ni marcas de agua en ningún lugar de la imagen.`
- **With integrated title:**
  `Regla final imprescindible: renderiza únicamente el texto indicado («<TITLE>») con ortografía exacta y no añadas subtítulos extra, palabras inventadas, logotipos ni marcas de agua.`
