# MurciaGram

Galería de inspiración visual (estilo Pinterest) con el patrimonio de la Región de Murcia.
Práctica de CSS3: HTML semántico, Mobile-First, Grid, Flexbox, `<picture>` y `@media print`.

## Estructura

```
index.html
css/styles.css
assets/raw/   <- fotos originales (ej. lorca.jpg)
assets/img/   <- versiones optimizadas (lorca-mobile.jpg, lorca-desktop.jpg)
.vscode/tasks.json
```

## Automatización de imágenes

1. Instala [ImageMagick](https://imagemagick.org).
2. Pon tus fotos originales en `assets/raw/` (nombres: `lorca.jpg`, `cartagena.jpg`, `mazarron.jpg`, `murcia.jpg`).
3. En VSCode: `Ctrl+Shift+P` → **Tasks: Run Task** → **Optimizar imágenes (ImageMagick)**.

Genera en `assets/img/` una versión de 400px (`-mobile`) y otra de 1000px (`-desktop`) de cada foto.
En Windows, ejecuta la tarea desde una terminal Git Bash.

## Despliegue

Publicado con GitHub Pages: _añade aquí tu enlace_.
