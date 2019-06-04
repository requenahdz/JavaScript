## Practicas de JavaScript

### Practica 1
Dado el siguiente arreglo de números realiza las siguientes practicas.
```
var arreglo=[12,32,41,43,81,26,73,78,27,77,85,56,16,96,21,63,69,80,90,23];
```

* Imprime en consola todos los números.
* Imprime en consola todos los números que sean pares.
* Imprime en consola todos los números que sean impares.
* Imprime en consola todos los números sean mayor a 50.
* Imprime en consola todos los números menor a 50.
* Imprime en consola todos los números contengan un 5 o 7.
* Imprime en consola todos los números que son primos.
* Imprime en consola todos los números mayores a 30 y menores a 80.
* Imprime en consola todos los númeroso ordenado de mayor a menor.
* Imprime en consola todos los números menor a mayor.

##### Código de ayuda
```
console.log("texto en consola");
```

### Practica 2
Crea la siguientes funciones.
* Crea una función que retorne la hora actual.
* Crea una función retorne la fecha del dia de hoy con el formato 18/Abril/2019.
* Crea una función retorne un número random del 1 al 100.
* Crea una función retorne un arreglo con 10 números random del 1 al 100 pero que no contenga el número 3, 5 y 7.
* Crea una función retorne el dia sera mañana. ejemplo "Jueves".
* Crea una función retorne el dia que fué el primer dia del mes actual. ejemplo "Miercoles".
* Crea una función retorne el número de dias que contiene el mes actual. Ejemplo "31";
* Crea una función retorne el dia que sera el último dia del mes actual. ejemplo "Viernes".
* Crea una función retorne el dia que sera el último dia del mes actual. ejemplo "Viernes".
##### Código de ayuda
```
function myFunction() {
  var miVariable='valor';
  return miVariable;
}
```


### Practica 3
Crea un formulario que sume, reste, multiplique y divida dos numeros dados, el resultado debe ser mostrado en una etiqueta div

##### Código de ayuda
```
//ETIQUETAS HTML

<input type="text" id="texto" placeholder="Escribe un texto.">
<button type="button" id="btn" >Aceptar</button>
<div id="resultado"></div>

//CODIGO JAVASCRIPT

//Muestra una alerta cuando el usuario hace clic en un elemento.
document.getElementById("btn").addEventListener("click", function() {

  //Obtiene el valor de un input.
  var texto=document.getElementById("texto").value;
  
  //Modifica contenido de un elemento.
  document.getElementById("resultado").innerHTML = texto;

});
```

### Practica 4
Crea una calendario en html utlizando solo javascript que muestre el mes actual. 
![alt text][logo]

[logo]: https://requenahdz.github.io/javascript/mes.png "Mes"

### Practica 5
Crear una formulario que ayuda a cifrar y descifrar oraciones con el método de cifrado César. 

El cifrado César es uno de los primeros métodos de cifrado conocidos históricamente. Julio César lo usó para enviar órdenes a sus generales en los campos de batalla. Consistía en escribir el mensaje con un alfabeto que estaba formado por las letras del alfabeto latino normal desplazadas tres posiciones a la derecha. <br>
Con nuestro alfabeto el sistema quedaría así:

Alfabeto en claro:	A B C D E F G H I J K L M N Ñ O P Q R S T U V W X Y Z <br>
Alfabeto cifrado:	  D E F G H I J K L M N Ñ O P Q R S T U V W X Y Z A B C

Por ejemplo, si se quiere enviar el mensaje DILLANMLP, lo que se escribirá realmente es GLÑÑDPOÑS

### Practica 6
Realiza una galería de imagenes con las siguientes acciones <br>
* Posibilidad de añadir más imágenes.<br>
* Posibilidad de remplazar imágenes.<br>
* Posibilidad de eliminar imágenes. <br>


### Dillan MLP
