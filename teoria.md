## Explica los siguentes conceptos con tus propias palabras. (no más de tres líneas por respuesta).

* Estructura de Datos:
Las estructuras de datos son diferentes maneras de guardar información, para que luego pueda ser utilizada de manera eficiente.

* Lista Enlazada:
Es un tipo de estructura de datos en la cual cada nodo tiene un contenido y una referencia al proximo nodo. Se usa para datos que se manejan siempre de forma lineal.

* Árbol:
Un arbol es una estructura no lineal en la que cada nodo puede apuntar a uno o varios nodos. También se suele dar una definición recursiva, esto quiere decir que cada nodo es un arbol en si mismo.

* Closures:
Es un concepto de como JavaScript esta diseñado que en muchos casos puede traer errores por no saber que existe. Cuando ejectuamos una funcion, gracias a closures se puede utilizar las variables que tenia su creador aunque ese execution contxt no exista mas. Closures da provacidad y nos permite crear variables que no pueden ser modificadas.

* Contexto de Ejecución:
Es la porción de lineas de codigo que son tenidas en cuenta para mi contexto, cuando defino una funcion, tolo lo que esta dentro de esa funcion, es mi execution context. Tiene cuatro componentes: Global Object, This, Outer Enviroment y el codigo.

* Variable THIS:
En el contexto gobal, this es un objeto de tipo window. Dentro de una funcion, this es la funcion en si misma, hace referencia a si misma.

* Hoisting:
Cada vez que ese esta por ejecuta un execution context, JS, en el hoisting mira el codigo entero y resrerva un espacio de memoria para todas las funciones y las declaraciones de variables. No importa el orden, siempre van arriba.

* Pasar por valor y por referencia:
Si paso un argumento como referencia doy acceso a ese argumento y si es modificado, se modifica el original tambien (objetom funcion)
Si se pasa como valor no se puede modificar, solo es una copia ( string, numero, booleano, undefined)

* Algoritmo:
Es un conjunto de instrucciones para resolver algo. Los algoritmos resuelven problemas, deben ser comprensibles y deben ser eficientes, esto significa que deben usar la menor catidad de pasos posible.

* Big O notation:
Se refiere a la complejidad de los algortimos para predecir el comportamiento o compararlos y ver cual es mas eficiente en distintos casos.

* Inmediatly Invoked Function Expression (IIFF):
Son funciones que se ejecutan tan pronto como se definen.