# Entregable 10 — Proyecto Final | Milton Developer

## Descripción

Proyecto final del curso de Desarrollo Web Full Stack, correspondiente a la Comisión 91305 de Coderhouse.

El proyecto consiste en un sitio web estático de 5 páginas desarrollado para presentar el perfil profesional, habilidades, proyectos y servicios de Milton Developer.

El sitio integra HTML5 semántico, SCSS, Bootstrap, diseño responsive, animaciones, SEO básico y despliegue en un servidor público.

## Tecnologías utilizadas

- HTML5
- SCSS / Sass
- Bootstrap 5.3
- JavaScript
- AOS (Animate On Scroll)
- Font Awesome
- Flexbox
- CSS Grid
- Git
- GitHub
- Vercel / Netlify

## Páginas del sitio

- Inicio
- Sobre mí
- Proyectos
- Habilidades
- Contacto

## Características

- Estructura semántica HTML5.
- SEO On-Page básico.
- `title`, `description` y `keywords` únicos en cada página.
- Atributos `alt` en las imágenes.
- Navbar responsive de Bootstrap.
- Menú hamburguesa funcional en dispositivos móviles.
- Arquitectura SCSS mediante partials.
- Uso de variables, nesting, mixins con parámetros y `@extend`.
- CSS compilado desde Sass.
- Diseño responsive para diferentes tamaños de pantalla.
- Animaciones nativas mediante SCSS.
- Animaciones mediante la librería AOS.
- Iconos mediante Font Awesome.
- Organización de recursos multimedia dentro de `assets/`.

## Estructura del proyecto

```text
Entregable10/
│
├── assets/
│   └── img/
│
├── pages/
│   ├── contacto.html
│   ├── habilidades.html
│   ├── proyectos.html
│   └── sobre-mi.html
│
├── scss/
│   ├── base/
│   ├── components/
│   ├── layout/
│   ├── utilities/
│   └── main.scss
│
├── styles/
│   ├── styles.css
│   ├── styles.css.map
│   └── styles-original.css
│
├── index.html
├── package.json
├── package-lock.json
├── .gitignore
└── README.md

Compilación de SCSS

El proyecto utiliza Sass para compilar los archivos SCSS en CSS.

Para compilar los estilos:

npm run sass

El archivo principal scss/main.scss utiliza @use para importar los diferentes partials del proyecto.

Repositorio

Repositorio público en GitHub:

https://github.com/Wildcode7/91305_Coder_Clase_entregable10

## Autor

Milton Cesar Galvez Zapata

Estudiante de Desarrollo Web Full Stack.

Proyecto desarrollado como parte del proceso de formación en desarrollo web.




