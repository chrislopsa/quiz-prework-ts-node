# quiz-prework-ts-node

1)JavaScript Básico:
Describe qué es una función en JavaScript y cómo se declara.
--es un bloque de código cuya trabajo es recibir unos datos o informacion, procesarlas y devolver un valor en base a eso. en JS  hay 2 tipos de funciones, las funciones declaradas: function my_funcion(){} y las funciones de flecha: function ()=>{}

2) Manipulación del DOM:
Explica cómo seleccionar un elemento del DOM y cambiar su contenido.

--usando el los metodos de la clase document, ejemplo: document.getElementById, document.getElementbyClassname, y posteriormente con el metodo inner.HTML y backtips agrego el contenido HTML nuevo.

3)Programación Orientada a Objetos (OOP):
¿Qué es una clase en JavaScript y cómo se define una?

--

4) Eventos en JavaScript:
¿Cómo se agrega un evento de clic a un botón en JavaScript?
--selecciono primero el elemento del DOM y con el metodo addEventListenner, ejemplo: myelement.addEventListenner("click",()=>{}).

5)Variables y Tipos de Datos:
Explica las diferencias entre var, let, y const en JavaScript.
--var: es la manera antigua de declarar variables, tiene un scope global y dicha variable puede ser accedida desde cualquier lugar del código, esto puede ser contraproducente.
let: es otra manera de declarar variables pero esta tiene un contexto de ejecución de bloque, lo que hace que no pueda ser accedida desde cualquier lugar del código.
const: es la manera de declarar constantes, osea valores que no van a variar a lo largo de la ejecucion del código, estos deben ser inicializados en el momento de la declaración.

6)Control de Flujo:
¿Qué son las estructuras de control de flujo y cuáles son algunas de las más comunes en JavaScript?
--son las estructuras que me permiten controlar cuantas veces se repetira una porcion de codigo en respuesta a un evento, las mas comunes son los ciclos for, las sentencias if, else, y while.

7)Funciones de Flecha:
Describe qué es una función de flecha en JavaScript y proporciona un ejemplo de cómo se usa.
-- es una funcion que puede ser anonima y la idea es simplificar la escritura y lectura del codigo, estas no tienen hoisting, arrow_function ()=>{}:
arrow_function: nombre de la funcion(opcional)
() :aqui van los argumentos, si son dos o mas son obligatorios
=>: indica que es una arrow function
{}:indica el bloque de codigo donde la funcion hace su proceso, en ocasiones es opcional.

8)JSON:
¿Qué es JSON y cómo se utiliza en JavaScript?
--es un tipo de archivo para manejar datos basado en la estructura Clave-Valor, se puede usar en javascript como el documento que contiene la informacion y yo pueda trabajar con ella.

9)Promesas:
Explica qué es una promesa en JavaScript y proporciona un ejemplo de su uso.
-- es una peticion a un servidor externo, se dice promesa porque yo debo esperar la respuesta y en base a esa respuesta ejecutar una porcion de codigo, ejm:
quiero solicitar todos los vuelos reservados para el dia de hoy y mostrarlos en pantalla, debo hacer la peticion a la BD, si la peticion es de respuesta positiva hago algo, si por alguna razon la BD no me devuelve nada, ejecuto otra porcion de codigo.


10)Depuración:
¿Cuáles son algunas de las herramientas o métodos que se pueden usar para depurar código JavaScript?
--console.log()


Preguntas de Selección Múltiple (20)
¿Cuál de las siguientes es la forma correcta de declarar una variable en JavaScript?
A) var myVariable; 
B) variable myVariable;
XC) let myVariable;
D) A y C son correctas.

¿Qué método se utiliza para agregar un elemento al final de un array en JavaScript?
XA) push()
B) pop()
C) shift()
D) unshift()

¿Cuál de los siguientes operadores se utiliza para comparar tanto el valor como el tipo de dos variables en JavaScript?
A) ==
XB) ===
C) !=
D) !==

