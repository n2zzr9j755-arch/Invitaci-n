# Invitación · Primera Comunión de Mau y Bautizo de Marcel

Página web de la invitación (29 de noviembre). Se publica gratis con GitHub Pages.

## Qué es cada archivo
- `index.html` — la página completa. Se llama así a propósito: es el archivo que GitHub Pages muestra primero.
- `video.mp4` — el video de apertura.
- `poster.jpg` — imagen que se ve mientras carga el video.
- `preview.jpg` — imagen que aparece en la vista previa del enlace en WhatsApp.

## Cómo publicarla (sin usar la terminal)
1. Entra a github.com e inicia sesión (o crea tu cuenta gratis).
2. Toca **New repository**. Nombre sugerido: `invitacion`. Déjalo en **Public** (Pages gratis lo requiere) y crea el repositorio.
3. Toca **uploading an existing file**. Sube los 4 archivos sueltos (`index.html`, `video.mp4`, `poster.jpg`, `preview.jpg`), no una carpeta. Baja y toca **Commit changes**.
4. Ve a **Settings → Pages**. En *Source* elige **Deploy from a branch**, rama **main**, carpeta **/(root)**, y toca **Save**.
5. Espera 1 o 2 minutos. Tu enlace será: `https://TU-USUARIO.github.io/invitacion/`

## Vista previa en WhatsApp
En `index.html` hay una línea con `TU-USUARIO` y `TU-REPO`. Ábrela con el lápiz de GitHub (Edit) y cámbialos por tu usuario y el nombre del repositorio. Después guarda con **Commit changes**. WhatsApp guarda la vista previa en memoria, así que si la cambias después de enviarla puede tardar en actualizarse.

## Antes de enviarla
- Ábrela desde otro teléfono y revisa el video, los botones de mapas y las mesas de regalo.
- Haz una confirmación de prueba: debe abrir WhatsApp con el mensaje escrito hacia tu número.

## Para cambiar el número de WhatsApp
Busca en `index.html` la línea `const WA="..."`. Va con lada de país y sin signos (México: 52 + 10 dígitos).

> Nota: en un repositorio público cualquiera puede ver el código, incluido ese número. Es el mismo que ya verán tus invitados al confirmar.
