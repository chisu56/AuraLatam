Crea un programa que utilice console.log para mostrar un mensaje de bienvenida.
```javascript
console.log('Bienvenido');
```
Crea una variable llamada "nombre" y asígnale tu nombre. Luego, utiliza console.log para mostrar el mensaje "¡Hola, [tu nombre]!" en la consola del navegador.
```javascript
let nombre = 'Angel';
console.log(`¡Hola, ${nombre}!`);
```
Crea una variable llamada "nombre" y asígnale tu nombre. Luego, utiliza alert para mostrar el mensaje "¡Hola, [tu nombre]!".
```javascript
let nombre = 'Angel';
alert(`¡Hola, ${nombre}!`);
```
Utiliza prompt y haz la siguiente pregunta: ¿Cuál es el lenguaje de programación que más te gusta?. Luego, almacena la respuesta en una variable y muestra la respuesta en la consola del navegador.
```javascript
let respuesta = prompt(' ¿Cuál es el lenguaje de programación que más te gusta?');
console.log(respuesta);
```
Crea una variable llamada "valor1" y otra llamada "valor2", asignándoles valores numéricos de tu elección. Luego, realiza la suma de estos dos valores y almacena el resultado en una tercera variable llamada "resultado". Utiliza console.log para mostrar el mensaje "La suma de [valor1] y [valor2] es igual a [resultado]." en la consola.
```javascript
let valor1 = 13;
let valor2 = 7;
let resultado= valor1 + valor2;
console.log(`La suma entre ${valor1} y ${valor2} es igual a ${resultado}.`)
```
Crea una variable llamada "valor1" y otra llamada "valor2", asignándoles valores numéricos de tu elección. Luego, realiza la resta de estos dos valores y almacena el resultado en una tercera variable llamada "resultado". Utiliza console.log para mostrar el mensaje "La diferencia entre [valor1] y [valor2] es igual a [resultado]." en la consola.
```javascript
let valor1 = 13;
let valor2 = 7;
let resultado= valor1 - valor2;
console.log(`La diferencia entre ${valor1} y ${valor2} es igual a ${resultado}.`)
```
Pide al usuario que ingrese su edad con prompt. Con base en la edad ingresada, utiliza un if para verificar si la persona es mayor o menor de edad y muestra un mensaje apropiado en la consola.
```javascript
edad = prompt('Ingresa tu edad:');
if (edad > 17) {
console.log('Eres mayor de edad.');
} else {
console.log('Eres menor de edad.');
}
```
Crea una variable "numero" y solicita un valor con prompt. Luego, verifica si es positivo, negativo o cero utilizando un if-else y muestra el mensaje correspondiente.
```javascript
numero = parseFloat(prompt("Ingresa un número:"));
if (numero > 0) {
  console.log("El número es positivo.");
} else if (numero < 0) {
  console.log("El número es negativo.");
} else {
  console.log("El número es cero.");
}
```
Utiliza un bucle while para mostrar los números del 1 al 10 en la consola.
```javascript
numero = 1;
while (numero <= 10) {
  console.log(numero);
  numero++;
}
```
Crea una variable "nota" y asígnale un valor numérico. Utiliza un if-else para determinar si la nota es mayor o igual a 7 y muestra "Aprobado" o "Reprobado" en la consola.
```javascript
 nota = 8; // Reemplaza con el valor de la nota que deseas probar
if (nota >= 7) {
  console.log("Aprobado");
} else {
  console.log("Reprobado");
}
}
```
Utiliza Math.random para generar cualquier número aleatorio y muestra ese número en la consola.
```javascript
numeroAleatorio = Math.random();
console.log(numeroAleatorio);
```
Utiliza Math.random para generar un número entero entre 1 y 10 y muestra ese número en la consola.
```javascript
numeroIntAleatorio = parseInt(Math.random() * 10) + 1;
console.log(numeroIntAleatorio);
```
Utiliza Math.random para generar un número entero entre 1 y 1000 y muestra ese número en la consola.
```javascript
numeroIntAleatorio = parseInt(Math.random() * 1000) + 1;
console.log(numeroIntAleatorio);
```
