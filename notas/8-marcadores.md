# ⏩ Marcadores (ANCHORS)  
Cuando una página web es muy extensa y tiene múltiples secciones, es útil crear enlaces internos que nos permitan **navegar rápidamente** a una parte específica del contenido. Estos enlaces se llaman **marcadores** o **anclas internas**.  

## 🔗 Crear un Marcador Dentro Del Mismo Documento  
Para definir un marcador, se usa una estructura similar a la de un hipervínculo. Primero, se asigna un **nombre** a la sección de la página a la que queremos enlazar:  

```html
<a name="nombre_del_marcador"></a>
```

Luego, se crea el enlace que dirigirá a esa sección específica de la página:  

```html
<a href="#nombre_del_marcador">Ir al marcador</a>
```

> [!NOTE]  
> El marcador puede estar asociado a un texto, una imagen o incluso puede estar vacío.
<br/>

## 🌍 Enlazar a Un Marcador Desde Otro Documento  
También es posible enlazar un marcador desde otra página o documento HTML. Para hacerlo, es necesario conocer el **nombre del archivo** y el **nombre del marcador** definido previamente:  

```html
<a href="nombre_del_documento.html#nombre_del_marcador">Ir al marcador en otro documento</a>
```
