# Latin Wings — Sitio web

Página web de una sola pieza (HTML + CSS + JS) para el restaurante **Latin Wings**.
No requiere build, servidor, ni dependencias: es un sitio estático.

## Contenido
- `index.html` — la página completa (menú, ubicación, WhatsApp, descarga de carta).
- `latin-wings-logo.jpg` — logo de la marca, referenciado desde `index.html`.

## Cómo subirlo a GitHub

Desde esta carpeta, en tu terminal:

```bash
git init
git add .
git commit -m "Sitio web Latin Wings"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/TU-REPOSITORIO.git
git push -u origin main
```

Reemplaza `TU-USUARIO/TU-REPOSITORIO` por los datos de tu repositorio en GitHub
(créalo antes vacío, sin README, en https://github.com/new).

## Cómo publicarlo gratis (GitHub Pages)

1. En GitHub, entra al repositorio → **Settings** → **Pages**.
2. En "Build and deployment", elige **Deploy from a branch**.
3. Selecciona la rama `main` y la carpeta `/ (root)`.
4. Guarda. En 1-2 minutos tu sitio quedará disponible en:
   `https://TU-USUARIO.github.io/TU-REPOSITORIO/`

## Cómo verlo en tu computador antes de subirlo

Simplemente abre `index.html` haciendo doble clic, o arrástralo a tu navegador.
No necesita servidor.

## Pendientes antes de publicar

- Cambiar el número de WhatsApp de ejemplo (`+57 300 123 4567`) por el real
  (aparece 3 veces en `index.html`: botón flotante, sección de contacto y footer).
- Cambiar la dirección y el mapa de ejemplo por la ubicación real del local.
- Revisar los precios de la carta si cambian con el tiempo.
