Desafíos:
Crear una función que muestre "¡Hola, mundo!" en la consola.
```javascript
function saludo(){
  console.log("¡Hola, mundo!");
}
```
Crear una función que reciba un nombre como parámetro y muestre "¡Hola, [nombre]!" en la consola.
```javascript
function hola(nombre){
  console.log(`¡Hola, ${nombre}!`);
}
function hola("ANGEL");
```
Crear una función que reciba un número como parámetro y devuelva el doble de ese número.
```javascript
function doblar(numero){
  return numero*2;
}
let resultado= doblar(5);
console.log(resultado);
```
Crear una función que reciba tres números como parámetros y devuelva su promedio.
```javascript
function promedio(a,b,c){
  return (a+b+c)/3;
}
let resultado = promedio(4,5,8);
console.log(resultado);

```
Crear una función que reciba dos números como parámetros y devuelva el mayor de ellos.
```javascript
function numeroMayor(a,b){
  return a>b ? a:b;
}
let resultadoMayor= numeroMayor(10,15);
console.log(resultadoMayor);
```
Crear una función que reciba un número como parámetro y devuelva el resultado de multiplicar ese número por sí mismo.
```javascript
function multiplicador(a){
  return a*a;
}
let cuadrado= multiplicador(5);
console.log(cuadrado);
```
