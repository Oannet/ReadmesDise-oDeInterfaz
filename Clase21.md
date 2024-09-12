INFORMACIÓN 21: "Fetch API

Interfaz moderna para realizar
solicitudes HTTP, diseñada para ser

más simple y poderosa que

XMLHttpRequest.

Ventajas de Fetch API sobre

XMLHttpRequest

Promesas: simplifica el manejo de operaciones
asíncronas.
Es más fácil de leer y escribir.
Mejor manejo de flujos de trabajo complejos y
encadenamiento de solicitudes.

Manejo de Errores

No considera un error de red (como una falla en la

conexión) como un error en la promesa.

PROGRAMACIÓN ASINCRONA

Es un paradigma de programación que permite que varias
tareas se ejecuten al mismo tiempo de manera no bloqueante,
es decir, que si dos tareas independientes se deben ejecutar,
la segunda se puede ejecutar sin necesidad de terminar la
primera.

CALLBACKS

Los callbacks son funciones que se pasan como argumento a
otras funciones y se ejecutan después de que la operación
asíncrona se haya completado. Son la forma más antigua de
manejar la asincronía en JS

PROMESAS

Una promesa es un objeto que representa la eventual
finalización exitosa o fallida de un a operación asíncrona. Las
promesas en compareción con los callbacks son una forma
más limpia de manejar la asincronía

ESTADOS DE UNA PROMESA

Los estados de una promesa son los posibles escenarios en los
que se puede encontrar una operacíón asincrona en tiempo
de ejecución:

Pending (pendiente): significa que su ejecución no ha
terminado, es el estado inmediato luedo del inicio del
ejecución de la operación
Fulfiled (cumplida): Significa que la operación asincrona se
ha completado de manera exitosa
Rejected (rechazada): Significa que la operación se
completo fallidamente.

CONSUMO DE UNA PROMESA

.then(): Se usa en el caso de que la promesa se haya
cumplido exitosamente
.catch(): se usa en el caso de que la promesa falle.
.finally(): Se usa en cualquier caso

CREAR UNA PROMESA

Para crear una promesa usamos su constructor “Promise” y la
sintaxis de poo

¡HAGAMOS UN EJEMPLO!

ASYNC Y AWAIT

Async y await son palabras reservadas que nos ayudan a
simplificar el manejo de la asincronía.
hacen que el código sea mucho más limpio, legible y
mantenible.

Async se usa para declarar una función como asíncrona que
devuelve automáticamante una promesa.

await se usa dentro de una función asincrona “async” para
pausar la operación hasta que la promesa de dicha función se
complete de manera exitosa o fallida"