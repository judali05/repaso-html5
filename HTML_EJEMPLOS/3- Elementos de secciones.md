## Elementos de secciones
* **< boby >< /boby >**
<br>donde se ubica el contenido de el documento.
~~~
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Titulo del documento</title>
        <link href="styles.css">
    </head>
    <body>
    </body>
</html>
~~~
* **< header >< /header >**
<br>en este se coloca todo lo de la cabecera de el documento como el logo, nombre de la web o el menú.
~~~
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Titulo del documento</title>
        <link href="styles.css">
    </head>
    <body>
        <header>
            
        </header>
    </body>
</html>
~~~
* **< nav >< /nav >**
<br>es un elemento contenedor para enlaces de navegacion, que se supone proveen formas de acceder a las secciones del sitio web.
~~~
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Titulo del documento</title>
        <link href="styles.css">
    </head>
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
* **< main >< /main >**
<br>reprecenta el contenido principal  que esta directamente relacionado.
~~~
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Titulo del documento</title>
        <link href="styles.css">
    </head>
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
* **< h1 > hasta < h6 >**
<br>estructura del encabezado o titulos para el contenido del documento
~~~
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Titulo del documento</title>
        <link href="styles.css">
    </head>
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
* **< section >< /section>**
<br>representa una sección de un documento, para determinar una parte del documento.
~~~
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Titulo del documento</title>
        <link href="styles.css">
    </head>
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
* **< article >< /article >**
<br>representa un contenido independiente y autonomo.
~~~
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Titulo del documento</title>
        <link href="styles.css">
    </head>
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
* **< p >< /p >**
<br>representa el contenido del documento.
~~~
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Titulo del documento</title>
        <link href="styles.css">
    </head>
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
* **< aside >< /aside >**
<br>representa el contenido adicional o barra lateral del documento.
~~~
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Titulo del documento</title>
        <link href="styles.css">
    </head>
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
* **< footer >< /footer >**
<br>represente el contenido que ira en el pie de pagina del documento.
~~~
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Titulo del documento</title>
        <link href="styles.css">
    </head>
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
