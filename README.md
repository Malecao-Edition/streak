# STREAK

App móvil de rachas, lista para publicar en GitHub Pages.

## Publicar
1. Crea un repositorio nuevo en GitHub.
2. Sube `index.html`, `manifest.webmanifest` y `sw.js` a la raíz.
3. Ve a **Settings → Pages**.
4. En **Deploy from a branch**, selecciona `main` y `/ (root)`.
5. Guarda y abre el enlace de GitHub Pages.

## Funciones
- Crear, editar y eliminar metas.
- Rachas y calendario.
- Estadísticas e hitos.
- Nombre personalizable.
- Sonido y vibración.
- Días de descanso configurables.
- Inicio de semana configurable.
- Recordatorio general configurable.
- Datos persistidos con LocalStorage.
- PWA básica para instalación en dispositivos compatibles.

> Los recordatorios horarios se guardan como preferencia. Las notificaciones automáticas en segundo plano requieren APIs/permisos adicionales y dependen del navegador/plataforma.
