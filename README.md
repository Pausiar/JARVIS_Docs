# JARVIS_Docs

Documentación web estática para J.A.R.V.I.S., publicada como un sitio HTML/CSS/JavaScript ligero.

## Stack detectado

- HTML estático en la raíz del repositorio.
- CSS global en `style.css`.
- JavaScript vanilla para búsqueda y navegación lateral en `script.js`.
- Sistema de iconos SVG en `icons.svg`, consumido mediante `<svg><use href="icons.svg#icon-name"></use></svg>`.

## Desarrollo local

No requiere dependencias de Node ni proceso de build.

```bash
python3 -m http.server 8000
```

Después abre `http://127.0.0.1:8000/index.html`.

## Despliegue esperado

El sitio puede servirse directamente desde GitHub Pages. Para este repositorio, la URL esperada es:

```text
https://pausiar.github.io/JARVIS_Docs/
```
