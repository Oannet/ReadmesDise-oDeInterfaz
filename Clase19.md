INFORMACIÓN 19: "Clase 03

HTTP

Protocolo utilizado para la

comunicación entre

navegadores web y servidores

Hypertext Transfer Protocol

Enviar y recibir datos

Tipos de Solicitudes HTTP

GET: Solicita datos del servidor.

https://ejemplo.com/index.html

Tipos de Solicitudes HTTP

POST: Envía datos al servidor

Tipos de Solicitudes HTTP

PUT: Actualiza datos en el. servidor

Tipos de Solicitudes HTTP

DELETE: Elimina datos en el servidor.

Estructura de una Solicitud HTTP

Método: Indica la acción a realizar (GET, POST, etc.).

URL: La dirección del recurso solicitado.

Cabeceras: Información adicional como el tipo de contenido
que se envía o espera recibir.
Cuerpo: Contiene los datos que se envían al servidor

(usualmente con POST o PUT).

Estructura de una Solicitud HTTP

GET /index.html HTTP/1.1
Host: www.ejemplo.com
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64)
Accept:
text/html,application/xhtml+xml,application/xml;q=0.9

Códigos de estado

Mensajes que envía un servidor en respuesta a una

solicitud HTTP

Códigos de estado

Respuestas informativas

1xx

La solicitud ha sido recibida y que el proceso sigue en curso

Códigos de estado

Éxito

2xx

La solicitud fue recibida, entendida y procesada correctamente por el servidor

Códigos de estado

Redirección

3xx

El cliente debe tomar acciones adicionales para completar la solicitud

Códigos de estado

Errores del cliente

4xx

Indican que hubo un error en la solicitud realizada por el cliente

Códigos de estado

Errores del servidor

5xx

https://developer.mozilla.org/es/docs/Web/HTTP/Status
El servidor encontró un problema al intentar procesar la solicitud

API

API significa Application Programming Interface
(Interfaz de Programación de Aplicaciones).
Una API es un conjunto de reglas y definiciones
que permite a una aplicación interactuar con otra.

REST

Representational State Transfer

Es un estilo arquitectónico para sistemas

distribuidos, como servicios web. Fue introducido
por Roy Fielding en su tesis doctoral en el año

2000.

API Pública

Es una API que está disponible para el uso del

público general.

JSONPlaceholder

POSTMAN

Herramienta que facilita la creación,

prueba y documentación de APIs.

AJAX

Permite a las aplicaciones web

comunicarse con el servidor de manera

asíncrona

Asynchronous JavaScript and XML

XMLHttpRequest

Proporciona una forma fácil de
obtener información de una

URL sin tener que recargar la

página completa. POOy

prototipos

POO(programaciónorientadaaobjetos)

Programación orientada a objetos es una paradigma de programación
que se basa en la representación de objetos de la vida real en vez del uso

de funciones y lógica.

El Objeto this:

Imaginemos que de alguna manera queremos programar todo un

zoologico.

En este sentido podemos programar a todos y cada uno de los animales,

pero esto sería muy tardado.

Para esto nos sirve la programación orientada a objetos.

Callbacks:

Un objeto en programación es una idea abstracta de un objeto en el

mundo real.

Por ejemplo podemos pensar en el objeto

“Animal”

Si lo pensamos bien es un objeto muy genérico ya que describe

muchísimos otros objetos, los animales pueden ser de muchas especies,
razas, colores, tamaños, tener distintos números de extremidades, y un

largo etc...

Promesas:
Clases

Las clases son nuestro primer concepto importante.

Podemos entender las clases como un molde que nos sirve para crear

objetos de uno o muchos tipos.

Las clases se componen de dos cosas.

Propiedades
y métodos

¿Que cosas definen a un animal?
¿Que acciones tienen los animales?

Promesas:

Propiedades

Todos los animáles tienen como propiedades un tamaño, una altura, una
cantidad de extremidades, si vuelan, nadan o caminan, una especie, su

