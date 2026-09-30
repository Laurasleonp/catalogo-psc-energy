PSC ENERGY - CATALOGO INTERACTIVO 2026

CONTENIDO
- index.html: catálogo interactivo.
- manifest.json: instalación como aplicación web.
- service-worker.js: caché para uso offline.
- assets/: 10 páginas del catálogo e iconos.

PRUEBA EN COMPUTADOR
Para probar la PWA/offline correctamente debe servirse por HTTP/HTTPS; abrir index.html directamente permite revisar la navegación, pero los navegadores no activan Service Worker desde file://.

PUBLICACIÓN
Subir el contenido completo de esta carpeta a un hosting estático HTTPS (por ejemplo GitHub Pages). No se requiere dominio propio.

ANDROID
1. Abrir la URL publicada en Chrome con internet.
2. Menú > Instalar app / Agregar a pantalla principal.
3. Abrir una vez y esperar a que cargue.
4. Luego puede usarse sin conexión desde el icono instalado.

iPHONE / iPAD
1. Abrir la URL publicada en Safari con internet.
2. Compartir > Agregar a pantalla de inicio.
3. Abrir una vez desde el icono y dejar cargar el catálogo.
4. Luego puede usarse sin conexión desde ese icono.

ONLINE
Cualquier visitante puede abrir la misma URL o escanear un QR sin instalar nada.
