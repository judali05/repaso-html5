# :mag_right: SINTAXIS 
La etiqueta presenta frecuentemente dos partes, su apertura y cierre, y se encierran ambas partes entre símbolos "menor que" y "mayor que".
<br>

| APERTURA  | CIERRE |
|---|---|
|El inicio de una etiqueta se produce de la siguiente manera:<div align="center"> `<etiqueta>`</div> |El final de una etiqueta se produce de manera similar a su apertura, aunque agregando una barra:<div align="center"> `</etiqueta>` </div> |


<br>

***

## ESTRUCCTURA BÁSICA
Una de las principales ventajas de HTML5 es la inclusión de elementos semánticos, o marcados semánticos, que nos ayudan a definir las distintas divisiones de una página web.
<br>
<div align="center">

<img src="https://github.com/judali05/HTML-5/assets/129390687/df9831e5-b716-4eb1-9752-fb70e2273552" style=" width: 500px;">
  
</div>
<br>
html ordena mediante marcadores semánticos haciendo que se diferencie claramente el contenido que referencia cada etiqueta.
<br>

~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <header>
        <h1>Titulo</h1>
    </header>
    <nav>
        <a href="#">Seleccione 1</a>
        <a href="#">Seleccione 2</a>
    </nav>
    <section>      
        <article>
            <h2>Contenido principal</h2>
            <p>Este es el contenido principal de mi web.</p>      
        </article>      
    </section>
    <aside>
        <h3>Contenido secundario</h3>
        <p>Me gusta mucho esta página.</p>
    </aside>
    <footer>
        <h4>Redes sociales</h4>
        <a href="#">Facebook</a>
        <a href="#">Tiwtter</a>
    </footer>
</body>
</html>
~~~

> [!IMPORTANT]
>`Comentario` <br>
>En este lenguaje un comentarios se escribe de la siguiente forma <br>
 `<!-- (Aquí va lo que se comente) -->`
<br>
<br>
