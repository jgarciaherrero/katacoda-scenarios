# Array.map()
Llama a una función que devuelve el elemento transformado para cada elemento del array.
```
var nuevo_array = arr.map(function callback(currentValue, index, array) {
    // Elemento devuelto de nuevo_array
}[, thisArg])
```
Al map se le pasa como parámetro una función que tiene como argumentos:
- el valor del elemento
- el índice del elemento
- el array que está siendo recorrido
y devuelve el array con los elementos transformados.

Esto se puede ver en el siguiente ejemplo:
`formacion-javascript-array/src/ejemplo3.js`{{open}}

Para ejecutarlo:
`node formacion-javascript-array/src/ejemplo3.js`{{execute}}
