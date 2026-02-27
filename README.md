# Perfil Personal — Jhonn Marca

Landing page de presentación personal construida con **HTML**, **CSS** y **JavaScript**, pensada para usarse como carta de presentación / portafolio simple y para publicarse en **GitHub Pages**.

## Contenido

- `index.html`: página principal lista para GitHub Pages.
- `Carta de Presentacion.html`: versión original del documento (opcional, puedes dejarla o eliminarla cuando ya uses solo `index.html`).
- `styles.css`: estilos globales, diseño responsive, modo claro/oscuro, animaciones y layout de todas las secciones.
- `script.js`: comportamiento del sitio (scroll reveal, menú móvil, modo oscuro/claro, partículas del fondo, etc.).
- `img/Jhonn.jpeg`: fotografía de perfil (asegúrate de subir esta carpeta `img` al repositorio).

## Cómo usar este proyecto

1. Abre el archivo `index.html` en el navegador para ver la carta de presentación.
2. Edita los textos directamente en `index.html` si quieres cambiar datos personales, formación, pasatiempos o motivación.
3. Ajusta colores, tamaños o animaciones desde `styles.css`.
4. Si quieres modificar interacciones (menú, partículas, modo oscuro/claro), hazlo en `script.js`.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `perfil-jhonn-marca`).
2. Copia estos archivos al repositorio:
   - `index.html`
   - `styles.css`
   - `script.js`
   - Carpeta `img` con `Jhonn.jpeg`
   - (Opcional) `Carta de Presentacion.html`
3. Haz commit y push a la rama principal (`main` o `master`).
4. En GitHub, ve a **Settings → Pages**:
   - En **Source**, elige **Deploy from a branch**.
   - Selecciona la rama (`main` o `master`) y la carpeta `/root`.
5. Guarda los cambios. GitHub generará una URL del tipo:

   `https://tu-usuario.github.io/tu-repositorio/`

6. Abre esa URL y deberías ver tu perfil personal con modo claro/oscuro y partículas funcionando.

## Personalización rápida

- **Título de la pestaña**: edita la etiqueta `<title>` en `index.html`.
- **Foto de perfil**: reemplaza `img/Jhonn.jpeg` por otra imagen con el mismo nombre o cambia la ruta en la etiqueta `<img>`.
- **Colores de tema**: modifica las variables CSS en `styles.css` dentro de `:root` y `[data-theme="light"]`.

Este proyecto no requiere ninguna dependencia ni build: es estático y funciona solo con un navegador.

