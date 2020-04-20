# Comparadores de igualdad y desigualdad
Una de las cosas que llaman la atención cuando se llega a Javascript es el uso del comparador con `===` o `!==`. Para complicarlo aun mas, los operadores `==` y `!=` también están disponibles, pero su significado no es siempre el mismo.

Como guía de estilo básica, se deben utilizar `===` y `!==`.

El operador de igualdad (`==`) convierte los dos operandos de la expresión a un mismo tipo y después les aplica una comparación estricta. El operador de identidad, o igualdad estricta (`===`) compara que los operandos sean del mismo tipo y que sean iguales.

En el Javascript `ejemplos-javascript/src/comparadores1.js`{{open}} se ilustra la diferencia de estos comparadores.
Para ejecutarlo, puedes pulsar aquí: `node ejemplos-javascript/src/comparadores1.js`{{execute}}

## Igualdad entre 0, undefined y null
En Javascript, una variable puede estar también indefinida (`undefined`) o tener un valor nulo (`null`). Los operadores de comparación se comportan tal y como se puede ver ewn el Javascript `ejemplos-javascript/src/comparadores2.js`{{open}}.
Se puede ejecutar dicho Javascript pulsando aquí: `node ejemplos-javascript/src/comparadores2.js`{{execute}}

## Comparación de objetos
La comparación de dos objetos sólo va a dar true si los objetos comparados son el mismo objeto, independientemente de que internamente sean iguales o no.
Se puede ver un ejemplo en el Javascript `ejemplos-javascript/src/comparadores3.js`{{open}}.
Se puede ejecutar dicho Javascript pulsando aquí: `node ejemplos-javascript/src/comparadores3.js`{{execute}}

# Operadores relacionales
Como en otros lenguajes, se puede comparar con los operadores `>`, `<`, `>=` y `<=`.
En este caso, Javascript ejecuta el `valueOf()` de cada operando y después los compara.
Esto se puede ver en el siguiente ejemplo: `ejemplos-javascript/src/comparadores4.js`{{open}}. Parte de la sintaxis mostrada, se explicará mas adelante en este curso.
Se puede ejecutar dicho Javascript pulsando aquí: `node ejemplos-javascript/src/comparadores4.js`{{execute}}
