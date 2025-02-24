# 📂 Elementos Estructurales 

Los elementos estructurales de una página web forman la base del documento HTML. Aquí encontrarás los principales:  

- [🏁 ELEMENTOS INICIALES](#-elementos-iniciales)  
- [📝 ELEMENTOS PARA METADATOS](#-elementos-para-metadatos)  
- [📌 ELEMENTOS DE SECCIONES](#-elementos-de-secciones)  
<br/> 

## 🏁 Elementos Iniciales  

### `<!DOCTYPE html>`  
Indica que el documento sigue el estándar HTML5.  

```html
<!DOCTYPE html>
```  

### `<html></html>`  
Define el inicio y fin del documento HTML.  

```html
<!DOCTYPE html>
<html>

</html>
```  
<br/>

## 📝 Elementos Para Metadatos  

### `<head></head>`  
Contiene información sobre el documento, como enlaces a estilos y scripts.  

```html
<!DOCTYPE html>
<html>
    <head>

    </head>
</html>
```  

### `<title></title>`  
Define el título que aparece en la pestaña del navegador.  

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Mi Página Web</title>
    </head>
</html>
```  

### `<link>`  
Vincula archivos externos, como hojas de estilo CSS.  

```html
<!DOCTYPE html>
<html>
    <head>
        <link rel="stylesheet" href="styles.css">
    </head>
</html>
```  

### `<meta>`  
Proporciona información sobre la codificación y configuración del documento.  

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
    </head>
</html>
```  

### `<style></style>`  
Permite agregar estilos CSS directamente en el documento.  

```html
<!DOCTYPE html>
<html>
    <head>
        <style>
            p {
                text-align: center;
            }
        </style>
    </head>
    <body>
        <p>Hola, mundo</p>
    </body>
</html>
```  
<br/> 

## 📌 Elementos De Secciones  

### `<body></body>`  
Contiene el contenido visible de la página.  

```html
<!DOCTYPE html>
<html>
    <body>
    </body>
</html>
```  

### `<header></header>`  
Sección superior que suele contener el logo, título y menú de navegación.  

```html
<!DOCTYPE html>
<html>
    <body>
        <header>
            <h1>Mi Sitio Web</h1>
        </header>
    </body>
</html>
```  

### `<nav></nav>`  
Contiene enlaces de navegación para moverse dentro del sitio.  

```html
<!DOCTYPE html>
<html>
    <body>
        <nav>
            <ul>
                <li><a href="#">Inicio</a></li>
                <li><a href="#">Servicios</a></li>
                <li><a href="#">Contacto</a></li>
            </ul>
        </nav>
    </body>
</html>
```  

### `<main></main>`  
Contiene el contenido principal de la página.  

```html
<!DOCTYPE html>
<html>
    <body>
        <main>
            <h1>Bienvenido</h1>
            <p>Esta es mi página de ejemplo.</p>
        </main>
    </body>
</html>
```  

### `<h1> - <h6>`  
Encabezados para organizar la jerarquía del contenido.  

```html
<!DOCTYPE html>
<html>
    <body>
        <h1>Título Principal</h1>
        <h2>Subtítulo</h2>
        <h3>Sección</h3>
    </body>
</html>
```  

### `<section></section>`  
Define una sección dentro del documento.  

```html
<!DOCTYPE html>
<html>
    <body>
        <section>
            <h2>Sobre Nosotros</h2>
            <p>Información sobre la empresa.</p>
        </section>
    </body>
</html>
```  

### `<article></article>`  
Agrupa contenido independiente, como publicaciones de blog o noticias.  

```html
<!DOCTYPE html>
<html>
    <body>
        <article>
            <h2>Novedades</h2>
            <p>¡Lanzamos un nuevo producto!</p>
        </article>
    </body>
</html>
```  

### `<aside></aside>`  
Contiene información complementaria, como barras laterales o anuncios.  

```html
<!DOCTYPE html>
<html>
    <body>
        <main>
            <section>
                <h1>Artículo Principal</h1>
                <p>Contenido principal de la página.</p>
            </section>
            <aside>
                <p>Información adicional o publicidad.</p>
            </aside>
        </main>
    </body>
</html>
```  

### `<footer></footer>`  
Define el pie de página con información de contacto o derechos de autor.  

```html
<!DOCTYPE html>
<html>
    <body>
        <footer>
            <p>© 2024 Mi Sitio Web - Todos los derechos reservados</p>
        </footer>
    </body>
</html>
```  