¿Cuál es la salida del siguiente código?
console.log(typeof null);
A) null
XB) undefined
C) object
D) number

¿Cuál de los siguientes métodos se usa para recorrer todos los elementos de un array?
A) forEach()
B) map()
C) filter()
XD) Todas las anteriores

¿Qué se entiende por “hoisting” en JavaScript?
XA) Declaraciones de variables y funciones se mueven al principio de su ámbito.
B) Es un término para describir la eliminación de variables.
C) Es un método para agrupar varias funciones.
D) Ninguna de las anteriores.

¿Cuál es la diferencia entre null y undefined en JavaScript?
A) null significa que una variable ha sido declarada pero no definida, undefined significa que no se ha declarado.
XB) null es un valor asignado intencionalmente, undefined significa que una variable no tiene valor.
C) undefined es un valor asignado intencionalmente, null significa que una variable no tiene valor.
D) No hay diferencia.

¿Cuál es el propósito del método Array.prototype.map()?
XA) Modificar el array original.
B) Crear un nuevo array con los resultados de aplicar una función a cada elemento del array original.
C) Filtrar los elementos de un array.
D) Encontrar un elemento en un array.

¿Qué es el Event Loop en JavaScript?
A) Un ciclo que controla las llamadas recursivas.
XB) Un proceso que permite a JavaScript realizar operaciones asincrónicas.
C) Un método para iterar sobre arrays.
D) Ninguna de las anteriores.

¿Cuál es la salida del siguiente código?

console.log(0.1 + 0.2 === 0.3);
A) true
XB) false
C) undefined
D) NaN

¿Qué se entiende por strict mode en JavaScript?

A) Un modo que permite utilizar características experimentales.
B) Un modo que cambia la forma en que se ejecuta JavaScript, haciéndolo más seguro.
C) Un método para validar datos.
XD) Ninguna de las anteriores.

¿Cuál de las siguientes es una forma correcta de crear un objeto en JavaScript?

A) let obj = {};
B) let obj = Object.create();
C) let obj = new Object();
XD) A y C son correctas.

¿Qué es un callback en JavaScript?

XA) Una función que se pasa como argumento a otra función.
B) Un tipo de variable especial.
C) Un método para declarar funciones.
D) Ninguna de las anteriores.

¿Cuál es el propósito de async y await en JavaScript?

A) Ejecutar funciones síncronas.
XB) Manejar operaciones asincrónicas de manera más simple y legible.
C) Declarar variables globales.
D) Ninguna de las anteriores.

¿Cuál de las siguientes es una estructura de datos inmutable en JavaScript?

A) Arrays
B) Strings
C) Objetos
XD) Ninguna de las anteriores.

¿Cómo se puede convertir un objeto JSON en una cadena de texto en JavaScript?

A) JSON.parse()
B) JSON.stringify()
XC) toString()
D) parseInt()

¿Qué es un Promise en JavaScript?

A) Una función que se ejecuta inmediatamente.
XB) Un objeto que representa la eventual finalización (o falla) de una operación asincrónica.
C) Un método para declarar variables.
D) Ninguna de las anteriores.

¿Qué método se utiliza para agregar uno o más elementos al principio de un array y devolver la nueva longitud del array?

A) push()
B) pop()
XC) shift()
D) unshift()

¿Cuál es la diferencia entre localStorage y sessionStorage en JavaScript?

A) localStorage almacena datos solo durante la sesión del navegador, sessionStorage almacena datos de manera persistente.
XB) sessionStorage almacena datos solo durante la sesión del navegador, localStorage almacena datos de manera persistente.
C) No hay diferencia entre ellos.
D) Ambos almacenan datos solo durante la sesión del navegador.

¿Qué método se utiliza para detener la propagación de un evento en el DOM?

XA) event.stopPropagation()
B) event.preventDefault()
C) event.stop()
D) event.cancel()
