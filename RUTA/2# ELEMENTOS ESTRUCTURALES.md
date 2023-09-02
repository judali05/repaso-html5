# :file_folder: ELEMENTOS ESTRUCTURALES
En este punto se detalla de forma resumida los elementos que componen la estructura básica que se ha planteado en el punto anterior y otros componentes que puede contener una página web.
* ELEMENTOS INICIALIES
* ELEMENTOS PARA METADATOS
* ELEMENTOS DE SECCIONES
<br>

## ELEMENTOS INICIALES
### `< !DOCTYPE html >`
Permite que los navegadores comprendan que el documento se basa en HTML5.
~~~
<!DOCTYPE html>
~~~
### `< html >< /html >`
Esta es la etiqueta de apertura y cierre de un documento HTML, los elementos que se agregen deben estar dentro de dichas etiquetas.
~~~
<!DOCTYPE html>
<html>

</html>
~~~
<br>

***

## ELEMENTOS PARA METADATOS
### `< head >< /head >`
En esta etiqueta es donde se ubican los metadatos en el documento con enlacesa, la cual solo es visible para los navegadores.
~~~
<!DOCTYPE html>
<html>
    <head>

    </head>
</html>
~~~
### `< title >< /title >`
Define el titulo de la web.
~~~
<!DOCTYPE html>
<html>
    <head>
        <title>Titulo del documento</title>
    </head>
</html>
~~~
### `< link >`
La etiqueta incorpora recursos que son externos a el documento.
~~~
<!DOCTYPE html>
<html>
    <head>
        <title>Titulo del documento</title>
        <link href="styles.css">
    </head>
</html>
~~~
### `< meta >` 
Sirve para aportar informacion sobre el documento.
~~~
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Titulo del documento</title>
        <link href="styles.css">
    </head>
</html>
~~~
### `< style >< /style >`
Funciona para agregar documentación css y se aplique en el documento.
~~~
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Titulo del documento</title>
        <link href="styles.css">
        <style>
             p {
              text-align: center;
            }
          </style>
    </head>
    <body>
        <p>hola</p>
    </body>
</html>
~~~
<br>

***

## ELEMENTOS DE SECCIONES
### `< boby >< /boby >`
Donde se ubica el contenido de el documento.
~~~
<!DOCTYPE html>
<html>
    <body>
    </body>
</html>
~~~
### `< header >< /header >`
En este se coloca todo lo de la cabecera de el documento como el logo, nombre de la web o el menú.
~~~
<!DOCTYPE html>
<html>
    <body>
        <header>
            
        </header>
    </body>
</html>
~~~
### `< nav >< /nav >`
Es un elemento contenedor para enlaces de navegacion, que se supone proveen formas de acceder a las secciones del sitio web.
~~~
<!DOCTYPE html>
<html>
    <body>
        <header>
            <nav class="menú">
                <ul>
                  <li>Inicio</li>
                  <li>Sobre nosotros</li>
                  <li>Contacto</li>
                </ul>
              </nav>
        </header>
    </body>
</html>
~~~
### `< main >< /main >`
Reprecenta el contenido principal  que esta directamente relacionado.
~~~
<!DOCTYPE html>
<html>
    <body>
        <header>
        </header>
        <main>
            <h1>Titulo del tema</h1>
            <p>resumen del tema a tratar</p>
        </main>
    </body>
</html>
~~~
### `< h1 > < h2 > < h3 > < h4 > < h5 > < h6 >`
Estructura del encabezado o titulos para el contenido del documento
~~~
<!DOCTYPE html>
<html>
    <body>
        <header>
        </header>
        <main>
            <h1>Titulo del tema</h1>
            <section> 
                    <h2>Subtitulo del tema</h2>
                    <p>resumen del tema a tratar</p>
            </section>
        </main>
    </body>
</html>
~~~
### `< section >< /section>`
Representa una sección de un documento, para determinar una parte del documento.
~~~
<!DOCTYPE html>
<html>
    <body>
        <header>
        </header>
        <main>
            <section>
                <h1>Titulo del tema</h1>
                    <h2>Subtitulo del tema</h2>
                    <p>resumen del tema a tratar</p>
            </section>
        </main>
    </body>
</html>
~~~
### `< article >< /article >`
Representa un contenido independiente y autonomo.
~~~
<!DOCTYPE html>
<html>
    <body>
        <header>
        </header>
        <main>
        <section>
            <article>
                <h1>Titulo del tema</h1>
                <p>resumen del tema a tratar</p>
            </article>
            <article>
                <h2>Subtitulo del tema</h2>
                <p>resumen del tema</p>
            </article>
        </section>
        </main>
    </body>
</html>
~~~
### `< aside >< /aside >`
Representa el contenido adicional o barra lateral del documento.
~~~
<!DOCTYPE html>
<html>
    <body>
        <header>
        </header>
        <main>
        <section>
               <h1>Titulo del tema</h1>
                <p>resumen del tema a tratar</p>
        </section>
        <section>
            <aside>
                <p> texto adicional del tema </p>
            </aside>
        </section>
        </main>
    </body>
</html>
~~~
### `< footer >< /footer >`
Represente el contenido que ira en el pie de pagina del documento.
~~~
<!DOCTYPE html>
<html>
    <body>
        <header>
        </header>
               <h1>Titulo del tema</h1>
                <p>resumen del tema a tratar</p>
        <footer>
            <p>informacion del creador de la pagina, empresa, datos personales, etc.</p>
        </footer>
    </body>
</html>
~~~

<br>
<br>
