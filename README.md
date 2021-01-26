# Bienvenid@ a mi web personal

## Tabla de contenidos

1. [Una breve historia del blog](#una-breve-historia-del-blog)
2. [Instalación y uso de Jekyll](#instalacion-y-uso-de-jekyll)
3. [Instalar plugins](#instalar-plugins)
4. [Cambiar el tema por defecto](#cambiar-el-tema-por-defecto)
5. [Estructura de directorios](#estructura-de-directorios)

## Una breve historia del blog

## Instalación y uso de Jekyll

1. Descargar Ruby+DevKit desde [su web](https://jekyllrb.com/docs/installation/windows/)

2. Hacer la instalación dándole siguiente a todo

3. Cuando se habra la consola, hacer los pasos 1, 2 y 3 en orden. Tardará un rato.

4. Comprobar que está todo instalado con `ruby -v`, `gem -v`

5. Hecho esto, hacer un `gem install jekyll bundler` y, acto seguido, comprobar que está instalado **Jekyl** con `jekyll -v`

6. Crear un nuevo proyecto con ` jekyll new nombre-proyecto`

7. Se nos creará una estructura por defecto, con el tema _minimal_.

8. Ir al archivo **Gemfile** y añadir la línea `gem "webrick`

9. Hacer un `bundle install`

10. Hacer un `bundle exec jekyll serve` para levantar el servidor

## Instalar plugins

1. Acudir a [la dirección siguiente](https://jekyllrb.com/docs/plugins/your-first-plugin/)

2. Básicamente consiste en añadir una línea en el archivo `_config.yml` y otra en el archivo `Gemfile`. Revisar la documentación de cada plugin.

## Cambiar el tema por defecto.

Se puede desactivar, comentando las lineas para el tema que se encuentran en el archivo `_config.yml` y `Gemfile`. Y ya seguir la con esa estructura pero con nuestro estilo.

Para saber cómo esta compuesto el tema por defecto, hacer `bundle info --path minima`. Esto nos dará la ruta del tema. Hacemos _cd_ para entrar en el y un _ls_ para ver los archivos.

## Estructura de directorios

```
.
├── _config.yml
├── _data
│   └── members.yml
├── _drafts
│   ├── begin-with-the-crazy-ideas.md
│   └── on-simplicity-in-technology.md
├── _includes
│   ├── footer.html
│   └── header.html
├── _layouts
│   ├── default.html
│   └── post.html
├── _posts
│   ├── 2007-10-29-why-every-programmer-should-play-nethack.md
│   └── 2009-04-26-barcamp-boston-4-roundup.md
├── _sass
│   ├── _base.scss
│   └── _layout.scss
├── _site
├── .jekyll-metadata
└── index.html # can also be an 'index.md' with valid front matter
```
