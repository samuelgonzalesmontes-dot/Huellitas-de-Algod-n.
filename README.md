# Huellitas de Algodón — aplicación instalable (PWA)

Esta versión conserva la página original y corrige la instalación como aplicación en Android y iPhone.

## Publicar en GitHub Pages
1. Descomprime este ZIP.
2. Sube **todos los archivos que están dentro de `Emprendimiento Digital`** a la raíz de tu repositorio (incluidos `index.html`, `manifest.json`, `sw.js`, `icon-192.png` e `icon-512.png`).
3. En GitHub entra a **Settings → Pages** y publica desde la rama `main`, carpeta `/(root)`.
4. Espera a que GitHub Pages publique la dirección HTTPS.

## Instalar en Android
1. Abre el enlace publicado con Google Chrome.
2. Pulsa **📲 Instalar App** si aparece el aviso; también puedes abrir el menú ⋮ y elegir **Instalar aplicación** o **Instalar y crear acceso directo**.
3. Confirma. La aplicación aparecerá en el menú de aplicaciones y se abrirá en modo independiente.

## Instalar en iPhone
1. Abre el enlace publicado en **Safari** (no dentro de Instagram/WhatsApp).
2. Pulsa **Compartir**.
3. Elige **Añadir a pantalla de inicio** y confirma con **Añadir**.
4. Abre Huellitas desde el nuevo icono.

## Importante
- La instalación PWA necesita que la página esté publicada mediante HTTPS (GitHub Pages lo proporciona).
- En Android, Chrome puede mostrar un diálogo nativo de instalación. Si no lo muestra, el botón de la página explica cómo instalar desde el menú.
- En iPhone, iOS no ofrece el mismo aviso automático que Android: se instala desde Compartir → Añadir a pantalla de inicio.
- Esto crea una aplicación web instalable que se abre sin la barra del navegador; no genera un APK ni una IPA nativa.
