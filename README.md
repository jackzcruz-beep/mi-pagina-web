<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://ai.google.dev/static/site-assets/images/share-ais-513315318.png" />
</div>

# Run and deploy your AI Studio app

This contains everything you need to run your app locally.

View your app in AI Studio: https://ai.studio/apps/b8cc7a9c-bba4-44c5-be13-612cf86e9671

## Run Locally

**Prerequisites:**  Node.js


1. Install dependencies:
   `npm install`
2. Set the `GEMINI_API_KEY` in [.env.local](.env.local) to your Gemini API key
3. Run the app:
   `npm run dev`

## Rediseño NexusMóvil — octubre 2026

Esta versión adapta la interfaz a la identidad visual de NexusMóvil y prioriza una compra directa:

- Logo oficial integrado desde `src/assets/images/nexus-logo.png`.
- Hero más amplio, limpio y orientado a productos reales.
- Se eliminó la presentación de celulares como categoría o propuesta comercial.
- Categorías principales: In-Ear/KZ, periféricos gamer, adaptadores/DAC, componentes PC y audio/accesorios.
- Nueva sección de categorías y ruta de compra rápida.
- CTA de producto orientado a `Comprar` y WhatsApp.
- Paleta visual centrada en azul noche, cyan y violeta como acento.
- Tipografía y espaciado más limpios, con menos ruido visual.
- El carrusel tiene protección cuando no existen slides.

### Próxima fase recomendada para producción

El proyecto todavía usa `localStorage` para buena parte de productos, pedidos, usuarios y configuración. Para una tienda multiusuario real se recomienda migrar esos datos a una API/backend y una base de datos, además de mover la autenticación administrativa fuera del frontend.
