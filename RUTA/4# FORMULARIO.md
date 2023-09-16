# :postbox: FORMULARIO
Es una caja de texto que puede contener los datos introducidos por los ususarios.

## ELEMENTOS DE FORMULARIOS

<div align="center">
  
| ELEMENTO | DESCRIPCIÓN |
|---|---|
| `<form>` | esta es la etiqueta de inicio y cierre de un formulario. |
| `<fieldset>` | permite organizar en grupos los campos de un formulario. |
| `<legend>` | esta define el titulo de la etiqueta < fieldset >. |
| `<label>` | define el titulo de un control del formulario. |
| `<input>` | se usa para crear controles interactivos en el formulario. |
| `<button>` | define el boton de un formulario. |
| `<select>` | permite seleccionar una serie de opciones que se encuentren en dicho fromulario. |
| `<optgroup>` |	Representa un conjunto de opciones, agrupadas lógicamente. |
| `<option>` | representa un item dentro de un < select >. |
| `<textarea>` | define un campo para que el usuario ingrese un texto con una cantidad maxima en el formulario. |
  
</div>
<br>

### ATRIBUTOS DEL FROM

* `action` : Se usa para indica dónde se enviarán los datos del formulario para que se puedan guardar. Por lo general, se especifica la URL de un script del lado del servidor que se encargará de procesar los datos del formulario.
* `method` : Tiene dos valores el GET o el POST y determina el método HTTP que se utilizará para enviar los datos del formulario al servidor. La diferencia principal radica en cómo se transmiten los datos.
    * `GET` :  Información se envía de forma visible.
      > [!NOTE]
      > Es la forma predeterminada si no se especifica el atributo method.

      <br>
  
    * `POST` : Información se envía de forma no visible, Es adecuado para enviar datos sensibles, como contraseñas o información personal.

### ATRIBUTOS DEl INPUT

<div align="center">

| ATRIBUTOS |	DESCRIPCIÓN |
|---|---|
| `type`	| Da el tipo de input  como de texto, contraseña, correo, fechas etc. |
| `value`	| Valor inicial del input. |
| `placeholder` |	Describe el valor esperado en un campo. |
| `required` |	Especifica que es obligatorio rellenar el campo el input.| 
| `readonly` | El input es de solo lectura, el usuario no puede editar el control. |
| `disabled`	| El input no se puede modificar,hace que el elemento no sea mutable, enfocable o incluso enviado con el formulario. |
| `size`	| Cantidad de caracteres visibles en un input. Su valor por defecto es 20. Funciona en los inputs de los siguientes tipos: text,  search, tel, url, email, and password. |
| `maxlength` 	| Máximo número de caracteres del input. |
| `min` / `max`	| Mínimo y máximo número de caracteres del input. |
| `pattern`	| Nos permite indicar un patrón,especifica una expresión regular que el valor del control de formulario debe coincidir. |
</div>
<br>


### VALOR DEL TYPE
El artributo type de los inputs especifican el tipo de datos que se ingresa en un campo.

<div align="center">
  
| VALOR	| DESCRIPCIÓN |
|---|---|
| `text` | Campo de texto. |
| `password`	| Campo oculto. Usado para contraseñas. |
| `number`	| Campo de número. Muestra un selector y agrega validación predeterminada. |
| `date`	| Campo de fecha (año, mes y día). Abre un selector de fechas para año, mes y día. |
| `email`	| Campo de correo electrónico haciendo su validación. |
| `checkbox`	| Casilla de verificación que permite seleccionar o deseleccionar distintos valores. |
| `submit`	| Botón que envía el formulario |
| `image`	| Botón con imagen de tipo submit. La imagen se define en el atributo src. |
| `file`	| Permite seleccionar un archivo. |
| `radio`	| Permite seleccionar un valor único entre múltiples opciones. |
| `color` | Control para especificar un color; abre un selector de colores cuando está activo. |
| `url`	| Nos permite ingresar una URL. |
</div>
<br>
<br>

