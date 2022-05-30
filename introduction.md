# HTML Learning
## What's HTML?
Es el lenguaje de marcado, que nos permite darle la estructura básica a una página web o darle la estructura al contenido como:
- Texto
- Imagenes 
- Videos
- Listas

## What’s HTML used for?
Para crear la estructura de contenido con ayuda de etiquetas de HTML y así la elaboración de páginas web.

## Structure of a HTML Document
La estructura de un documento HTML es el conjunto de elementos que caracterizan un determinado ámbito.
``` html 
<!Doctype>
<html>
  <head>
  </head>
  <body>
      Contenido
    <button></button>
  </body>
 </html>
```

## What are HTML Tags?
Se utiliza para indicar el principio y el final de un elemento HTML en un documento HTML. Estas etiquetas dan instrucciones al navegador web sobre cómo mostrar el texto. Por ejemplo:

| Etiqueta      |                   Descripción               |
|:-----------   | :-------------                               |
|```<!DOCTYPE>```| Sirve para definir el tipo de documento|
|```<html></html>```|Define un documento HTML|
|```<head></head>```|Dentro se escribe información sobre el documento|
|```<title></title>```|Para escribir el título del documento. Se escriben dentro de ```<head>```|
|```<body></body>```|Justo después de ```</head>``` Es el contenedor del documento|
|```<h1></h1> hasta <h6></h6>```|Para crear títulos de párrafos, de más importante a menos|
|```<p></p>```|Los párrafos de texto de nuestro documento|
|```<br>```|Un salto de línea simple|
|```<hr>```|Salto de línea que indica un cambio de temática entre párrafos|
|```<a></a>```|Podremos escribir enlaces a otras páginas|

## What’s a HTML empty element?
Una etiqueta/elemento vacia es un elemento de HTML que no lleva una etiqueta de cierre, solo pueden acabar con " />". Por ejemplo:
```
<area>          <hr>          <meta>          <wbr>
<base>          <img>         <param>
<br>            <input>       <source>
<col>           <link>        <track>
<embed>
```
Aunque no tiene etiqueta de cierre, no afecta a las demas que si tienen etiqueta de cierre.

## What are HTML attributes?
Son palabras especiales utilizadas dentro de la etiqueta de apertura, esto para añadir, complementar información o significado al elemento HTML al que estamos colocando y así controlar el comportamiento del elemento. Por ejemplo:

| Atributo| Descripción|
| :-------| :--------- |
|src | Señala la fuente| 
|lang | Indica el lenguaje |
|width| Modifica el ancho |
|height| Modifica la altura |
|background-color| Cambia el color del fondo |
|id | Da una identificación unica |
|style | Le da estilo |
|href | Señala el enlace |
|class | Identifica |
|align | Sirve para alinear |
```
Ejemplo:   <a href="https://github.com/katherine-na" disabled <p style="color:pink; font-size: 20px">mi titulo de html</p>
```
## What are HTML global attributes?
Son atributos comunes a todos los elementos HTML; se pueden usar en todos los elementos. 
Atributos globales.

| Atributos globales | Definición |
| :--------- | :--------|
| lang | Indica el lenguaje |
| class | Identifica |
| title | 
| style |
| input |


```
acceskey                    dir                     is                  lang                  title
autocapitalize              draggable               itemid              nonce                 translate
autocomplete                enterkeyhint            itemprop            slot                  dropzone
class                       hidden                  itemref             spellcheck
contentditable              inputmode               itemscope           style
contextmenu                 id                      itemtype            tabindex

```
[source](https://www.htmlquick.com/es/reference/attributes.html#:~:text=Los%20atributos%20son%20un%20mecanismo,o%20configuraciones%20para%20los%20elementos)


# Formularios

| Input type="" | Qué es? |
| :-------  | :-------|
| text | Crea un campo de texto en una linea |
| mail | Solicita un correo real |
| password | Solicita una contraseña |
| submit | Boton que envia los datos |
| reset | Recetea el formulario |
| radio | Define un boton de opción |
| checkbox | Define una casilla de verificación |
| button | Crea un boton |
| color | Aparece un selector de color |
| date | Selecciona fechas |
| time | Selecciona la hora |
| datetime-local | Selecciona la fecha y la hora local |
| month | Selecciona un mes |
| file | Puedes cargar archivos y subirlos |
| hidden | Sirve para ocultar |
| image | Puedes colocar una imagen |
| number | Permite escribir números |
| range | Selecciona un valor mediante un control deslizante |
| search | Puedes hacer busquedas | 
| tel | Unicamente para telefonos |
| url | Unicamente para links |
| week | Selecciona semanas |

# Elementos de formularios 

| Elemento | Qué es? | 
| :----- | :----- |
| ```<label>``` | Este elemento define una etiqueta para varios elementos de formulario |
| ```<select>``` | Este elemento define una lista desplegable |
| option | Los elementos ```<option>``` definen una opción que se puede seleccionar |
| size | Este atributo especifica el número de valores visibles | 
| multiple | Este atributo permite que el usuario seleccione más de un valor |
| ```<textare>``` | Define un campo de entrada de varias líneas (un área de texto)|
| rows | Este atributo especifica el número visible de líneas en un área de texto |
| cols| Este atributo especifica el ancho visible de un área de texto |
| ```<button>``` | Define un botón en el que se puede hacer clic|
|```<fieldset>``` | Se utiliza para agrupar datos relacionados en un formulario.
|```<legend>``` | Define un título para el ```<fieldset>``` elemento |
| datalist | Especifica una lista de opciones predefinidas |
| output | Representa el resultado de un cálculo |


# Atributos de Formulario

| Atributo   | Qué es?   |
| :----------| :-----    | 
| accept-charset | Especifica las codificaciones de caracteres utilizadas para el envío de formularios |
| action | Especifica dónde enviar los datos del formulario cuando se envía un formulario |
| autocomplete | Especifica si un formulario debe tener la función de autocompletar activada o desactivada |
| enctype | Especifica cómo se deben codificar los datos del formulario al enviarlos al servidor (solo para method="post") |
| method | Especifica el método HTTP a utilizar al enviar datos de formulario |
| name | Especifica el nombre del formulario |
| novalidate | Especifica que el formulario no debe validarse cuando se envía |
| rel | Especifica la relación entre un recurso vinculado y el documento actual |
| target | Especifica dónde mostrar la respuesta que se recibe después de enviar el formulario |
