# 📂 ELEMENTOS ESTRUCTURALES

Los elementos que componen la estructura básica de una página web incluyen los siguientes:

- [ELEMENTOS INICIALES](#elementos-iniciale)
- [ELEMENTOS PARA METADATOS](#elementos-para-metadatos)
- [ELEMENTOS DE SECCIONES](#elementos-de-secciones)

---

## 🏁 ELEMENTOS INICIALES

### `<!DOCTYPE html>`
Define que el documento sigue el estándar HTML5.

```html
<!DOCTYPE html>
```

### `<html></html>`
Etiqueta que encierra todo el contenido de la página web.

```html
<!DOCTYPE html>
<html>

</html>
```

---

## 📝 ELEMENTOS PARA METADATOS

### `<head></head>`
Contiene metadatos e información del documento.

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
        <title>Título del documento</title>
    </head>
</html>
```

### `<link>`
Incorpora recursos externos como hojas de estilo CSS.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Título del documento</title>
        <link rel="stylesheet" href="styles.css">
    </head>
</html>
```

### `<meta>`
Proporciona información sobre el documento.

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Título del documento</title>
    </head>
</html>
```

### `<style></style>`
Permite escribir código CSS dentro del mismo archivo HTML.

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
        <p>Hola</p>
    </body>
</html>
```

---

## 📌 ELEMENTOS DE SECCIONES

### `<body></body>`
Contiene el contenido visible de la página web.

```html
<!DOCTYPE html>
<html>
    <body>
    </body>
</html>
```

### `<header></header>`
Incluye la cabecera de la página, como el logo y el título.

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
Contiene enlaces de navegación dentro del sitio.

```html
<!DOCTYPE html>
<html>
    <body>
        <nav>
            <ul>
                <li><a href="#">Inicio</a></li>
                <li><a href="#">Sobre Nosotros</a></li>
                <li><a href="#">Contacto</a></li>
            </ul>
        </nav>
    </body>
</html>
```

### `<main></main>`
Define el contenido principal de la página.

```html
<!DOCTYPE html>
<html>
    <body>
        <main>
            <h1>Título del Tema</h1>
            <p>Resumen del tema a tratar</p>
        </main>
    </body>
</html>
```

### `<h1> - <h6>`
Encabezados que estructuran el contenido.

```html
<!DOCTYPE html>
<html>
    <body>
        <h1>Título Principal</h1>
        <h2>Subtítulo</h2>
        <h3>Sección</h3>
        <h4>Subsección</h4>
        <h5>Detalle</h5>
        <h6>Nota</h6>
    </body>
</html>
```

### `<section></section>`
Define secciones dentro de la página.

```html
<!DOCTYPE html>
<html>
    <body>
        <section>
            <h1>Título de la Sección</h1>
            <p>Contenido relevante de la sección.</p>
        </section>
    </body>
</html>
```

### `<article></article>`
Representa un contenido independiente dentro de una sección.

```html
<!DOCTYPE html>
<html>
    <body>
        <section>
            <article>
                <h1>Artículo 1</h1>
                <p>Descripción del artículo.</p>
            </article>
            <article>
                <h2>Artículo 2</h2>
                <p>Más información aquí.</p>
            </article>
        </section>
    </body>
</html>
```

### `<aside></aside>`
Contiene información adicional o complementaria.

```html
<!DOCTYPE html>
<html>
    <body>
        <main>
            <section>
                <h1>Artículo Principal</h1>
                <p>Texto principal.</p>
            </section>
            <aside>
                <p>Contenido adicional o anuncios.</p>
            </aside>
        </main>
    </body>
</html>
```

### `<footer></footer>`
Define el pie de página con información relevante.

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

---

<div align="center">
  
📌 [ANTERIOR](https://github.com/judali05/HTML-5/blob/main/RUTA/1%23%20SINTAXIS.md) || [SIGUIENTE](https://github.com/judali05/HTML-5/blob/main/RUTA/3%23%20CONTENIDO%20Y%20TEXTO.md)

</div>
