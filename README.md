# noelialruiz.github.io

Mi sitio personal: proyectos de datos, experiencia, formación y certificados.

**Ver el sitio:** https://noelialruiz.github.io

| Archivo | Qué es |
|---|---|
| `index.html` | La página completa en español e inglés (HTML, CSS y el botón ES/EN en un solo archivo) |
| `images/` | Mi foto, las imágenes de las tarjetas de proyecto y `tarjeta-compartir.jpg` (la vista previa en LinkedIn y WhatsApp) |
| `files/cv-noelia-leon-ruiz.pdf` | Mi CV en español |
| `files/cv-noelia-leon-ruiz-en.pdf` | Mi CV en inglés |
| `_fuentes/` | Las fuentes de los CV (`cv.html`, `cv-en.html`) y de la tarjeta para compartir (`tarjeta.html`); GitHub Pages no publica las carpetas que empiezan con `_` |

## Cómo actualizarlo

- **Nuevo proyecto:** copiar un bloque `<article class="proyecto">` de `index.html`, cambiar título, pregunta, resultado, imagen y enlaces, y ponerlo primero si es el mejor. Cada texto va dos veces: `<span lang="es">` y `<span lang="en">`.
- **CV:** editar `_fuentes/cv.html` o `_fuentes/cv-en.html` y volver a imprimirlo a PDF con Edge (`--print-to-pdf`) en `files/`.
- **Colores:** están al inicio del `<style>` de `index.html`, en `:root` (modo claro) y en `@media (prefers-color-scheme: dark)` (modo oscuro).

El diseño de una sola página se inspira en el sitio de [Jon Barron](https://jonbarron.info).
