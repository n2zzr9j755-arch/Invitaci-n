# Invitación · Primera Comunión de Mau y Bautizo de Marcel

Página web de la invitación (29 de noviembre). Se publica gratis con GitHub Pages.

## Qué es cada archivo
- `index.html` — la página completa. Se llama así a propósito: es el archivo que GitHub Pages muestra primero.
- `video.mp4` — video de apertura (con audio).
- `cierre.mp4` — video corto del final (sin audio).
- `poster.jpg` y `cierre.jpg` — imágenes que se ven mientras cargan los videos.
- `preview.jpg` — imagen para la vista previa del enlace en WhatsApp.

## Cómo publicarla (sin usar la terminal)
1. Entra a github.com e inicia sesión (o crea tu cuenta gratis).
2. Toca **New repository**. Nombre sugerido: `invitacion`. Déjalo en **Public** (Pages gratis lo requiere) y crea el repositorio.
3. Toca **uploading an existing file**. Sube los 6 archivos sueltos (`index.html`, `video.mp4`, `cierre.mp4`, `poster.jpg`, `cierre.jpg`, `preview.jpg`), no una carpeta. Baja y toca **Commit changes**.
4. Ve a **Settings → Pages**. En *Source* elige **Deploy from a branch**, rama **main**, carpeta **/(root)**, y toca **Save**.
5. Espera 1 o 2 minutos. Tu enlace será: `https://TU-USUARIO.github.io/invitacion/`

## Si ya habías subido la versión anterior
Entra al repositorio, toca **Add file → Upload files** y sube de nuevo los 6 archivos. GitHub reemplaza los que tengan el mismo nombre. Después de **Commit changes**, espera 1 o 2 minutos.

## Vista previa en WhatsApp
En `index.html` hay una línea con `TU-USUARIO` y `TU-REPO`. Ábrela con el lápiz de GitHub (Edit) y cámbialos por tu usuario y el nombre del repositorio. Guarda con **Commit changes**. WhatsApp guarda la vista previa en memoria, así que si la cambias después de enviarla puede tardar en actualizarse.

## Sonido
El navegador no permite reproducir sonido sin que la persona toque la pantalla. Por eso el video empieza sin sonido y el primer toque lo activa. Hay un botón fijo arriba a la derecha para silenciar o reactivar.

## Antes de enviarla
- Ábrela desde otro teléfono y revisa los dos videos, los botones de mapas y las mesas de regalo.
- Haz una confirmación de prueba: debe abrir WhatsApp con el mensaje escrito hacia tu número.

## Para cambiar el número de WhatsApp
Busca en `index.html` la línea `const WA="..."`. Va con lada de país y sin signos (México: 52 + 10 dígitos).

> Nota: en un repositorio público cualquiera puede ver el código, incluido ese número. Es el mismo que ya verán tus invitados al confirmar.
