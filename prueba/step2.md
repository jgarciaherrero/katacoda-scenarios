# Array.forEach()
Llama a una función por cada elemento del array.
```
arr.forEach(function callback(currentValue, index, array) {
    // tu iterador
}[, thisArg]);
```
Al forEach se le pasa como parámetro una función que tiene como argumentos:
- el valor del elemento
- el índice del elemento
- el array que está siendo recorrido

Esto se puede ver en el siguiente ejemplo:
`formacion-javascript-array/src/ejemplo2_1.js`{{open}}

Para ejecutarlo:
`node formacion-javascript-array/src/ejemplo2_1.js`{{execute}}

Este código se puede reducir de la siguiente manera:
`formacion-javascript-array/src/ejemplo2_2.js`{{open}}

Para ejecutarlo:
`node formacion-javascript-array/src/ejemplo2_2.js`{{execute}}
