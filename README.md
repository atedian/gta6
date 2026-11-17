# Noches de Miami — Generador de Prompts Tropical 80s / 90s

Herramienta web para crear prompts listos para usar en cualquier IA generadora de imágenes, pensada para transformar fotografías o ilustrar escenas y miniaturas con estética tropical nocturna de los años 80 y 90.

**[Abrir la web en vivo](https://atedian.github.io/gta6/)**

## Cómo funciona

1. **Elige el modo de creación:**
   - **Transformar mi foto:** conserva reconocibles las facciones, el peinado, la expresión y el tono de piel de la imagen que adjuntes, reinterpretándola como ilustración digital pintada a mano con contornos definidos y sombras gráficas.
   - **Crear imagen desde cero:** genera la escena completa sin necesitar ninguna fotografía de referencia.
2. **Describe al protagonista con asistente instantáneo:**
   - Escribe vestimenta, pose o expresión en **Protagonista / Acción** o usa los botones **Sugerir idea**, **Mejorar detalle** y los atajos rápidos integrados para enriquecer la descripción sin descargas externas.
3. **Personaliza escenario, paleta y formato:**
   - **Escenario de fondo:** paseo marítimo con palmeras al atardecer, calle con hoteles Art Déco y neón, deportivo clásico junto a la playa o azotea frente al skyline costero.
   - **Paleta y luz:** atardecer coral y magenta, noche de neón turquesa y violeta o sol tropical vibrante de mediodía.
   - **Formato y composición:** `16:9` para miniatura de YouTube, `9:16` vertical o `1:1` cuadrado, eligiendo además si el protagonista va a la **izquierda**, en el **centro** o a la **derecha**.
4. **Incluye título o deja la escena limpia:**
   - **Sin texto:** mantiene el espacio libre para editar después y ordena no añadir letras ni marcas de agua.
   - **Añadir título o texto:** escribe tu titular (por ejemplo para YouTube o portadas), elige rotulación **Neón 80s**, **Cromo retro** o **Editorial** y decide si va a la **izquierda**, al **centro** o a la **derecha**, previsualizando todo en el monitor de encuadre.
5. **Elige versión del prompt, copia y genera:**
   - Selecciona **Estilo GTA 6** para obtener la estética exacta de portada en herramientas como ChatGPT, o cambia con un clic a **Sin copyright** si algún generador estricto bloquea referencias comerciales.
   - Pulsa **Copiar prompt**, abre tu generador de imágenes preferido desde los accesos directos (adjuntando tu foto si elegiste *Transformar mi foto*), pega el texto y genera la imagen.

## Skill para agentes de IA

El repositorio incluye una skill compañera en [`skills/noches-de-miami-prompts/SKILL.md`](skills/noches-de-miami-prompts/SKILL.md) con las mismas reglas de estilo, modos, encuadres y rotulación para usar directamente desde agentes de programación o asistencia:

```sh
npx skills add atedian/gta6
```

## Ejecución local

Todo el proyecto web vive en [`index.html`](index.html) sin dependencias externas ni paso de compilación: basta con abrir ese archivo en cualquier navegador moderno.
