# :fast_forward: MARCADORES
Al crear una página web muy larga y con muchos apartados, es útil crear ciertos enlaces que nos permitan saltar directamente a la parte de la página que nos interesa. Este tipo de hipervínculos se llaman marcadores o enlaces locales.

## LLAMAR MARCADOR EN UN DOCUMENTO
* La estructura de los marcadores es básicamente la misma que al crear un hiperenlace o hipervínculo a otra página. Lo primero que hay que hacer es definir con un nombre cada parte de la página a la que queremos enlazar.

<br>

~~~
<a name="(nombre del marcador)"></a>
~~~

<br>

* La sintaxis para crear un enlace a esa sección de la página es la siguiente:

<br> 

~~~
<a href="#(nombre del marcador)"> MARCADOR </a>
~~~

<br>

> [!NOTE]
> Puede contener un texto, una imagen o incluso podemos dejarla en blanco.

## LLAMAR MARCADOR EN OTRO DOCUMENTO
* También se puede hacer una llamada a marcadores desde otro documento. Para ello, necesitamos saber el nombre del documento y el nombre del marcador o ancla de la sintaxis anterior

<br>

~~~
<a name="(nombre del marcador)"></a>
~~~

<br>

* la sintaxis para llamar es la siguiente:

<br>

~~~
<a href="(nombre del documento)#(nombre del marcador)"> MARCADOR </a>
~~~

<br>
<br>
