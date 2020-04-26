# Operadores lógicos
Los operadores lógicos sirven para operar con booleanos como en otros lenguajes. Tenemos los siguientes:
- NOT	&rArr;	`!`
- AND	&rArr;	`&&`
- OR	&rArr;	`||`

Como ocurre con el == o el !=, Javascript primero convierte los operandos a booleanos y luego aplica el operador devolviendo el último valor utilizado. De esta manera:
```
true && true es true		true || false es true
1 && 2 es 2			1 || 2 es 1
0 && 1 es 0			0 || 1 es 1
undefined && 1 es undefined	undefined || 1 es 1
```

Esto se puede ver y probar en el Javascript `ejemplos-javascript/src/operadoresLogicos.js`{{open}}.
Para ejecutarlo, pulsa aquí:  `node ejemplos-javascript/src/operadoresLogicos.js`{{execute}}

