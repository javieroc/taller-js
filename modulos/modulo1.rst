Modulo 1
========

En este modulo atacaremos las nociones y conceptos elementales para poder
ser desarrolladores web, algunas cosas se profundizaran en posteriores modulos
pero los conceptos aqui aprendidos son cruciales.

Ruta de aprendizaje de desarrollo web
-------------------------------------

Empecemos recordando que en un pasado cercano, las páginas web se construian
únicamente usando *HTML*, *CSS* y *Javascript*. Esto aún sigue siendo cierto
pero ahora contamos con muchas otras herramientas que nos facilitan estructurar
nuestras aplicaciones web.

[imagen]

Para que nos sirven cada uno de estos lenguajes. Empecemos con *HTML*, que
no es un lenguaje de programación sino más bien un lenguaje de marcado que nos
sirve para declarar la información. Esto quiere decir que html no se encarga
del diseño de la página web, para eso se usa *CSS* hojas de estilos en cascada,
y lo declara con un lenguaje distinto que html. Por último *Javascript* si es
un lenguaje de programación que nos ayuda a programar el comportamiento e interacción
con nuestro sitio web.

Entrando un poco más en detalle:

**Bases de HTML**

HTML, que significa Lenguaje de Marcado de Hipertextos se usa para definir
el sentido y la estructura del contenido de una página web. Es un lenguaje de
etiqueta o tags que se declaran usando *(<, > ,/)*.

Vamos a distinguir algunos elementos:

- Etiquetas: estructura básica de html que tienen dos propiedades básicas, atruibutos y contendio, por ejemplo un párrafo: `<p>Esto es un parrafo</p>`.
- Atributos: son formas de configurar la etiqueta, son pares nombre-valor separados por un signo igual *=*, por ejemplo la url de una imagen `<img img="http://image.png" />`
- Links: es un tipo especial de etiqueta que genera un hipervinculo de una página a otra, esto es la base de como funciona la web, `<a href="pagina2.html">Soy un link a pagina 2</a>`
- Imagenes: etiqueta para declarar imagenes usando una *uri*.

**Bases de CSS**

.. role:: css(code)
   :language: css

Es un lenguaje de hojas de estilo, es decir, te permite aplicar estilos de manera selectiva a
elementos en documentos HTML. Por ejemplo, para seleccionar todos los elementos de párrafo en una
página HTML y volver el texto dentro de ellos de color rojo, has de escribir:

.. code-block:: CSS

   p {
     color: red;
   }

Estructura de una regla CSS:

- Selector: El elemento HTML al que aplicaremos la regla. Esta selecciona el(los) elemento(s) a dar estilo (en este caso, los elementos p ).
- Declaración: Una sola regla como :css:`color: red;` especifica a cuál de las propiedades del elemento quieres dar estilo.
- Propiedades: Maneras en las cuales puedes dar estilo a un elemento HTML. (En este caso, color es una propiedad del elemento p.)
- Valor de la propiedad: A la derecha de la propiedad, después de los dos puntos (:), tenemos el valor de la propiedad, para
  elegir una de las muchas posibles apariencias para una propiedad determinada (hay muchos valores para color además de red).

**Bases de Javascript**

A diferencia de *HTML* y *CSS*, *Javascript* si es un lenguaje de programación, interpretado y orientado a objetos. Que se
utiliza en millones de páginas web y aplicaciones de servidor (NodeJS). Javascript no esta directamente relacionado Java, lo
único en común es que son lenguajes de programación.

La principal carácteristica de Javascript es que permite escribir código asincrono. Esto quiere decir que el código
no necesariamente se ejecuta en el orden en que lo escribimos. Conceptos relacionados:

- Callbacks/Eventos.
- Promesas.
- Async/await.
- AJAX.

De momento solo utilizaremos Javascript para modificar el DOM y poco más.


**DOM: Document Object Model**



**Frontend/Backend**

Frontend es todo lo que corre en el navegador, lo que se ve. Y backend es todo
lo que corre en internet, en el servidor.