INFORMACIÓN 17: "C L A SE 01
¿ Q ué es Vi sua l Studio C ode?
Es un edi tor de código fuente
gr a tui to y mul t ipl a t a forma
des a r rol l ado por Mi c rosof t .
Introducción al Editor Visual Studio Code
Microsoft. (2023). Visual Studio Code. Recuperado de https://code.visualstudio.com/
01
D es c a rga Vi sua l Studio C ode desde el s i t io ofi c i a l :
ht tps :// code.vi sual s tudio. com/
Sigue l a s ins t ruc c iones del ins t a l ador pa r a tu
s i s tema oper a t i vo (Windo w s , ma c O S, L inux ).
Instalación:
02
Configuración Básica:
Al abrir VS Code por primera vez, puedes
personalizar la apariencia, como el tema oscuro o
claro. Ctrl+K+T
01
Configura la fuente y el tamaño de letra en la
configuración (Ctrl + ,)
02
03
04
Interfaz de Usuario
Explorer: para navegar entre los archivos de tu proyecto.
Search: para buscar en el proyecto.
Source Control: integración con sistemas de control de
versiones como Git.
Extensions: para instalar extensiones.
05
Interfaz de Usuario
Editor principal: Aquí es donde
escribirás tu código.
Terminal integrado: Puedes ejecutar comandos
directamente desde VS Code (Ctrl + ñ).
HTML Snippets: Provee atajos para etiquetas y
atributos HTML.
Live Server: Permite ver en tiempo real los
cambios en tu archivo HTML.
Prettier: Formatea automáticamente tu
código.
Emmet: Atajos para escribir HTML y CSS más
rápidamente.
06
ExtensionesRecomendadas para HTML y CSS
Historia de HTML
HTML fue creado en 1991 por el físico Tim Berners-Lee,
como investigador del CERN, como propuesta de un
nuevo lenguaje de “Hipertexto” para compartir
documentos. desde entonces ha evolucionado desde
un simple lenguaje de marcado para documentos
hasta HTML5, que incluye capacidades multimedia y
semánticas.
07
Fundamentos de HTML
HyperText Markup Language/lenguaje de marcado de hipertexto
Estructura básica de un documento HTML
<etiqueta atributo=”value”>holiiis</etiqueta>
Toda página web se compone por etiquetas, estas son indicadores para el
navegador de como interpretar y como mostrar cierto elelemento
Se compone por cuatro partes: apaertura, atributos, contenido y cierre
08
Estructura básica de un documento HTML
Estructura básica de un documento HTML
<!DOCTYPE html>:
Declara el tipo de documento.
<html>:
Elemento raíz.
<head>:
Contiene metadatos, título,
enlaces a CSS o JS.
<body>:
Contiene el contenido visible.
09
Estructura básica de un documento HTML
Elementos y etiquetas HTML más comunes
Comentarios: <!-- contenido comentado -->
Encabezados: <h1> a <h6>
Párrafos: <p>
Enlaces: <a href="URL">Texto del enlace</a>
Imágenes: <img src="URL" alt="Descripción">
Listas:
<ul></ul> <!-- unorder list-->
<ol></ol> <!-- order list-->
<li></li> <!-- list item-->
10
Estructura básica de un documento HTML
Elementos y etiquetas HTML más comunes
Botones: <button type="button"
onclick="function()">Name</button>
Form:
<form action="/submit" method="post">
<!-- Esto es un formulario que usa metodos de petición http-->
<label for="name">Nombre:</label>
<input type="text" id="name" name="name">
<input type="submit" value="Enviar">
</form>
11
Estructura básica de un documento HTML
Elementos y etiquetas HTML más comunes
Elementos Multimedia y Formatos Imágenes, audio y video
12
Imágenes: <img src="ruta_imagen.jpg" alt="Descripción de la imagen">
Audio: <audio controls><source src="audio.mp3" type="audio/mpeg">
</audio>
Video: <video controls><source src="video.mp4" type="video/mp4"></video>
Estructura básica de un documento HTML
Atributos importantes para etiquetas HTML
13
Estructura básica de un documento HTML
Enlaces y navegación
14
Estructura básica de un documento HTML
Formularios y validación básica
15
Estructura básica de un documento HTML
Semántica en HTML5
16
Etiquetas semánticas:
<header>
,
<footer>
,
<article>
,
<section>. Beneficios:
Mejoran la accesibilidad y hacen
que el código se vea más
organizado
Estructura básica de un documento HTML
Introducción a CSS
17
Cascading Style Sheets u Hojas de estilo en
cascada
Permite aplicar estilos como colores,
formas y márgenes a documentos HTML
de manera masiva y automática.
Se les llama "en cascada" porque los estilos
se aplican de arriba hacia abajo en el
código.
Lanzada en 1996
Estructura básica de un documento HTML
¿Cómo se incluye en HTML?
18
rel="stylesheet" se utiliza en
la etiqueta <link> para
especificar la relación entre el
documento actual y el
archivo vinculado. Cuando el
valor de rel es "stylesheet"
, se
indica que el archivo
vinculado es una hoja de
estilos en cascada (CSS) que
debe aplicarse al documento.
19 Estructura básica de un documento HTML
Etiqueta: Un componente básico en HTML que define un
elemento (<p>
,
<div>).
Clase: Un selector en CSS que se aplica a múltiples
elementos para compartir un mismo estilo (.importante).
ID: Un selector en CSS que se aplica a un solo elemento
único en la página (#titulo-principal).
Repaso:
Estructura básica de un documento HTML
Selectores básicos
20
Selector de etiqueta: p { color: blue; }
Selector de clase: .clase { color: red; }
Selector de ID: #id { color: green; }
Pseudo-clases ( : ): Estilizan elementos según su estado;
:hover, :focus
Pseudo-elementos ( : : ): Estilizan una parte específica de un
elemento; :: after, ::before
Modelo de Caja (Box Model)
Describe cómo los elementos HTML se
representan como cajas rectangulares.
Cada caja tiene cuatro áreas:
Contenido: El área donde se muestra el
contenido (texto, imágenes, etc.).
Padding (Relleno): Espacio entre el
contenido y el borde de la caja.
Border (Borde): El borde alrededor del
padding.
Margin (Margen): Espacio exterior entre el
borde y otros elementos.
21
Es un módulo que permite distribuir y alinear
elementos en un contenedor de forma eficiente.
Es ideal para crear layouts flexibles y responsivos,
ya que permite centrar elementos horizontal y
verticalmente, distribuir espacio, y reorganizar
elementos dentro de un contenedor.
display: flex;: Activa Flexbox en un contenedor.
justify-content: Alinea los elementos
horizontalmente.
align-items: Alinea los elementos
verticalmente.
Flexbox
22
Es un framework front-end de código
abierto que facilita el desarrollo de sitios
web y aplicaciones web responsivos y
móviles.
Bootstrap
23
Bootstrap utiliza un sistema de 12 columnas que permite
organizar el contenido en filas y columnas, facilitando la
creación de diseños responsivos.
Sistema de Rejilla (Grid System):
24
Estructura básica de un documento HTML
Importar fuentes
25
https://fonts.google.com/
https://developer.mozilla.org/es/do Clase02

Brendan Eich, ingeniero de
Netscape, creó JavaScript en

1995 en solo 10 días

JavaScript

QuéesJavaScript:

JavaScript es un lenguaje de programación interpretado
(aquel que no necesita ser compilado previamente a su

ejecución) que se ejecuta principalmente en

navegadores web.
Es orientado a objetos.

Variablesyconstantes

var:
Declaración de variables con alcance de
función (obsoleto en muchos casos).

let:
Declaración de variables con alcance de
bloque.

const:
Declaración de constantes, cuyo valor no
puede cambiar.

TiposdeDatosPrimitivos

Números

Cadenas (strings)

Booleanos

EstructurasComplejas:

Arrays:

Objetos:

OperadoresAritméticos

OperadoresdeComparación

OperadoresLógicos

Y lógico (&&):

O lógico (||):

No lógico (!):

Funciones

Declaración de Funciones:

Funciones Anónimas:

funciones que no se han
declarado con un nombre

¿QuéeselDOM?

(Document Object Model) es una API

definida para representar e

interactuar con cualquier documento

HTML o XML

Es una representación en forma de
árbol del contenido de una página
web. Permite a JavaScript interactuar

y modificar el contenido de una

página web.

<html>

<head>

<title> <div>

<body>

<p> <p>

ManejodeEventos

Se refiere al proceso de capturar y responder a
"
eventos
"
que

ocurren dentro de una aplicación o sistema.

SeleccióndeElementos

Con el DOM, puedes seleccionar cualquier elemento HTML utilizando

métodos como getElementById o querySelector.

Permite modificar atributos, estilos, o contenido de esos elementos.

Selección por ID

Selección por Clase

Selección por Etiqueta

ModificacióndeContenidoyEstilos

Selección de un Solo Elemento con Selectores CSS

Selección de Múltiples Elementos con Selectores CSS

Selección por Atributo name

CrearyEliminarElementos

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

se puede acceder al grupo.""