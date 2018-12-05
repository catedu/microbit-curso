##Reto 8 ¿Qué botón has pulsado?

A veces puede interesar usar un pulsador para iniciar, pausar o detener un código o subrutina. Algunos robots incorporan botoneras para esta finalidad.

### Objetivo. {#objetivo}

Crear un programa que muestre en pantalla la letra del pulsador que se ha accionado.

Pruébalo aquí:

<div style="position:relative;height:0;padding-bottom:81.97%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---run?id=_ibiDd0EKA15r" allowfullscreen="allowfullscreen" sandbox="allow-popups allow-forms allow-scripts allow-same-origin" frameborder="0"></iframe></div>

### Descripción del código. {#descripci-n-del-c-digo}

Se usará el bloque al iniciar para que al principio se muestre el texto “Pulsa un botón”. La micro:BIT no muestra caracteres acentuados, por lo que dejará un hueco si se pone la tilde en la palabra botón.

Posteriormente se usará el evento al presionar el botón A  y se introducirá el bloque mostrar cadena donde se sustituirá el texto por defecto por la letra “A”.

Esto mismo se repetirá cuando se pulsa el botón B y la pulsación combinada de A+B.

El código quedaría de la siguiente forma:

![](../images/image13.png)

### Propuesta. {#propuesta}

Crear una caja de música. Al pulsar el botón A haga hará sonar una melodía. El bloque necesario para hacer sonar una melodía se encuentra en la categoría Música.



