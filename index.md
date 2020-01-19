---
layout: default
---

# JavaScript Object Notation

JSON es un formato ligero de intercambio de datos basado en texto plano definido por [Douglas Crockford](https://crockford.com) en 2002.

## Introducción

El intercambio de datos en la informática es la transmisión estructurada de información entre sistemas o aplicaciones totalmente independientes. Para que esta transmisión sea posible y la información comprensible para todo tipo de sistemas o aplicaciones debemos estructurar la información a transmitir siguiendo unos estándares comunes para todos, estos son los formatos de intercambio de datos. Algunos de los formatos de intercambio de datos más populares son XML, CSV o el propio JSON.
Hasta finales de la década de los 90, XML o lenguaje de marcas extensible era el estandar de transmisión de datos por excelencia pese a que presentaba problemas cuando trabajábamos con grandes volúmenes de datos debedido a la exceso de cantidad de carcacteres añadidos por la sintaxis basada en etiquetas de XML.

### Ejemplo de XML
```xml
<alumno>
  <nombre>Douglas</nombre>
  <apellido>Crockford</apellido>
  <telefono>123456789</telefono>
  <curso>
    <nivel>Primero</nivel>
    <modalidad>Ciencias de la Computación</modalidad>
  </curso>
</alumno>
```
*Tamaño en disco del ejemplo: 217 bytes*

## ¿Qué es JSON?

JSON son las siglas de JavaScript Object Notation, que no es más que un lenguaje de transmisión y almacenamiento de datos basado en texto plano, esto significa que la información será almacenada en ficheros de texto plano en lugar de información binaria. 
JSON es un estandar ligero que se caracteriza por reducir el tamaño de los archivos y el volumen de datos que es necesario transmitir frente a otros estándares como XML, es por ello que desde su aparición su popularidad y uso mantiene un constante crecimiento. 
Un archivo JSON es una cadena de texto, que sigue una estructura y una sintaxis, que es capaz de ser interpretado por un analizador sintáctico o *parser*\* e incorporar la información contenida al lenguaje de programación deseado. A este proceso se le denomina *parsing*, mientras que el proceso contrario, que consiste en almacenar un objeto o una estructura de datos en una cadena de texto para ser transmitida o almacenada, se conoce como *stringification*.
JSON es un estandar independiente del lenguaje de programación por lo que es compatible con la mayoría de lenguajes de programación, bien de forma nativa como es el caso de JavaScript o PHP (desde la versión 5.2) o bien mediante librerías de terceros como pueden ser [JSON-java](https://github.com/stleary/JSON-java) para Java o [JsonBox](https://github.com/anhero/JsonBox) para C++.

*Un analizador sintáctico, parser en inglés, es un programa informático que analiza una cadena de símbolos de acuerdo a las reglas de una gramática formal definida.*

### Ejemplo de JSON
```json
{
  "nombre" : "Douglas",
  "apellido" : "Crockford",
  "telefono" : 123456789,
  "curso" : {
    "nivel" : "Primero",
    "modalidad" : "Ciencias de la Computación"
  }
}
```
*Tamaño en disco del ejemplo: 163 bytes*

## JSON y XML

En proceso.

## Objetos en JavaScript

JSON recibe su nombre debido a que se basa en un subconjunto de la notación literal de objetos en JavaScript, pese a ser completamente independiente de este, por lo que no podemos definir la sintaxis de JSON sin hablar antes de los propios objetos de JavaScript, ya que en la definición de estos se basa la sintaxis de JSON.
Pero, ¿qué es un objeto? Un objeto es una unidad o estructura dentro de un programa que tiene un estado y un comportamiento. Es decir, tiene una serie de datos almacenados y tareas que este es capaz de realizar.
Hay varias formas de [definir objetos en JavaScript](https://developer.mozilla.org/es/docs/Web/JavaScript/Guide/Trabajando_con_objectos#Creando_nuevos_objetos): mediante el uso de inicializadores de objeto, mediante una función constructora o usando el método Object.create.
La inicialización de un objeto, también denominado como la notación literal de este, es la forma que JavaScript nos ofrece para crear un nuevo objeto mediante la siguiente sintaxis:
```js
var objeto = {
    propiedad1 : valor1,
    propiedad2 : valor2,
    // ...
} 
```
Esta es la sintaxis en la que se basa JSON, en la definición de un objeto como un conjunto de pares **clave-valor** donde clave ha de ser una cadena de caracteres limitada por doble comilla y valor cualquiera de los tipos disponibles en JSON, que se especificarán más adelante, todo esto limitado por llaves.

## Sintaxis de JSON

En proceso.

## Lenguajes soportados

En proceso.