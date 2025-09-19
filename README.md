# TechNova Solutions — Sitio para reto OSINT

Este repositorio contiene un sitio estático de ejemplo para usar en un reto de OSINT.
Incluye varias "pistas" típicas: emails, humans.txt, /.well-known/security.txt, metadatos HTML, sitemap y robots.txt.

## Estructura
- `index.html`, `about.html`, `careers.html`, `blog/lanzamiento.html`
- `assets/logo.svg`
- `humans.txt`
- `/.well-known/security.txt`
- `robots.txt`, `sitemap.xml`
- `.nojekyll` (necesario para servir `.well-known` en GitHub Pages)

## Publicar en GitHub Pages
1. Crea un repositorio público, por ejemplo `technova-sec`.
2. Sube todos los archivos de esta carpeta al repositorio (incluida la carpeta `.well-known/`).
3. En *Settings → Pages* selecciona:
   - **Branch:** `main`
   - **Folder:** `/ (root)`
4. Guarda y espera a que se despliegue.
5. (Opcional) Para un dominio personalizado (`www.technova-sec.com`), configura un registro CNAME
   apuntando a tu dominio de GitHub Pages y crea un archivo `CNAME` en la raíz con `www.technova-sec.com`.

## Indexación y búsqueda
- Añade el repo a Google Search Console para acelerar la indexación, o enlaza al sitio desde redes sociales.
- El `sitemap.xml` y `robots.txt` ya están configurados para permitir el rastreo.

> **Aviso educativo:** Todo el contenido de personas/datos es ficticio.
