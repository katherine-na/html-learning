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
  </body>
 </html>
```

## What are HTML Tags?
Se utiliza para indicar el principio y el final de un elemento HTML en un documento HTML. Estas etiquetas dan instrucciones al navegador web sobre cómo mostrar el texto. Por ejemplo:
```
  1. <!DOCTYPE>  
        Sirve para definir el tipo de documento
  2. <html></html>
        Define un documento HTML
  3.<head></head>
        Dentro se escribe información sobre el documento
  4. <title></title>
        Para escribir el título del documento. Se escriben dentro de <head>
  5. <body></body>	
        Justo después de </head>. Es el contenedor del documento
  6. <h1></h1>, <h2></h2> hasta <h6></h6>	
        Para crear títulos de párrafos, de más importante <h1> a menos <h6>
  7. <p></p>	
        Los párrafos de texto de nuestro documento
  8. <br>	
        Un salto de línea simple
  9. <hr>	
        Salto de línea que indica un cambio de temática entre párrafos
  10. <a></a>	
        Podremos escribir enlaces a otras páginas  
``` 

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
```
img src="fuente"/>          width="ancho"          height="altura"          class="Identificador" 
lang="lenguaje"             id="unico"             href ="enlaces":         align="alinear"
background-color="fondo"    style="estilo"

Ejemplo:   <a href="https://github.com/katherine-na" disabled <p style="color:pink; font-size: 20px">mi titulo de html</p>
```
## What are HTML global attributes?
Son atributos comunes a todos los elementos HTML; se pueden usar en todos los elementos. 
Atributos globales.
```
acceskey                    dir                     is                  lang                  title
autocapitalize              draggable               itemid              nonce                 translate
autocomplete                enterkeyhint            itemprop            slot                  dropzone
class                       hidden                  itemref             spellcheck
contentditable              inputmode               itemscope           style
contextmenu                 id                      itemtype            tabindex

```
![source](https://www.htmlquick.com/es/reference/attributes.html#:~:text=Los%20atributos%20son%20un%20mecanismo,o%20configuraciones%20para%20los%20elementos.



