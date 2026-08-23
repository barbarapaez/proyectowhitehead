# Proyecto PICIFFYH

Sitio del proyecto de investigación "El surgimiento de la metafisica procesual en la filosofia de la ciencia temprana de N. A. Whitehead", radicado en la Facultad de Filosofia y Humanidades, Universidad Nacional de Cordoba, Argentina.

## Sitio desplegado

(agregar el link una vez desplegado en Vercel o Netlify)

## Pendientes antes de publicar (2 cosas puntuales)

1. **Imagen de Whitehead**: descargar desde
   https://iiif.wellcomecollection.org/image/V0027330/full/800%2C/0/default.jpg
   y guardarla como `assets/images/alfred-north-whitehead-retrato.jpg`.
   Licencia: dominio publico (Public Domain Mark). Credito sugerido: "Alfred North Whitehead. Photograph. Wellcome Collection."

2. **Email de contacto**: en `pages/contacto.html` hay un email de ejemplo
   (`CAMBIAR-EMAIL-DEL-PROYECTO@ejemplo.com`) que hay que reemplazar por
   el email real del proyecto antes de publicar.

## Estructura

```
/
index.html
pages/
  proyecto.html
  equipo.html
  nuestro-trabajo.html
  contacto.html
scss/
  main.scss (solo imports)
  utilities/ (variables, mixins, placeholders)
  base/ (reset, tipografia, animaciones)
  layout/ (header, nav, footer, grid)
  components/ (cards, badges, buttons, media, pullquote, timeline)
styles/
  styles.css (compilado, no editar a mano)
assets/
  images/
```

## Compilar el SCSS

```
npm install --save-dev sass
npx sass scss/main.scss styles/styles.css
```

## Tecnologias

- HTML5 semantico
- SCSS (variables, mixins con parametros, extend/placeholders, nesting, partials)
- Bootstrap 5 (navbar responsiva)
- AOS (animaciones al hacer scroll)
- Google Fonts: Spectral, IBM Plex Sans, IBM Plex Mono
