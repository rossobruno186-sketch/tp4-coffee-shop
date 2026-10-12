# Landing Page - Coffea ☕

Landing page estática de una sola página para la cafetería ficticia Coffea, desarrollada para la materia Diseño UX-UI (2026) en FCyT, Sede Concepción del Uruguay.

## 📁 Estructura del Proyecto

- `index.html`: Página principal de la landing.
- `404.html`: Página de error personalizada.
- `css/`: Hojas de estilo organizadas por capas lógicas (tokens, base, layout, components, utilities).
- `assets/`: Imágenes (AVIF/WebP), iconos (SVG optimizados) y fuentes tipográficas.
- `netlify.toml`: Configuración de despliegue continuo y headers HTTP para Netlify.

## ⚙️ Convenciones Técnicas

- **Stack:** HTML5 semántico y CSS3 puro. **Cero JavaScript**.
- **Arquitectura CSS:** Uso de `@layer` para el control de especificidad y cascada sin utilizar `!important`.
- **Nomenclatura:** BEM (Block, Element, Modifier) estricto (ej. `.product-card`, `.product-card__title`).
- **Responsive:** Enfoque *Mobile-first*. Estilos por defecto para base (360px) escalando hacia `md`, `lg` y `xl` (1920px).
- **Design Tokens:** Centralización de variables (Custom Properties) para colores, tipografías, espacios y radios en `tokens.css`.
- **Accesibilidad:** Soporte 100% por teclado, contrastes WCAG AA, y uso de `:focus-visible`.
