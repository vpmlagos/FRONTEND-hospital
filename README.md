# Proyecto Hospital Privado

El repositorio contiene la página web desarrollada utilizando HTML, CSS, Bootstrap y el preprocesador SASS.

## Instrucciones de Ejecución

Para visualizar el proyecto, simplemente abre el archivo `index.html` en tu navegador.

### Ejecución en Modo Desarrollo

Para ejecutar el proyecto en modo desarrollo, sigue estos pasos:

1. **Instalar SASS**:

   Si no tienes SASS instalado, primero necesitas instalarlo globalmente usando el siguiente comando:

   ```bash
   npm install -g sass

   sass src/sass/main.scss dist/style.css

 ```


/Proyecto-Hospital-Privado
├── index.html
├── equipo.html
├── contacto.html
├── package-lock.json
├── package.json
├── README.md
├── node_modules
│   └── ...
├── src
│   ├── img
│   │   └── ...
│   ├── sass
│   │   └── abstracts
│   │          └──_mixins.scss
│   │          └──_variables.scss
│   │   └── base
│   │          └──_reset.scss
│   │   └── components
│   │          └──_buttons.scss
│   │          └──_cards.scss
│   │          └──_carousel.scss
│   │   └── layout
│   │          └──_navbar.scss
│   │   └── pages
│   │          └──_home.scss
│   │   └── themes
│   │          └──_dark.scss
│   │   └── vendors
│   │          └──_bootstrap.scss
│   │   └── main.scss
│   ├── style
│   │   └── homeStyle.css
├── dist
│   └── style.css
│   └── style.css.map
