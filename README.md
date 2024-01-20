# ![](https://app.aluracursos.com/assets/images/logos/logo-aluraespanhol.svg) Programa One Alura + Oracle Next Education. 

### Responsables:
- Cristian Velasco Head de Alura Latam
- Amanda Gelumbauskas


### Detalles:
- Curso de 6 meses: hard & soft skills, metodologias, back & front end, programación, datos
- 2 Meses de preselección
- 4 meses de curso front end o back end
    - Front: interfaz gráfica con React utilizando HTML, CSS, Javascript
    - Back: Java, spring (Spring es un framework para el desarrollo de aplicaciones y contenedor de inversión de control, de código abierto para la plataforma Java)
 
### Cronograma:

- 2 meses de selección. 
	- Miercoles 17 de enero se libera el curso de iniciante en programación
	- Martes 23 de enero Challenge Encriptador + live 9pm
	- Jueves 25 de enero último día para completar el primer curso Curso Lógica de programación (javascript)
	- Lunes 4 de marzo Live 9pm
	- Miercoles 20 de marzo fecha final para completar los cursos de principiante en programación
	- Semana de 21 a 27 de marzo, semana de ??
- Luego del proceso de selección, se puede elegir entre front o back

### Cursos
- [Iniciación a la programación](#Curso-I-Iniciacion-a-la-programacion)


![](https://github.com/analopbec/ONE_oracle/blob/main/img/crono2.jpg)


### Requisitos:
- Finalizar cursos, pruebas y challenges (asincrónicos)
		
  
```
//bloque de codigo...		
```



# Curso I Iniciacion a la programacion

## Javascript

![¿Qué es JavaScript?](https://developer.mozilla.org/es/docs/Learn/JavaScript/First_steps/What_is_JavaScript)

![Guía Javascript](https://www.aluracursos.com/blog/guia-de-javascript)

![Primer Programa: ](https://github.com/analopbec/logica-programacion1) 


### Contenido Inicial

NaN —> not a number
==
&&
===
!=
!==
null

- Buenas prácticas: utilizar ";"
	- Fin de Archivo
	- llave de cierre
	- luego de palabras reservadas (break, 

- Alertar, mostrar un mensaje en un pop-up de la página --> alert('Hola Mundo');
- Incluir el archivo .js en el archivo html: <script src="app.js"></script>
- Pedirle que ingrese un dato al usuario --> prompt

- Console.log --> visualiza en la consola
- Comentar: //comentario /* comentario */
- typeof(variable) —> me trae el tipo de mensaje
- Para que aparezca en la pantalla del html: documento.writeln(“mensaje”, sumaPruba)
- parseInt() --> garantiza que sea un número

- limpiar pantalla: console.log(clear)


### Variables
- Variables: en camelCase (let) o (var) y constante (const)

#### Como saber si usar var, let o const??
- Var es una variable que sin importar donde la declaremos, vamos a poder acceder a ella desde cualquier lugar del código
- let solo y unicamente dentro de un bloque de código en particular
- const es un tipo de variable pensada para que no pueda cambiar en todo el programa --> solo lectura
Actualmente no se recomienda usar var. Es  mejor utilizar let o const. Debido a que 'var', permite volver a declarar la misma variable, o cambiar el contenido de esta variable desde otro scope. Lo cual puede generar errores y no lo sabrias. En cambio let o const no permite esto, y te avisa si una variable con el mismo nombre ya ha sido declarada.




### Condicionales: 
- if (condicion) {} else {}
- Operador ternario: --> condicion? hacer esto : si no otra cosa	
```
If(variable >4){
consolé.log(sdfsd) —> que hacemos si se cumple la funcion
} else If (variable=4) {
if() {} else {}
} else {}

```


Expresión regular para saber si un nombre contiene letras y estaciones --> Devuelve true o false
```
Var nombre = prompt(“ingrese nombre“)
var nombreTest = /ˆ[A-Za-z\s]+$/.test(nombre)
```

Swich —> analizar casos posibles específicos. Por ejemplo calificaciones, días de semana etc
```
switch(variable){
	case valor1:
		hacer algo ej alert(“lunes”)
		break;
	case valor2:
		hacer algo ej alert(“martes)
		break;
	etc….
	default:
		equivale al else
		break;
}
```


### Bucles

#### - While --> primero se inicializa un contador i = 0
- do while
  
```
While (i < 5) {
	hacer algo
	i = i + 1 // i++ // contador++
}

let contador = 0
While (contador <10)
	console.log(`cuenta: ${contador}`);
	contador++;

```

#### - For --> For(inicialización; condición; contador)

```
For(inicialización; condición; contador)
for( var/let i=1; i<10; i++){
hacer algo;
}

```
### Funciones

```
function nombreFuncion() {
	hacer algo
}

```

- Objetos 

```
const nombre = {
	lista: [],
	atributo: numero,
	atributo2: true,
	metodo(){
		this.atributo +=1},
metodo(atributo){
	return xxxx
},
metodo3(){
	if(pasa algo) {this.atributoxxxxx}
else {this.atributo pasa otra cosa}
},
metodo4(algo){ return this.atributo ? Algo : otra cosa}
```

- Listas:
	 - Math.max(0,variable) // Math.min
	 - Math.round o .toFixed(2) para 2 decimales
	 - Lista.filter(x=> x > y) // Lista.reduce((a,b) => a + b , 0)
	 - .every // .map // .some // .length. // .includes(algo) // .apply() //
	 - Math.max(…this.lista) // Lista.push(…otraLista)
	 - .pop saca elementos lista.pop() borra el ultimo o shift o slice o splice
	 - Splice(posición,borrar,agregar,agregar…)


### Clases

```
class ejemplo {
	#name —> atributo privado
	constructor(nombre, precio, detalle) {
	this.#name = nombre;
	this.prec = precio;
	}
	metodo(){
	}
	metodo2(precio){
	return xxx
	}
} 

```
module.exports = {ejemplo}
const {ejemplo} = require(‘.pagina.js’)
const plancha = new ejemplo("Pepe", 2, true)

### Funcion random
- Generar un numero aleatorio entre un minimo y un máximo

```
// op 1
random = Math.floor(min + Math.random() * max);

// op 2
function random(min, max) {
  return Math.floor(min + Math.random() * (max - min));
}

alert( random(1, 5) );

//op 3
function getRandomInt(max){
  return Math.floor(Math.random() * max);
}


```


### Libreria Math

- Math.floor() --> lleva al numero entero menor (no redondea)
- Math.random() // aleatorio entre entre 0 y 1
- Math.max(a,b) el maximo entre a y b
- Math.min(a,b) el minimo entre a y b
- Math.round() redondea el numero
