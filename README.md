# Generador de Prompts · Miami Nocturno 80s / 90s

Aplicación web estática en un único archivo (`index.html`, sin dependencias externas) para construir prompts en tiempo real orientados a transformar fotografías o crear ilustraciones y miniaturas desde cero con estética tropical nocturna de los años 80 y 90.

## Características

- **100 % estática y sin dependencias:** HTML, CSS y JavaScript integrados en `index.html`; se ejecuta completamente en el navegador.
- **Actualización en tiempo real:** Cada cambio en modo, protagonista/acción, escenario, paleta o formato regenera el prompt automáticamente.
- **Dos modos de creación:**
  - *Transformar mi foto:* mantiene reconocibles facciones, peinado, expresión y tono de piel como ilustración digital pintada a mano.
  - *Crear imagen desde cero:* genera la escena completa sin mencionar fotografías adjuntas.
- **Accesos rápidos y portapapeles:** Botón de copia con API moderna (`navigator.clipboard.writeText`) y respaldo seleccionando el texto, más accesos directos a ChatGPT y Gemini.
- **Diseño adaptable y accesible:** Dos columnas en escritorio con resultado fijo, una columna en móvil sin desbordamiento desde `360px`, alto contraste y soporte para teclado y lectores de pantalla.

## Uso local

Abre `index.html` directamente en cualquier navegador moderno o inicia un servidor local estático:

```sh
python3 -m http.server 8080
```

## Publicación en GitHub (`atedian`) y GitHub Pages

Este repositorio está preparado para servirse directamente desde la raíz (`index.html` + `.nojekyll`) con **GitHub Pages**.

1. Cambia a la cuenta `atedian` (si usas `gh` CLI) o crea el repositorio en GitHub bajo `https://github.com/atedian`:

   ```sh
   gh auth switch --user atedian
   gh repo create atedian/gta6 --public --source=. --remote=origin --push
   ```

   *(Si prefieres crear el repositorio desde la web de GitHub, enlaza el remoto manualmente:)*

   ```sh
   git remote add origin https://github.com/atedian/<nombre-repo>.git
   git push -u origin main
   ```

2. Activa **GitHub Pages** para usar la web directamente desde el repositorio:
   - En GitHub, entra en **Settings → Pages**.
   - En **Build and deployment → Source**, elige **Deploy from a branch**.
   - Selecciona la rama **`main`** y la carpeta **`/ (root)`**, y pulsa **Save**.
   - En ~1 minuto la aplicación estará disponible en `https://atedian.github.io/<nombre-repo>/`.
