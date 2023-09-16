# :file_folder: ELEMENTOS ESTRUCTURALES
Los elementos que componen la estructura básica que se ha planteado en el punto anterior y otros componentes que puede contener una página web.
* <a href="#1">ELEMENTOS INICIALIES</a>
* <a href="#2">ELEMENTOS PARA METADATOS</a>
* <a href="#3">ELEMENTOS DE SECCIONES</a>
<br>

<a name="1"><h1>ELEMENTOS INICIALES</h1></a>
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
<br>
<br>

<a name="2"><h1>ELEMENTOS PARA METADATOS</h1></a> 
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
<br>
<br>

<a name="3"><h1>ELEMENTOS DE SECCIONES</h1></a> 
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
En este se coloca todo lo de la cabecera de el documento como el logo, titulo de la web o el menú.
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

<div align="center">
  
  ##  [ANTERIOR](https://github.com/judali05/HTML-5/blob/main/RUTA/1%23%20SINTAXIS.md)  ||  [SIGUIENTE](https://github.com/judali05/HTML-5/blob/main/RUTA/3%23%20CONTENIDO%20Y%20TEXTO.md)
  
</div>
