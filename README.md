# Nails Glez 💅

Página web de [@nails.glez21](https://www.instagram.com/nails.glez21).

Es un sitio estático (un solo `index.html`), listo para publicarse gratis en Vercel.

## Cómo editar

- **WhatsApp, ubicación y horario:** en `index.html`, busca `const NEGOCIO` y cambia los valores.
- **Fotos:** ahora hay ilustraciones de muestra (`img/hero-1.svg`, `img/hero-2.svg` y `img/1.svg` a `img/8.svg`).
  Para poner tus fotos reales, súbelas a `img/` (ej. `1.jpg`) y en `index.html` cambia `img/1.svg` por `img/1.jpg`.
- **Precios:** busca `class="price"` en cada servicio.
- **Colores:** al inicio del `<style>`, en `:root`.

## Publicar en Vercel

1. Entra a https://vercel.com y accede con GitHub.
2. **Add New → Project**, elige este repositorio y da **Deploy** (no hay que configurar nada).
3. Tu página queda en `https://<nombre>.vercel.app`. Cada cambio que subas a GitHub se publica solo.
