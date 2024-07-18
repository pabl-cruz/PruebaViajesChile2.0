# Prueba Viajes Chile 2.0 

Repositorio de prueba final del módulo 3 para Bootcamp de Programación Front-End Trainee de Desafío Latam. Contiene los archivos de la página.

## Lenguajes y frameworks utilizados

- HTML 5
- CSS 3
- SCSS con Sass
- Bootstrap 5.3.3 + Popper (Requieren instalación)

## Elementos para estilo utilizados

- Google Fonts, para uso de fuente tipográfica [Open Sans](https://fonts.google.com/specimen/OpenSans) en variantes:
  - Regular
  - Bold
- Font Awesome 6.5.2 para iconos:
  - **fa-solid fa-plane-up**
  - **fa-solid fa-phone**
  - **fa-solid fa-envelope**
  - **fa-brands fa-linkedin**
  - **fa-brands fa-instagram**
 
## Caracteristicas

- Incluye un carrusel de Bootstrap con titulos y subtitulos en header.
- Sección de Quienes Somos con dos columnas de imagen y texto, y que se oculta en vista de dispositivos pequeños.
- Sección Destacados con 4 cards de Bootstrap con imagen, texto y footer de precio en cada una, que cambia de formato en vista de dispositivos pequeños.
- Sección de Testimonios con método CSS BEM para sus clases y estilos (Bloque-Elemento-Modificador)
- Footer con dos columnas, una con un formulario de contacto con tooltips, alerta al enviar datos y modal en términos y condiciones; y otro con datos de contacto y redes sociales.

## Estructura de archivos

```
.
├───assets/
│   ├───css/
│   │   ├───main.css
│   │   └───main.css.map
│   ├───img/
│   │   ├───card1.jpg
│   │   ├───card2.jpg
│   │   ├───card3.jpg
│   │   ├───card4.jpg
│   │   ├───carousel1.jpg
│   │   ├───carousel2.jpg
│   │   ├───carousel3.jpg
│   │   ├───quienes-somos.jpg
│   │   ├───testimonio1.jpg
│   │   ├───testimonio2.jpg
│   │   ├───testimonio3.jpg
│   │   └───viajes.svg
│   ├───js/
│   │   └───scripts.js
│   └───scss/
│       ├───abstracts/
│       │   ├───_mixins.scss
│       │   └───_variables.scss
│       ├───base/
│       │   ├───_reset.scss
│       │   └───_typography.scss
│       ├───components/
│       │   ├───_card.scss
│       │   ├───_carousel.scss
│       │   ├───_contactlist.scss
│       │   ├───_navbar.scss
│       │   ├───_quienimg.scss
│       │   └───_testimony.scss
│       ├───layout/
│       │   └───_main.scss
│       ├───pages/
│       ├───themes/
│       │   └───_theme.scss
│       ├───vendor/
│       │   └───_bootstrap.scss
│       └───main.scss
├───index.html
├───package-lock.json
├───package.json
└───README.md

```
## Instalacion

1. Clona el repositorio:
```
git clone git@github.com:pabl-cruz/PruebaViajesChile2.0.git
```
2. Navega hacia el directorio del proyecto con terminal
```
cd PruebaViajesChile
```
3. en la terminal, instala las dependencias de Bootstrap en la carpeta del proyecto (se requiere npm).
```
npm i bootstrap@5.3.3
```
4. Abre **index.html** en tu navegador para ver el sitio web.
