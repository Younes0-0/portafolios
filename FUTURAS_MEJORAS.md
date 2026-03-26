# Futuras mejoras del portafolio

## 1) Navegación y estructura
- Crear la página `/contacto` (ahora mismo está enlazada pero no existe), con formulario, estado de envío y alternativa por email/LinkedIn.
- Añadir estado activo al menú para que el usuario sepa en qué sección está.
- Incluir una página `404` personalizada con enlaces de retorno a Inicio y Proyectos.

## 2) Contenido y marca personal
- Reescribir textos con propuesta de valor más concreta (qué problema resuelves y para quién).
- Añadir casos de estudio de proyectos: reto, stack, decisiones técnicas, resultado y métricas.
- Publicar versión bilingüe ES/EN para ampliar alcance profesional.
- Incorporar CV descargable y enlaces visibles a GitHub/LinkedIn.

## 3) UX/UI
- Mejorar responsive en móvil (navbar con menú hamburguesa y espaciado en cards).
- Añadir modo oscuro con preferencia guardada.
- Sustituir placeholders (`href="#"`) por rutas reales o botones deshabilitados con etiqueta “Próximamente”.
- Añadir microinteracciones suaves (focus, hover, transiciones coherentes).

## 4) Accesibilidad
- Revisar contraste de color y estados de foco visibles en todos los enlaces y botones.
- Usar landmarks semánticos y jerarquía de encabezados consistente.
- Incluir `aria-label` en iconos/enlaces que solo usan emoji.
- Probar navegación completa con teclado y lector de pantalla.

## 5) SEO y descubrimiento
- Definir metadatos por página (`title`, `description`, Open Graph y Twitter cards).
- Añadir `sitemap.xml` y `robots.txt`.
- Implementar datos estructurados (`Person`, `WebSite`, `CreativeWork/Project`).
- Optimizar textos para búsquedas locales y de nicho (autoescuelas, automatización, formación CAP).

## 6) Rendimiento y calidad técnica
- Comprimir imágenes y usar formatos modernos (`webp/avif`) con tamaños responsivos.
- Configurar auditorías con Lighthouse y objetivos de Core Web Vitals.
- Añadir linting/formatting (ESLint + Prettier) y scripts de validación previos al deploy.
- Subir cobertura de tests (p. ej. smoke tests de rutas y comprobaciones de enlaces rotos).

## 7) Conversión y contacto
- Añadir CTA principal visible en todas las páginas (“Trabajemos juntos” / “Solicitar demo”).
- Preparar formulario de contacto con validación y protección anti-spam.
- Integrar analítica ligera (Plausible/Umami) para medir clics, scroll y conversiones.

## 8) Mantenimiento y despliegue
- Reemplazar el README base de Astro por documentación del proyecto real.
- Configurar CI (GitHub Actions) para build/check en cada push y pull request.
- Definir versión de Node y gestor de paquetes recomendado para evitar diferencias locales.
- Añadir checklist de publicación para mantener consistencia en cada actualización.

---

## Prioridad recomendada (rápida)
1. Crear `/contacto` + corregir enlaces rotos.
2. Mejorar metadatos SEO por página.
3. Reescribir README/documentación real del proyecto.
4. Añadir modo oscuro y mejoras de accesibilidad.
5. Configurar CI con `astro check` + `astro build`.
