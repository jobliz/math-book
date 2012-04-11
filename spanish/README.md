Tras el libro de matemáticas que hubiera deseado en el pasado
=====

Tras mucho tiempo en la búsqueda de libros en internet para reparar mis conocimientos de matemáticas y algoritmia, me he encontrado particularmente insatisfecho. He logrado aprender un par de cosas, pero tener que saltar de un libro a otro no combina muy bien con mis ansias de tener una "vista general" de todo. Me sorprende que no exista (o que me haya sido imposible de conseguir) un libro que muestre de forma unificada, desde cero y de forma práctica, una aproximación a las matemáticas acompañada de la programación.

Así que decidí hacerlo yo mismo. Obviamente no tengo el nivel conceptual del maestro que desearía tener, pero es mejor que seguir esperando. Ahora bien, ¿para quién sería dicho libro?. No tengo experiencia alguna escribiendo libros así, de modo que sólo lo puedo imaginar escrito para mí mismo. ¿Que quisiera yo del libro ideal?

* Que me enseñe a programar desde cero, preferiblemente en un lenguaje que luego pueda usar en el mayor número de cosas posibles.

* Que me cuente de forma clara y sin rodeos porqué es importante aprender matemáticas. Tras varios años de educación formal esa pregunta aparentemente simple, "por qué", al parecer al sistema se le ha olvidado respondérmela. Tengo la vaga y obsesiva sensación de que es muy importante, pero poco más.

* Quiero que siempre que sea posible empieze las matemáticas desde cero, para no perderme en los primeros capítulos. Eso es muy incómodo y desmotiva rápidamente. Que construya poco a poco el conocimiento desde fundamentos definidos y sencillos.

* Que acompañe cada concepto matemático con un ejemplo programable, para evitar ese sentimiento horrible de "ésto solo sirve en el papel".

* Que no me trate como un idiota aunque me exija poco a nivel formalmente matemático. Que explique primero la intuición, luego la práctica, y después las pruebas formales, entendiendo que todas son igualmente importantes, pero que las presente en ese orden.

* Una vez establecidos los fundamentos necesarios, que toque una gran variedad de temas útiles, y que cada uno de ellos tenga una aplicación práctica que pueda imaginarme haciendo, y que pueda programar con mis propias manos.

Sí, soy bastante exigente. Y es porque siento que en el siglo XXI, después de tantos avances tecnológicos, hace falta algo así con urgencia. De repente existe, pero en dado caso no lo he podido conseguir. Ha pasado algo de tiempo desde que aprendí a programar, y ya tengo mi carrera universitaria casi a terminar, sin haberlo conseguido.


Contenido del libro
=====

Mentiría atrozmente si dijera que todo lo voy a escribir "de memoria", más bien pienso llenar mis muchas deficiencias en el camino. Como todo ser humano, lo que hago es posible porque me monto en los hombros de gigantes, gigantes particularmente generosos que han publicado en internet libros completos y extensos sobre matemáticas y programación. Afortunadamente mi tarea es solo de síntesis y traducción, ya que todo está ya disponible en inglés. ¡Si conoces el idioma, leer esos libros directamente será más provechoso que mi resumen!

Pero bueno, ahora el esquema de lo que tengo pensado.

El primer capitulo sería una introducción al lenguaje de programación Python. He escogido este lenguaje porque es dinámico, fácil de aprender, con un gran número de facilidades a la hora de trabajar con matemáticas, y una gran cantidad de usos adicionales. La bibliografía del capítulo sería:

* [Aprenda a pensar como un programador en Python](http://manuales.gfc.edu.co/python/thinkCSpy.es.pdf), todo un libro serio con una introducción completa al lenguaje. [La versión original en inglés puede encontrarse aquí](http://www.greenteapress.com/thinkpython/)

* [Learn Python the Hard Way](http://learnpythonthehardway.org/book/), quizás el mejor tutorial práctico para aprender Python, escrito por Zed Shaw. Es un tipo genial, aunque *muy* particular y sarcástico.

Los puntos a tratar en éste primer capítulo serían:

* Qué es un lenguaje de programación.
* Instalacion de Python (en Windows sería python, notepad++ y powershell, la combinación recomendada por Zed)
* Hola Mundo y comentarios
* Valores, Variables y Tipos (string, int, float, booleanos y listas, los más imprescindibles para trabajar con matemáticas)
* Nombres de variables y palabras reservadas
* Operadores matematicos (+, -, *, /, ==, <, >, %)
* Flujo de control (for, while, if, else)
* Funciones / Generadores
* Programación funcional básica: lambda, map, filter, reduce, range, y comprensión de listas
* Pasando parametros al ejecutar el script, introduccion a la libreria estándar, su importancia, y las partes argv y exit() del módulo sys
* El modulo math, para explicar un segundo módulo
* **Aplicaciones prácticas de todo lo visto**
* Palindromos (tanto para cadenas como enteros)
* Secuencia de Fibonacci
* Factorial. Iterativo y usando la función reduce.
* Números primos. Teorema de Wilson usando factoriales.
* Último problema: La criba de Eratostenes, con la versión original y otra más lenta pero usando valores numéricos.
* Como instalar librerías adicionales en python, muy importante para trabajar en cualquier cosa.

El segundo capitulo seria de matematica elemental, los fundamentos necesarios desde cero para cualquier otro emprendimiento (el resto de los capítulos). Cosas como conjuntos, vectores, funciones, e incluso quizás derivadas e integrales simples. La bibliografía sería:

* [Calculus Made Easy](http://www.gutenberg.org/ebooks/33283), la introducción más sencilla que he encontrado a las derivadas y las integrales. Creo que es imposible leerlo sin sentir "así debieron habérmelo enseñado".

* [Unabridged Version of Sean's Applied Math Book](https://www.its.caltech.edu/~sean/book/unabridged.html). 2,321 páginas. Álgebra, cálculo, funciones de variable compleja, ecuaciones diferenciales ordinarias y parciales, cálculo de variaciones, y diferenciales no lineales. Un monstruo, en pocas palabras.
		
A partir de allí aún no tengo las cosas muy definidas, pero entre lo que pienso incluír en capítulos posteriores estarían (los vínculos llevan a los libros que usaría de bibliografía):

* [Estadística](http://www.greenteapress.com/thinkstats/)

* [Complejidad Computacional](http://www.greenteapress.com/thinkstats/)
