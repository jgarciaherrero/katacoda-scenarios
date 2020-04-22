# Funciones
Una función en Javascript se puede declarar con la siguiente sintaxis clásica:
```javascript
function diHola(nombre) {
    console.info("Hola " + nombre);
}

diHola('Estudiante');
```

Javascript permite que una variable sea de tipo función, de manera que, tras el anterior código se podría tener algo como lo siguiente:
```javascript
let funSaludo = diHola;
```

O incluso pasar una función como parámetro de otra. Esto último se suele utilizar mucho en funciones asíncronas para indicar a qué código llamar cuando acabe la función principal. Se verá su uso cuando entremos a trabajar con `gatewayscript`.

Esto se puede ver en el fuente `ejemplos-javascript/src/funciones2.js`{{open}} que se puede ejecutar con la sentencia: `node ejemplos-javascript/src/funciones2.js`{{execute}}.

## Funciones flecha
Se puede expresar una función de una manera mas corta utilizando la "fat arrow". Se suele utilizar para dar al lenguaje un aspecto más funcional.

Esto se puede ver en el fuente `ejemplos-javascript/src/funciones3.js`{{open}} que se puede ejecutar con la sentencia: `node ejemplos-javascript/src/funciones3.js`{{execute}}.
