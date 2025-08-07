Del proyecto de la carpeta js-curso-2-principal  ábrelo en Visual Studio Code.

Cambia el contenido de la etiqueta h1 con document.querySelector y asigna el siguiente texto: "Hora del Desafío".
```javascript
let titulo = document.querySelector('h1');
titulo.innerHTML="Hora del Desafío";
```
Crea una función que muestre en la consola el mensaje "El botón fue clicado" siempre que se presione el botón "Console".
En el index.html , agregamos en el onclick el siguiente código:
```HTML
<button onclick="mostrar_mensaje_consola()" class="button">Console</button>
```
En el app.js
```javascript
function mostrar_mensaje_consola(){
    alert('El botón fue clicado');
}
```
Crea una función que se ejecute cuando se haga clic en el botón "prompt", preguntando el nombre de una ciudad de Brasil. Luego, muestra una alerta con el mensaje concatenando la respuesta con el texto: "Estuve en {ciudad} y me acordé de ti".

```HTML
<button onclick="mostrar_prompt();" class="button">Prompt</button>
```
```javascript
function mostrar_prompt(){
    let ciudad = prompt('Escriba la ciudad:');
    alert(`Estuve en ${ciudad} y me acordé de ti`);
}
```
Crea una función que muestre una alerta con el mensaje: "Yo amo JS" siempre que se presione el botón "Alerta".
```HTML
<button onclick="mostrar_alert();" class="button">Alert</button>
```
```javascript
function mostrar_alert(){
    alert('Yo amo JS');
}
```
Al hacer clic en el botón "suma", pide 2 números y muestra el resultado de la suma en una alerta.
```HTML
<button onclick="mostrar_suma();" class="button">Suma</button>
```
```javascript
function mostrar_suma(){
    let numero1= parseInt( prompt('Escribir el primer numero:'));
    let numero2= parseInt(prompt('Escribir el segundo numero:'));

    let suma= numero1+ numero2;

    alert(`la suma de ${numero1} y ${numero2} es ${suma}`);
}
```
