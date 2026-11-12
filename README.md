# Inbioma · Propuesta 09 B

Sitio estático (HTML, imágenes, logo y tipografía incluidos). Se adapta a celular, tablet y desktop.

## Subir a GitHub
1. Crea un repositorio nuevo en GitHub (por ejemplo `inbioma-09b`).
2. Sube **el contenido** de esta carpeta a la raíz del repositorio: `index.html`, `vercel.json`, `README.md` y las carpetas `assets/` y `js/`.
   (Que `index.html` quede en la raíz, no dentro de otra carpeta.)

## Publicar en Vercel
1. En vercel.com → **Add New… → Project** → importa el repositorio.
2. Framework Preset: **Other**. No necesita Build Command ni Output Directory.
3. **Deploy**.

## Nota
La página está marcada `noindex` (Google no la muestra en búsquedas) porque es una propuesta.
Para publicarla de verdad, borra la línea `<meta name="robots" content="noindex">` de `index.html` y el bloque `X-Robots-Tag` de `vercel.json`.
