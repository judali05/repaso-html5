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
