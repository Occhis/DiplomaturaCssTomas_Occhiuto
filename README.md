# DiplomaturaCoder
# Occhiwebs - Portafolio Profesional (Preentrega 6)

Este repositorio contiene el desarrollo de un sitio web estático multipágina implementando HTML5, Bootstrap 5 y una **arquitectura SCSS modular**, basado en los contenidos y la práctica de la diplomatura de desarrollo web. 

## Descripción del Proyecto
El proyecto fue realizado integrando los conocimientos fundamentales adquiridos en la diplomatura (maquetación semántica, modelos de caja y selectores) junto con técnicas avanzadas de organización de estilos. En esta etapa, el proyecto ha sido refactorizado por completo para migrar de CSS plano a un sistema profesional de partials y variables utilizando Sass (`@use`).

---

## 📂 Estructura de Arquitectura SCSS

El código de estilos se organiza bajo una estructura limpia y modular dentro del directorio `scss/`:

```text
scss/
├── main.scss              # Archivo maestro (único punto de entrada con directivas @use)
├── utilities/
│   ├── _variables.scss    # Variables globales (colores, fuentes, radios, sombras y focus)
│   └── _mixins.scss       # Mixins reutilizables (ej. flex-center)
├── base/
│   ├── _tipografia.scss   # Estilos base y tipográficos globales
│   └── _base.scss         # Estilos globales de etiquetas y accesibilidad
├── layout/
│   ├── _header.scss       # Estilos de la cabecera
│   ├── _nav.scss          # Barra de navegación principal y toggler
│   └── _footer.scss       # Pie de página
└── components/
    ├── _buttons.scss      # Botones personalizados con mixins de centrado
    ├── _cards.scss        # Tarjetas y contenedores de sección
    ├── _forms.scss        # Formularios, inputs y selectores específicos
    ├── _tables.scss       # Tablas de servicios y precios
    ├── _carousel.scss     # Carrusel adaptativo
    └── _media.scss        # Contenedores multimedia (video e iframe)

## Tecnologías Utilizadas
* **HTML5**: Estructura semántica de las páginas (`header`, `nav`, `main`, `section`, `article`, `footer`).
* **CSS3**: Estilización visual, Flexbox, CSS Grid, tipografías externas y pseudoclases interactivas (`:hover`, `:focus`, `:active`).
* **Bootstrap 5.3 (CDN)**: Navbar responsivo, Carousel, Cards y sistema de grillas.
* **Control de Versiones**: Git / GitHub.