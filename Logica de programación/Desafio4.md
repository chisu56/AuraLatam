Crea una lista vacía llamada "listaGenerica".
```javascript
let listaGenerica = [];
```
Crea una lista de lenguajes de programación llamada "lenguagesDeProgramacion con los siguientes elementos: 'JavaScript', 'C', 'C++', 'Kotlin' y 'Python'.
```javascript
let lenguagesDeProgramacion = ['JavaScript', 'C', 'C++', 'Kotlin', 'Python'];
```
Agrega a la lista "lenguagesDeProgramacion los siguientes elementos: 'Java', 'Ruby' y 'GoLang'.
```javascript
let lenguagesDeProgramacion = ['JavaScript', 'C', 'C++', 'Kotlin', 'Python'];
lenguagesDeProgramacion.push('Java', 'Ruby', 'GoLang');
```
Crea una función que muestre en la consola todos los elementos de la lista "lenguagesDeProgramacion.
```javascript
let lenguagesDeProgramacion = ['JavaScript', 'C', 'C++', 'Kotlin', 'Python'];
lenguagesDeProgramacion.push('Java', 'Ruby', 'GoLang');
function mostrarLenguages() {
  for (let i = 0; i < lenguagesDeProgramacion.length; i++) {
    console.log(lenguagesDeProgramacion[i]);
  }
}

mostrarLenguages();
```
Crea una función que muestre en la consola todos los elementos de la lista "lenguagesDeProgramacion en orden inverso.
```javascript
function mostrarLenguagesReverso() {
  for (let i = lenguagesDeProgramacion.length - 1; i >= 0; i--) {
    console.log(lenguagesDeProgramacion[i]);
  }
}

mostrarLenguagesReverso();
```
Crea una función que calcule el promedio de los elementos en una lista de números.
```javascript
function calcularMedia(lista) {
  let suma = 0;
  for (let i = 0; i < lista.length; i++) {
    suma += lista[i];
  }
  return suma / lista.length;
}

let numeros = [10, 20, 30, 40, 50];
let media = calcularMedia(numeros);
console.log('Média:', media);
```
Crea una función que muestre en la consola el número más grande y el número más pequeño en una lista.
```javascript
function encontrarMayorMenor(lista) {
  let mayor = lista[0];
  let menor = lista[0];

  for (let i = 1; i < lista.length; i++) {
    if (lista[i] > mayor) {
      mayor = lista[i];
    }
    if (lista[i] < menor) {
      menor = lista[i];
    }
  }

  console.log('Mayor:', mayor);
  console.log('Menor:', menor);
}

let numeros = [15, 8, 25, 5, 12];
encontrarMayorMenor(numeros);
```

Crea una función que devuelva la suma de todos los elementos en una lista.
```javascript
function calcularSuma(lista) {
  let suma = 0;
  for (let i = 0; i < lista.length; i++) {
    suma += lista[i];
  }
  return suma;
}

let numeros = [15, 8, 25, 5, 12];
let suma = calcularSuma(numeros);
console.log('Suma:', suma);
```

Crea una función que devuelva la posición en la lista donde se encuentra un elemento pasado como parámetro, o -1 si no existe en la lista.
```javascript
   function encontrarIndiceElemento(lista, elemento) {
     for (let i = 0; i < lista.length; i++) {
       if (lista[i] === elemento) {
         return i; // Retorna el índice del elemento encontrado
       }
     }
     return -1; // Retorna -1 si el elemento no se encuentra en la lista
   }
   ```

Crea una función que reciba dos listas de números del mismo tamaño y devuelva una nueva lista con la suma de los elementos uno a uno.
  ```javascript
    function sumarListas(lista1, lista2) {
        return lista1.map((num, index) => num + lista2[index]);
    }
    
    const lista1 = [1, 2, 3];
    const lista2 = [4, 5, 6];
    const resultado = sumarListas(lista1, lista2);
    console.log(resultado);  
    
    ```

Crea una función que reciba una lista de números y devuelva una nueva lista con el cuadrado de cada número.
```javascript
function cuadradoLista(lista) {
    return lista.map(num => num ** 2);
}

const lista = [2, 3, 4];
const resultado = cuadradoLista(lista);
console.log(resultado);  

```
