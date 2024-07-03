# quiz-prework-ts-node
Preguntas Abiertas (10)
JavaScript Básico:
Describe qué es una función en JavaScript y cómo se declara.

una funcion es un bloque que contiene varias lineas las cuales desarrollan una logica y devuelve un resultado. este bloque es llamado funcion y tiene varias formas de ser declarado. se declara mediante la palabra func, o puede ser una arrow function que seria () => {} o esta la anonima que seria function() {}

Manipulación del DOM:
Explica cómo seleccionar un elemento del DOM y cambiar su contenido.
hay varias formas de aproximarse, todas son metodos del documento, está el GetElementById, QuerySelector y otros, esto depende de las necesidades y lo que se quiera modificar. si lo que se le quiere modificar son attributos entonces se hace con los metodos de atributos, si lo que desea es cambiar el contenido hmtl entonces se hace con los metodos innerhtml, outterhtml y otros y se le asigna en string lo que se quiera modificar.

Programación Orientada a Objetos (OOP):

¿Qué es una clase en JavaScript y cómo se define una?
una clase es una estructura que se predetermina para controlar los atributos de algun elemento especifico, este puede tener metodos(siempre debe tener el constructor) que nos permiten modificar el valor de los atributos ya determinados.

la clase se define escribiendo la palabra class seguida del nombre y ahi ya se le asigna el contenido


Eventos en JavaScript:

¿Cómo se agrega un evento de clic a un botón en JavaScript?
hay dos formas, se puede poner mediante un escuchador de eventos o tambien los botones en html contienen un atributo que nos permite captar el evento y ejecutar una funcion.



Variables y Tipos de Datos:

Explica las diferencias entre var, let, y const en JavaScript.
var y let funcionan de manera muy parecida, pues ambas declaran varaiables con son cambiantes en el tiempo, sin embargo, hay una diferencia en cuando a manejo de tipos de datos que no recuerdo el porqué es más eficiente user el let. y const es cuando queremos restringir que una variable no cambie el de tipo

Control de Flujo:

¿Qué son las estructuras de control de flujo y cuáles son algunas de las más comunes en JavaScript?
las estructuras de control de flujo son aquellas que te permiten controlar el flujo en el que se desarrollara tu codigo, lo más comun es la utilizacion de condicionales if y switch

Funciones de Flecha:

Describe qué es una función de flecha en JavaScript y proporciona un ejemplo de cómo se usa.
una funcion flecha es una funcion que se le asigna a una variable o se puede utilizar como un callback(el resultado de una peticion que se devuelve como funcion) y tiene la diferencia


JSON:

¿Qué es JSON y cómo se utiliza en JavaScript?

es un documento que nos permite comunicar informacion entre programas


Promesas:

Explica qué es una promesa en JavaScript y proporciona un ejemplo de su uso.
Depuración:

una promesa es una ejecucion que se hace de manera asincronica que nos va a retornar un resultado de exito y fracaso.

¿Cuáles son algunas de las herramientas o métodos que se pueden usar para depurar código JavaScript?

Preguntas de Selección Múltiple (20)
¿Cuál de las siguientes es la forma correcta de declarar una variable en JavaScript?
A) var myVariable;
B) variable myVariable;
xC) let myVariable;
D) A y C son correctas.
¿Qué método se utiliza para agregar un elemento al final de un array en JavaScript?
xA) push()
B) pop()
C) shift()
D) unshift()
¿Cuál de los siguientes operadores se utiliza para comparar tanto el valor como el tipo de dos variables en JavaScript?
A) ==
xB) ===
C) !=
D) !==
¿Cuál es la salida del siguiente código?
console.log(typeof null);
xA) null
B) undefined
C) object
D) number
¿Cuál de los siguientes métodos se usa para recorrer todos los elementos de un array?
A) forEach()
B) map()
C) filter()
xD) Todas las anteriores
¿Qué se entiende por “hoisting” en JavaScript?
xA) Declaraciones de variables y funciones se mueven al principio de su ámbito.
B) Es un término para describir la eliminación de variables.
C) Es un método para agrupar varias funciones.
D) Ninguna de las anteriores.
¿Cuál es la diferencia entre null y undefined en JavaScript?
A) null significa que una variable ha sido declarada pero no definida, undefined significa que no se ha declarado.
xB) null es un valor asignado intencionalmente, undefined significa que una variable no tiene valor.
C) undefined es un valor asignado intencionalmente, null significa que una variable no tiene valor.
D) No hay diferencia.
¿Cuál es el propósito del método Array.prototype.map()?
A) Modificar el array original.
xB) Crear un nuevo array con los resultados de aplicar una función a cada elemento del array original.
C) Filtrar los elementos de un array.
D) Encontrar un elemento en un array.
¿Qué es el Event Loop en JavaScript?
A) Un ciclo que controla las llamadas recursivas.
B) Un proceso que permite a JavaScript realizar operaciones asincrónicas.
xC) Un método para iterar sobre arrays.
D) Ninguna de las anteriores.
¿Cuál es la salida del siguiente código?

console.log(0.1 + 0.2 === 0.3);
A) true
B) false
C) undefined
xD) NaN
¿Qué se entiende por strict mode en JavaScript?

A) Un modo que permite utilizar características experimentales.
xB) Un modo que cambia la forma en que se ejecuta JavaScript, haciéndolo más seguro.
C) Un método para validar datos.
D) Ninguna de las anteriores.
¿Cuál de las siguientes es una forma correcta de crear un objeto en JavaScript?

A) let obj = {};
B) let obj = Object.create();
C) let obj = new Object();
xD) A y C son correctas.
¿Qué es un callback en JavaScript?

xA) Una función que se pasa como argumento a otra función.
B) Un tipo de variable especial.
C) Un método para declarar funciones.
D) Ninguna de las anteriores.
¿Cuál es el propósito de async y await en JavaScript?

A) Ejecutar funciones síncronas.
xB) Manejar operaciones asincrónicas de manera más simple y legible.
C) Declarar variables globales.
D) Ninguna de las anteriores.
¿Cuál de las siguientes es una estructura de datos inmutable en JavaScript?

A) Arrays
B) Strings
xC) Objetos
D) Ninguna de las anteriores.
¿Cómo se puede convertir un objeto JSON en una cadena de texto en JavaScript?

A) JSON.parse()
xB) JSON.stringify()
C) toString()
D) parseInt()
¿Qué es un Promise en JavaScript?

A) Una función que se ejecuta inmediatamente.
xB) Un objeto que representa la eventual finalización (o falla) de una operación asincrónica.
C) Un método para declarar variables.
D) Ninguna de las anteriores.
¿Qué método se utiliza para agregar uno o más elementos al principio de un array y devolver la nueva longitud del array?

A) push()
B) pop()
xC) shift()
D) unshift()
¿Cuál es la diferencia entre localStorage y sessionStorage en JavaScript?

xA) localStorage almacena datos solo durante la sesión del navegador, sessionStorage almacena datos de manera persistente.
B) sessionStorage almacena datos solo durante la sesión del navegador, localStorage almacena datos de manera persistente.
C) No hay diferencia entre ellos.
D) Ambos almacenan datos solo durante la sesión del navegador.
¿Qué método se utiliza para detener la propagación de un evento en el DOM?

A) event.stopPropagation()
xB) event.preventDefault()
C) event.stop()
D) event.cancel()
