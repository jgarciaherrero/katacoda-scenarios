# Comparadores de igualdad y desigualdad
Una de las cosas que llaman la atención cuando se llega a Javascript es el uso del comparador con `===` o `!==`. Para complicarlo aun mas, los operadores `==` y `!=` también están disponibles, pero su significado no es siempre el mismo.

Como guía de estilo básica, se deben utilizar `===` y `!==`.

El operador de igualdad (`==`) convierte los dos operandos de la expresión a un mismo tipo y después les aplica una comparación estricta. El operador de identidad, o igualdad estricta (`===`) compara que los operandos sean del mismo tipo y que sean iguales.

En el Javascript `ejemplos-javascript/src/comparadores1.js`{{open}} se ilustra la diferencia de estos comparadores.
Para ejecutarlo, puedes pulsar aquí: `node ejemplos-javascript/src/variables.js`{{execute}}

