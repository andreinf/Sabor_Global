# Sabor_Global#

Este proyecto corresponde al Ejercicio 6 del Día 5 del bootcamp de desarrollo web CSS Responsive. Aplicando todos los conocimientos adquiridos sobre **tipografía fluida**, **unidades viewport**, **imágenes responsive**, **clamp()**, **performance web** y **accesibilidad**.


## Conocimientos Aplicados

### Tipografía Fluida
- Uso de `clamp()` para escalado inteligente de fuentes.
- Adaptación de títulos y subtítulos con unidades `vw`, `vh`.
- Sistema jerárquico que se mantiene en todos los tamaños de pantalla.

### Imágenes Responsive
- Implementación de `<picture>` con diferentes resoluciones (`srcset`).
- Uso de `aspect-ratio` para mantener proporciones.
- Carga optimizada con `loading="lazy"` y `decoding="async"`.

### Layout Flexible
- Diseño responsive con `CSS Grid` y media queries.
- Reorganización automática del contenido según el tamaño del viewport.
- `background-image` en secciones destacadas con cobertura adaptable.

### Buenas Prácticas
- Colores definidos por variables CSS (`:root`) para escalabilidad.
- Uso de `rem`, `vw`, `clamp()` en lugar de `px` fijos.
- Performance optimizada con espacios reservados para imágenes.


## Responsividad

El sitio fue probado y se adapta correctamente a los siguientes rangos:

- **Smartphones pequeños** (320px - 480px)
- **Tablets** (768px - 1024px)
- **Laptops y monitores 1080p**
- **Pantallas ultra-wide (hasta 2560px)**