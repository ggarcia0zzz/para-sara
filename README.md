# Página de cumpleaños para Sara 🤍

Todo listo para subir a GitHub y compartir el link por QR.

## 📁 Qué hay aquí

```
index.html        ← la página completa (HTML + CSS + JS en un solo archivo)
assets/
  foto1.jpg ... foto6.jpg   ← tus 6 fotos, ya optimizadas para web
  video1.mp4                ← tu video
```

## 🎵 Sobre la música

La canción **"Halley's Comet" de Billie Eilish** está integrada como un
reproductor de Spotify embebido directo en la página (justo debajo de la
carta). No es un archivo de audio dentro del repo — se carga desde Spotify,
que sí tiene los derechos para reproducirla. Esto evita cualquier problema
de derechos de autor en un repositorio público de GitHub.

Una sola limitación: por las reglas del propio reproductor de Spotify, no
se puede forzar que arranque automáticamente justo en el minuto 1:43 ni que
suene sola sin que Sara toque play (Spotify no permite eso desde fuera de su
plataforma). Por eso dejé una nota chiquita arriba del reproductor:
*"dale play y arrastra a 1:43"* — son dos toques y listo, nada complicado.

Si en algún momento quieres una versión que sí suene automática desde el
segundo exacto sin que ella tenga que tocar nada, la única forma real de
lograrlo es con un archivo de audio propio (por ejemplo, si tú mismo grabas
o compras la pista), alojado en el repo. Si llegas a tener esa pista, dime
y te actualizo el código en un momento.

## 🚀 Cómo subirlo a GitHub Pages (para tener el link)

1. Ve a [github.com](https://github.com) e inicia sesión (o crea una cuenta gratis).
2. Arriba a la derecha, click en **+** → **New repository**.
3. Ponle un nombre, por ejemplo `para-sara` (puede ser cualquier nombre).
4. Déjalo en **Public** y crea el repositorio (no marques ningún checkbox extra).
5. En la página del repo recién creado, click en **uploading an existing file**
   (o el botón **Add file → Upload files**).
6. Arrastra **todo el contenido** de esta carpeta: `index.html` y la carpeta
   `assets` completa (con las 6 fotos, el video y, si ya lo tienes, `song.mp3`).
   - Importante: que `assets` quede como carpeta dentro del repo, no sueltos
     los archivos.
7. Click en **Commit changes**.
8. Ve a la pestaña **Settings** del repositorio → en el menú izquierdo
   **Pages**.
9. En "Build and deployment" → **Source**, selecciona **Deploy from a branch**.
10. En "Branch" selecciona **main** y la carpeta **/ (root)** → **Save**.
11. Espera 1-2 minutos y recarga la página. Arriba te va a aparecer un link
    así: `https://tu-usuario.github.io/para-sara/`
12. ¡Ese es el link que va en tu QR! 🎉

## 🔍 Antes de generar el QR

Abre el link en tu celular y revisa:
- Que las fotos carguen bien y en el orden correcto.
- Que el video se reproduzca al tocarlo.
- Que el reproductor de Spotify cargue y suene al darle play.
- Pruébalo con el wifi apagado (datos móviles) para asegurarte que carga rápido.

Para generar el QR puedes usar cualquier generador gratuito, por ejemplo
qr-code-generator.com, pegando el link de GitHub Pages.

## ✏️ Si quieres cambiar algo

Todo el texto y las rutas de las imágenes están directo en `index.html`,
buscando el texto correspondiente. Si quieres que te ayude a ajustar algo
(colores, textos, agregar otra foto), dime y lo hacemos.
