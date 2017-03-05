# GitHub Pages Simple

## Introducción

Es muy sencillo usar [GitHub Pages][1] y el gestor de temas [Jekyll][2] para crear un sitio web de [páginas estáticas](https://es.wikipedia.org/wiki/P%C3%A1gina_web#P.C3.A1ginas_est.C3.A1ticas_versus_p.C3.A1ginas_din.C3.A1micas) que todo mundo pueda ver. Los pasos indicados en esta guía se llevan a cabo complementamente usando un navegador web, sin necesidad de comandos de línea. Para tener tu sitio web en "un tris", sigue las instrucciones de esta página, para conocer más sobre GitHub ve a [GitHub Simple][3].

## Instrucciones abreviadas

A continuación se enumeran los pasos a realizar de forma muy breve, digamos a manera de [apunte escodido](https://es.wikipedia.org/wiki/Apunte_escondido).

### Crea un repositorio / sitio web en GitHub Pages

1. Si aún no la tienes, [crea una cuenta](../README.md#cómo-hago-una-cuenta) en [GitHub][4].
2. [Crea un nuevo repositorio](../README.md#crea-un-repositorio)) usando `nombredeusario.github.io` como nombre del mismo.
3. Haz clic en "Settings".
4. En la sección de GitHub Pages haz clic en "Choose a theme".
5. Revisa los temas y escoge uno.
6. Te dará la opción de editar el archivo [README.md](../README.md#qué-es-readme). Haz clic e el botón "Cancel" para editarlo posteriormente.

   > Nota: Mientras no haya una página de inicio personalizada, README.md se mostrará como la página de inicio del sitio web.

### Crea una nueva página usando Markdown

Puedes usar archivos [Markdown](https://es.wikipedia.org/wiki/Markdown) para compartir tu contenido como página web accesible por todo el mundo. [Jekyll][2] lo convertirá por tí en un formato que los navegadores web pueden interpretar como páginas web.

1. Ve al repositorio en GitHub en el que agregarás tu contenido.
1. Haz clic en el botón `Create new file` para agregar un nuevo archivo.
1. Agrega el nombre de archivo incluyendo la extensión `.md`.
1. Agrega tu contenido.
1. Haz clic en la pestaña `Preview` para revisar cómo se vería sin los efectos de diseño de la plantilla.
1. Haz clic en el botón `Commit new file` para guárdarlo.
1. Ve al enlace de la página, `nombredeusario.github.io/mipagina.md` y revisa el resultado.  

#### Ejemplo Markdown simple

##### Repositorio

https://github.com/rubenrivera/rubenrivera.github.io/

##### Enlace al archivo en GitHub

https://github.com/rubenrivera/rubenrivera.github.io/blob/master/README.md

### Crea una nueva página usando código HTML

Puedes usar archivos [HTML](https://es.wikipedia.org/wiki/HTML) para compartir tu contenido.

1. Ve al repositorio en GitHub en el que agregarás tu contenido.  
1. Haz clic en el botón `Commit new file` para agregar una nueva página.  
1. Agrega el nombre de archivo incluyendo la extensión `.html`.

  > Nota: Salvo que cambies la configuración de tu sitio `index.html` será usado como página de inicio  y por excepción `README.md`.

1. Agrega tu código.
1. Haz clic en el botón `Commit new file` para guárdarlo.
1. Ve al enlace de la página, `nombredeusario.github.io/mipagina.html` y revisa el resultado.  

#### Ejemplo HTML simple

##### Repositorio  

https://github.com/rubenrivera/rubenrivera.github.io/

##### Fuente HTML ¡Hola mundo!

    <html>
      <body>
        ¡Hola mundo!
      </body>
    </html>

##### Enlace al archivo en GitHub

https://github.com/rubenrivera/rubenrivera.github.io/blob/master/holamundo.html

##### Enlace a la página publicada  

Un enlace como este sería el que utilizarías para evaluar tu página en la herramienta para desarrolladores de Facebook o cualquier otro similar

https://rubenrivera.github.io/holamundo.html

# Véase también

## Guías oficiales de GitHub

[Getting Started with GitHub Pages][5]
[Mastering Markdown][6]

# Referencias

## Ayuda oficial de GitHub

[Creating a GitHub Pages site with the Jekyll Theme Chooser][7]


  [1]: https://pages.github.com/
  [2]: https://jekyllrb.com/
  [3]: /README.md
  [4]: http://github.com
  [5]: https://guides.github.com/features/pages/
  [6]: https://guides.github.com/features/mastering-markdown/
  [7]: https://help.github.com/articles/creating-a-github-pages-site-with-the-jekyll-theme-chooser/
