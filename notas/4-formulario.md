# 📮 Formulario  
Un formulario es un elemento que permite a los usuarios ingresar y enviar datos.  

## 📝 Elementos de Formulario  

<div align="center">  

| **Elemento** | **Descripción** |  
|---|---|  
| `<form>` | Define el inicio y cierre de un formulario. |  
| `<fieldset>` | Agrupa visualmente los campos de un formulario. |  
| `<legend>` | Define el título de un `<fieldset>`. |  
| `<label>` | Asigna un nombre descriptivo a un control del formulario. |  
| `<input>` | Crea controles interactivos para la entrada de datos. |  
| `<button>` | Representa un botón dentro del formulario. |  
| `<select>` | Muestra un menú desplegable de opciones. |  
| `<optgroup>` | Agrupa opciones dentro de un `<select>` para organizarlas lógicamente. |  
| `<option>` | Define un elemento dentro de un `<select>`. |  
| `<textarea>` | Permite la entrada de texto en varias líneas. |  
</div>  
<br>  

### ⚙️ Atributos de Formulario  

* `action` : Define la URL a la que se enviarán los datos del formulario para su procesamiento en el servidor.  
* `method` : Determina el método HTTP utilizado para enviar los datos. Sus valores pueden ser:    
  * `GET` : Envía la información en la URL, lo que la hace visible en la barra de direcciones.
  * `POST` : Envía los datos de forma oculta en el cuerpo de la solicitud, recomendado para información sensible.
    
> [!CAUTION]
> Get es el método predeterminado si no se especifica.  
  <br>  



### 🎛️ Atrubutos Del Input 

<div align="center">  

| **Atributo** | **Descripción** |  
|---|---|  
| `type` | 🔢 Especifica el tipo de entrada, como texto, contraseña, correo, etc. |  
| `value` | 🏷️ Establece el valor inicial del campo de entrada. |  
| `placeholder` | 💬 Muestra un texto de referencia dentro del campo hasta que se ingresa un valor. |  
| `required` | ❗ Indica que el campo es obligatorio. |  
| `readonly` | 🔒 Hace que el campo solo sea de lectura; el usuario no puede modificarlo. |  
| `disabled` | 🚫 Deshabilita el campo, impidiendo su edición y envío en el formulario. |  
| `size` | 📏 Determina la cantidad de caracteres visibles en el campo. Su valor predeterminado es 20. Solo funciona con los tipos: `text`, `search`, `tel`, `url`, `email` y `password`. |  
| `maxlength` | 🔢 Establece la cantidad máxima de caracteres permitidos. |  
| `min` / `max` | 📉📈 Define valores mínimos y máximos para el campo. |  
| `pattern` | 🔤 Permite definir una expresión regular para validar la entrada. |  

</div>  
<br>  

### 🔠 Valores Del Atributo `Type`  

El atributo `type` de los elementos `<input>` define el tipo de datos que se pueden ingresar en un campo.  

<div align="center">  

| **Valor** | **Descripción** |  
|---|---|  
| `text` | Campo de entrada de texto. |  
| `password` | Campo de entrada de contraseña (oculta el texto). |  
| `number` | Campo numérico con validación y controles de incremento/decremento. |  
| `date` | Campo para seleccionar una fecha (año, mes y día). |  
| `email` | Campo de correo electrónico con validación integrada. |  
| `checkbox` | Casilla de verificación para seleccionar múltiples opciones. |  
| `submit` | Botón para enviar el formulario. |  
| `image` |  Botón de envío con imagen, definida en el atributo `src`. |  
| `file` | Permite la selección de archivos desde el dispositivo. |  
| `radio` | Botón de selección única dentro de un grupo de opciones. |  
| `color` | Selector de color. |  
| `url` | Campo de entrada para direcciones web (URLs). |  
</div>  



