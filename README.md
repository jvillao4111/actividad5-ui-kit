# UI Kit - Sistema de Control de Rescates y Adopciones Animales

Librería de componentes visuales reutilizables desarrollada en **CSS3 puro** (sin frameworks) para garantizar consistencia visual y accesibilidad.

## Variables Globales (`:root`)
Las variables de diseño están definidas al inicio de `style.css`:
- `--color-primary`: `#2563eb` (Acciones principales)
- `--color-secondary`: `#475569` (Acciones secundarias)
- `--color-danger`: `#dc2626` (Alertas críticas / peligro)
- `--color-warning`: `#d97706` (Advertencias / urgencia media)
- `--color-success`: `#16a34a` (Estados favorables / disponible)

## Guía de Uso de Componentes

1. **Botones:** Combinar la clase base `.btn` con la variante deseada (`.btn-primary`, `.btn-secondary`, `.btn-danger`).
2. **Formularios:** Agrupar cada campo con `.form-group`, usar `.form-label` para la etiqueta y `.form-control` en `<input>` o `<select>`.
3. **Badges (Alertas):** Usar `.badge` junto a `.badge-high`, `.badge-medium` o `.badge-low`.
4. **Tarjetas (Cards):** Estructurar mediante `.card`, subdividiendo en `.card-header`, `.card-body` y `.card-footer`.
