
Pregunta al usuario qué día de la semana es. Si la respuesta es "Sábado" o "Domingo", muestra "¡Buen fin de semana!". De lo contrario, muestra "¡Buena semana!".
```javascript
let dia_semana = prompt('que dia de la semana es?);
if (dia_semana == Sábado || dia_semana == Domingo){
  alert("¡Buen fin de semana!);
}else{
  alert("¡Buena semana!");
}
```

Verifica si un número ingresado por el usuario es positivo o negativo. Muestra una alerta informativa.
```javascript
let numero= prompt('ingrese un numero');
if (numero>=0){
alert("su numero es positivo");
}else{
alert("su numero es negativo");
}
```
  
Crea un sistema de puntuación para un juego. Si la puntuación es mayor o igual a 100, muestra "¡Felicidades, has ganado!". En caso contrario, muestra "Intentalo nuevamente para ganar.".
```javascript
let puntuación = 120;
if ( puntuacion >= 100){
console.log("¡Felicidades, has ganado!");
}else{
console.log("Intentalo nuevamente para ganar.");
}
```
  
Crea un mensaje que informe al usuario sobre el saldo de su cuenta, utilizando un template string para incluir el valor del saldo.
```javascript
let saldo_cuenta= 300;
alert(`Tu saldo es de ${saldo_cuenta} dolares`);
```
Pide al usuario que ingrese su nombre mediante un prompt. Luego, muestra una alerta de bienvenida usando ese nombre.
```javascript
let nombre = prompt("ingrese su nombre:");
alert(`Bienvenido, ${nombre}`);

```
