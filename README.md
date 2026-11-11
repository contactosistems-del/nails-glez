# Nails Glez 💅

Página web de [@nails.glez21](https://www.instagram.com/nails.glez21).

Es un sitio estático (un solo `index.html`), listo para publicarse gratis en Vercel.

## Cómo editar

- **WhatsApp, ubicación y horario:** en `index.html`, busca `const NEGOCIO` y cambia los valores.
- **Fotos:** sube las imágenes a la carpeta `img/` con estos nombres:
  - `hero-1.jpg` y `hero-2.jpg` → fotos grandes de la portada
  - `1.jpg` a `8.jpg` → galería de trabajos
  Mientras no exista la foto, se ve un degradado de color.
- **Precios:** busca `class="price"` en cada servicio.
- **Colores:** al inicio del `<style>`, en `:root`.

## Publicar en Vercel

1. Entra a https://vercel.com y accede con GitHub.
2. **Add New → Project**, elige este repositorio y da **Deploy** (no hay que configurar nada).
3. Tu página queda en `https://<nombre>.vercel.app`. Cada cambio que subas a GitHub se publica solo.
