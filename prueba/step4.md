# Array.filter()
Llama a una función por cada elemento del array que devuelve true o false en función de si cumple el criterio de filtrado
```
var newArray = arr.filter(callback(currentValue[, index[, array]])[, thisArg])
```
Al filter se le pasa como parámetro una función que tiene como argumentos:
- el valor del elemento
- el índice del elemento
- el array que está siendo recorrido
y devuelve el array de elementos que cumplen la condición evaluada a true.

Esto se puede ver en el siguiente ejemplo:
`formacion-javascript-array/src/ejemplo4_1.js`{{open}}

Para ejecutarlo:
`node formacion-javascript-array/src/ejemplo4_1.js`{{execute}}

# Array.find()
Llama a una función por cada elemento del array que devuelve true o false en función de si cumple el criterio de filtrado.
```
arr.find(callback(element[, index[, array]])[, thisArg])
```
Al filter se le pasa como parámetro una función que tiene como argumentos:
- el valor del elemento
- el índice del elemento
- el array que está siendo recorrido
y devuelve el primer elemento del array que cumple la condición evaluada a true.

Esto se puede ver en el siguiente ejemplo:
`formacion-javascript-array/src/ejemplo4_2.js`{{open}}

Para ejecutarlo:
`node formacion-javascript-array/src/ejemplo4_2.js`{{execute}}
