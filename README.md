# Coffea - Landing Page (TP4)

Landing page estática y responsive desarrollada con HTML5 semántico y CSS3.

## Estructura del proyecto
- `index.html`: Maquetado principal con las 9 secciones.
- `404.html`: Página de error personalizada.
- `css/`: Hojas de estilo organizadas por capas (`@layer tokens, base, layout, components, utilities`).
- `assets/img/` y `assets/icons/`: Imágenes en formato AVIF con fallback JPG e íconos en SVG.
- `netlify.toml`: Configuración de despliegue, caché y seguridad.

## Convenciones
- Nomenclatura BEM para componentes.
- Variables CSS centralizadas en `css/tokens.css`.
- Diseño Mobile-First sin uso de JavaScript.

## Cómo levantar en local
Clonar el repositorio y abrir el archivo `index.html` directamente en el navegador o mediante la extensión Live Server de Visual Studio Code.