modo de reproducción (si es mamifero u oviparo) y un largo etc.

Luego podemos usar esta clase para crear una gran cantidad de

animales, estos son los objetos y se conocen como instancias de la clase.

Promesas:
métodos

Los métodos son las acciones que podrán ejecutar todas las instancias
de cierta clase, por ejemplo, los animales voladores podrán volar, todos

los animáles podrán comer o beber

¿Puedencrearunaclase“autos”?

Instancias

Una instancia no es más que un objeto creado por una clase.

Una instancia es una representación unica de una clase en memoria.

Las intancias son independiente. lo que quiere decir que tienen metodos

propios e independientes de otras instancias aunque ambas

pertenezcan a la misma clase, así sus acciones además pueden estar

sujetas a sus propiedades especificas de cada instancia.

Principiosfundamentales

Abstracción

La abstracción es el el concepto que en mi opinión describe en su
totalidad la POO, consiste en tomar un concepto de la vida real que en
apareiencia es complejo y enfocarse en sus aspectos escenciales, las

cosas que lo definen y las acciones que estos pueden hacer

encapsulamiento

Este principio se basa en agrupar las propiedades y métodos de una
clase, así como protegerlos restringiendo su acceso y definiendo como

se puede acceder al grupo.

Herencia

La herencia es el  ́

principio que nos permite reutilizar código y generar

jeraquías entre clases.

Esto se realiza mediante un mecanismo por el cual una clase (subclase o
clase hija) puede usar metodos y heredas propiedades de otra clase

(super clase o clase padre)

polimorfismo

Este principio se basa en crear código facil de extender.

El polimorfismo nos permite que diferentes clases respondan a mismos

métodos de manera distinta

Prototipos

Comparado con otros lenguajes de programación Java script no es un
lenguaje orientado a objetos, si no un lenguaje orientado en protoripos.

Esto significa que todo objeto proviene de un prototipo, así los conceptos
como herencia se construyen a traves de este concepto. A su vez esto

genera una cadena de prototipos.

Elprimerprototipo

Por definición podemos notar que en JS todo objeto tiene un prototipo,
podemos saber cual es el prototipo padre usando el método .__proto__

Así todos los objetos en JS directa o indirectamente heredan los métodos

y propiedades del prototipo Object.prototype

Diferenciaentreconstructoryprototype

Un construcctor es una función especial en una clase que nos permite

instanciar objetos con sus propiedades y médotos.

Un prototi ́

po es un objeto que nos permite heredar propiedades y
métodos entre clases y modificar el comportamiendo de las instancias

en tiempo de ejecución

Ventajasdeprototype

Una de las ventajas más significativas de los prototipos es que permiten
que múltiples instancias de un objeto compartan los mismos métodos y
propiedades sin duplicarlos en cada instancia. Esto reduce el uso de
memoria porque en lugar de tener múltiples copias del mismo método
en cada objeto, las instancias comparten una única referencia al método

definido en el prototipo.

Herenciaprototipica

otra ventaja es la herencia prototipica, donde podemos crear o usar un

método sobre un objeto fuera de la misma función.

Podemos notar en este código que logramos hacer lo mismo que la
sintaxis

“Extends
”
en programación orientada a objetos, usando

funciones constructoras que se llaman entre sí.

Esto nos permite heredar propiedades y métodos de objetos sin
establecer una jerarquía entre ellos. A su vez esto nos permite tener

flexibilidad en el comportamiento de las distintas instancias

por ejemplo el siguiente código

Supongamos que para una instancia en especifico queremos que el
método heredado y su método propio funcionen exactamente igual sin

modificar los constructores

Este mismo comportamiento lo podemos realizar con POO, sin embargo
la herencia prototipica la podemos realizar en tiempo de ejecución, lo

que nos permite agregar o cambiar métodos y propiedades

dinámicamente

En conclusíón:

Es importante conocer que la herencia en JS se produce gracias a su
naturaleza prototípica y que dependiendo de casos de uso especificos se

puede usar uno u otro"