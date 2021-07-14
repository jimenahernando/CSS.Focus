# CSS.Focus

Es indispensable diferenciar el evento focus del evento hover a la hora de poner estilos y conocer las reacciones en los distintos navegadores.
Pensar que en el evento hover el usuario guia la mirada junto con el cursor del raton. En cambio, el evento focus (se activa con el uso del tabulador)
depende del hincapie que haga el navegador.
En firefox el focus en los botones se marca sobre el texto y no rodeando al boton.

Aprendizaje de los siguientes atributos:
* outline: estable el contorno de un elemento. Se diferencia del border porque no ocupa espacio, se dibuja por encima del elemento, alerededor y y puede no ser rectangular y siempre es cerrado (contiene todos los lados)
* outline-offset: espacio entre el contorno outline y el borde del elemento.
* -moz-focus-inner: extension de Mozilla que representa un anillo de enfoque interno de un elemento button/input.

Tutorial: https://www.youtube.com/watch?v=Mvu5OMGcdVA&list=RDCMUCJZv4d5rbIKd4QHMPkcABCw&index=3&ab_channel=KevinPowell
