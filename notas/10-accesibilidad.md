# ♿ Accesibilidad Web (A11y - Accessibility)   
La accesibilidad es el conjunto de buenas prácticas para que cualquier persona, incluyendo personas con discapacidad visual, auditiva, motriz o cognitiva, pueda navegar y entender tu sitio web sin problemas, El objetivo es que la web sea usable para todos, sin importar sus capacidades o dispositivos.  
<br/>

## 📊 Buenas Prácticas de Accesibilidad en HTML  

### 1️⃣ Uso de `alt` en Imágenes  
El atributo `alt` describe el contenido de una imagen para usuarios con lectores de pantalla.  

📌 **Ejemplo:**  
```html
<img src="grafico-ventas.png" alt="Gráfico de ventas del primer trimestre">
```
* **Si la imagen es decorativa**, usa `alt=""` vacío.  
* No uses `alt` con frases como “imagen de…” (el lector ya sabe que es una imagen).  
<br/>

### 2️⃣ Formularios Accesibles  
Los formularios deben tener etiquetas `<label>` correctamente asociadas a sus campos.  

📌 **Ejemplo correcto:**  
```html
<label for="email">Correo electrónico:</label>
<input type="email" id="email" name="email">
```
* **El atributo `for` debe coincidir con el `id` del campo** para que los lectores de pantalla puedan asociarlos.
* Evita usar `placeholder` en lugar de `label`, ya que puede ser difícil de leer.  
<br/>

### 3️⃣ Navegación con Teclado  
Los usuarios deben poder navegar usando solo el teclado con la tecla **Tab**.  

📌 **Ejemplo de botones accesibles:**  
```html
<button>Enviar</button>
```
Evita usar `<div>` o `<span>` en lugar de botones reales (`<button>`).  
<br/>

### 4️⃣ Uso de ARIA para Accesibilidad Avanzada  
ARIA (**Accessible Rich Internet Applications**) permite mejorar la accesibilidad en elementos complejos.  

📌 **Ejemplo de `aria-label`:**  
```html
<button aria-label="Cerrar ventana">❌</button>
```
* **Mejora la accesibilidad de elementos que no tienen texto visible**.
* Usa `role="navigation"`, `role="alert"`, etc., para mejorar la semántica.  
