# GTA Intelligence — Leonida Files (v2)

PWA estática en español, diseñada para GitHub Pages. Incluye una landing editorial inspirada en el ambiente de Vice City, buscador y filtros de fichas, aportaciones locales, animaciones CSS, manifest y service worker.

## Publicar en GitHub Pages
1. Descomprime el ZIP.
2. Sube el contenido de esta carpeta a la raíz del repositorio. `index.html`, `manifest.json`, `sw.js` e `icon.svg` deben quedar en la raíz.
3. En GitHub abre Settings → Pages.
4. En Build and deployment selecciona Deploy from a branch, branch `main`, folder `/(root)` y Save.
5. Espera a que termine el deployment y abre la URL que GitHub Pages muestra.

## Limitaciones de esta demo
- Las imágenes de ambiente se cargan desde Unsplash y requieren conexión a internet.
- Las fichas iniciales son resúmenes editoriales de información oficial y ejemplos claramente etiquetados; no son una base de datos de secretos verificados.
- Los formularios añaden fichas solo a la vista actual; no sincronizan entre usuarios ni se guardan de forma permanente.
- Para perfiles, comentarios y contenido compartido se debe integrar un backend (por ejemplo, Supabase) y moderación.
- Proyecto independiente, no afiliado a Rockstar Games. GTA VI y sus marcas pertenecen a sus titulares.
