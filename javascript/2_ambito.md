# El ámbito de las variables y cómo se declaran
En Javascript se pueden declarar variables con tres comandos distintos: `var`, `let` y `const`.

La diferencia entre `var` y `let` es que el ámbito de las variables declaradas con `var` es global, mientras que las variables declaradas con `let` son locales al ámbito en que se declaran (esto hace más recomendable el uso de `let` para evitar efectos laterales).

En el siguiente ejemplo se ilustra que ocurre con las variables declaradas de las maneras indicadas en función de cómo se hayan declarado:

`ejemplos-javascript/src/variables.js`{{open}}

`node ejemplos-javascript/src/variables.js`{{execute}}

Como se puede ver, la variableConVar declarada dentro del bloque, se mantiene al salir de éste, a diferencia de la variable declarada con `let`. El comportamiento del `const` es, en este sentido, similar al `let`.

## Diferencia entre `let` y `const`
La diferencia es que el `const`, como indica su nombre, sirve para declarar constantes y, por tanto, si tratamos de asignarle un nuevo valor a una constante, dará error.