## Elementos para metadatos
**< head >< /head >**
<br>en esta etiqueta es donde se ubican los metadatos en el documento con enlacesa, la cual solo es visible para los navegadores.
~~~
<!DOCTYPE html>
<html>
    <head>

    </head>
</html>
~~~
**< title >< /title >**
<br>define el titulo de la web.
~~~
<!DOCTYPE html>
<html>
    <head>
        <title>Titulo del documento</title>
    </head>
</html>
~~~
**< link >**
<br>la etiqueta incorpora recursos que son externos a el documento.
~~~
<!DOCTYPE html>
<html>
    <head>
        <title>Titulo del documento</title>
        <link href="styles.css">
    </head>
</html>
~~~
**< meta >**
<br>sirve para aportar informacion sobre el documento.
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
**< style >< /style >**
<br>funciona para agregar documentación css y se aplique en el documento.
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
