# CSS Introduction
CSS is the language we use to style a Web page.

## What's CSS?
CSS significa hojas de estilo en cascada, describe cómo se deben mostrar los elementos HTML en la pantalla.

## What’s CSS used for?

## CSS Syntax
- El selector apunta al elemento HTML que desea diseñar.
- El bloque de declaración contiene una o más declaraciones separadas por punto y coma.
- Cada declaración incluye un nombre de propiedad CSS y un valor, separados por dos puntos.
- Varias declaraciones CSS se separan con punto y coma, y los bloques de declaración están rodeados por llaves.
 
![](http://www.naiarafernandez.com/wp-content/uploads/2016/05/css-sintaxis.png)

## What’s a CSS selector?  
Selecciona los elementos HTML que desea diseñar.
Podemos dividir los selectores de CSS en cinco categorías:

| Categoría | Descripción |
| :------- |:------- |
| Selectores simples | selecciona elementos basados en nombre, id, clase |
| Selectores combinadores | Selecciona elementos en función de una relación específica entre ellos |
| Selectores de pseudoclase | Selecciona elementos en función de un determinado estado |
| Selectores de pseudoelementos | Selecciona y diseñar una parte de un elemento |
| Selectores de atributos | Seleccionar elementos en función de un atributo o valor de atributo |

## What are CSS properties?
Permiten asignar un valor a otras propiedades de CSS al mismo tiempo.

## How to add CSS (three ways to insert CSS) -> External CSS, Internal CSS, Inline CSS
- External CSS  
Se definen dentro del elemento <link>, dentro de la sección <head> de una página HTML:
```
 <link rel="stylesheet" href="mystyle.css">
```
 
 -Internal CSS  
 Se definen dentro del elemento <style>, dentro de la sección <head> de una página HTML:
```
<head>
<style>
body {
  background-color: linen;
}

h1 {
  color: maroon;
  margin-left: 40px;
}
</style>
</head>
```
