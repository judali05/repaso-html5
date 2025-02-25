# 🔍 SEO  
SEO (**Search Engine Optimization**) es el conjunto de técnicas y estrategias que se usan para mejorar la visibilidad de una página web en los navegadores, Cuando optimizas el HTML de tu página, ayudas a que los buscadores entiendan mejor tu contenido, lo indexen correctamente y lo muestren a más personas cuando buscan información relacionada.  
<br/>

## 📊 Elementos clave para un buen SEO en HTML 

### 1️⃣ Metaetiquetas Esenciales  
Las metaetiquetas proporcionan información sobre tu página a los motores de búsqueda.  

📌 **Ejemplo de metaetiquetas importantes en el `<head>`:**  
```html
<head>
    <title>Guía de HTML5 para Principiantes</title>
    <meta name="description" content="Aprende HTML5 desde cero con ejemplos y buenas prácticas.">
    <meta name="keywords" content="HTML5, desarrollo web, tutorial, etiquetas HTML">
    <meta name="author" content="Tu Nombre">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
```
* **`title`** → Define el título que se muestra en la pestaña del navegador y en los resultados de búsqueda.
* **`description`** → Describe el contenido de la página (Google la usa para mostrar fragmentos en los resultados).
* **`keywords`** → Palabras clave relacionadas con el contenido (ya no es muy usada por Google, pero sigue siendo útil).
* **`viewport`** → Hace que la página sea **responsiva** en dispositivos móviles.  
<br/>

### 2️⃣ Uso Correcto de Encabezados (`h1` a `h6`)  
Los encabezados ayudan a los buscadores a entender la estructura de tu contenido.  

📌 **Ejemplo correcto de estructura de encabezados:**  
```html
<h1>Guía Completa de HTML5</h1>  <!-- Solo un H1 por página -->
<h2>¿Qué es HTML5?</h2>
<h3>Historia del HTML</h3>
<h3>Ventajas de HTML5</h3>
<h2>Cómo usar HTML5</h2>
<h3>Etiquetas más utilizadas</h3>
```
* **Usa solo un `<h1>` por página** (representa el título principal).
* Usa `<h2>`, `<h3>`, etc., para dividir el contenido en secciones jerárquicas.
* No abuses de los `<h1>` o `<h2>` solo para hacer texto grande.  
<br/>

### 3️⃣ Imágenes Optimizadas Para SEO**  
Las imágenes deben tener un **nombre descriptivo** y un atributo `alt` para ayudar a los motores de búsqueda a entenderlas.  

📌 **Ejemplo correcto:**  
```html
<img src="html5-introduccion.png" alt="Guía de introducción a HTML5">
```
* **Usa nombres descriptivos en los archivos de imagen** (evita cosas como `img001.jpg`).
* **El atributo `alt` ayuda a personas con discapacidad visual** y mejora el SEO.  
<br/>

### 4️⃣ Enlaces Internos & Externos 
Los enlaces ayudan a mejorar la navegación y la autoridad de la página.  

📌 **Ejemplo:**  
```html
<a href="tutorial-html5.html">Aprende más sobre HTML5</a>  <!-- Enlace interno -->
<a href="https://developer.mozilla.org/es/docs/Web/HTML" target="_blank" rel="noopener">Documentación en MDN</a>  <!-- Enlace externo -->
```
* **Usa enlaces internos** para conectar páginas dentro de tu web.
* **Usa enlaces externos de calidad** para dar credibilidad (pero sin abusar).
* Agrega `rel="noopener"` en enlaces externos para mejorar la seguridad.  

