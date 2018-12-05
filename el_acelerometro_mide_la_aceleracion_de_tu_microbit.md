##Reto 11 Dado electrónico.

Un dado es un objeto cúbico usado en juegos de azar. En las caras del cubo aparecen puntos que representan distintos números.

Se propone crear un dado electrónico que, usando el panel LED, muestre el resultado de obtener un número al azar entre 1 y 6.

### Objetivo. {#objetivo}

Tras agitar la micro:BIT, se deberá calcular un número aleatorio cuyo valor esté entre 1 y 6\. Posteriormente, se mostrará en el panel LED el valor obtenido.

Pruébalo ¡¡lo puedes sacudir!! este simulador es genial !!
<div style="position:relative;height:0;padding-bottom:81.97%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---run?id=_A1Tcyy1zLRgP" allowfullscreen="allowfullscreen" sandbox="allow-popups allow-forms allow-scripts allow-same-origin" frameborder="0"></iframe></div>

### Descripción del código. {#descripci-n-del-c-digo}

Como evento de inicio del programa se usará el bloque si agitado, se mostrará un número escogido al azar entre 0 y 5, al que se le sumará 1\. Se suma 1 dado que el bloque escoge al azar, tiene como valor fijo de inicio el 0.

Tras una pausa de 1 segundo se borra la pantalla, quedando a la espera de que se vuelva agitar la micro:BIT.

![](images/image20.png)

### Propuesta. {#propuesta}

Diseñar un programa que permita jugar a la ruleta además se deberá indicar si es rojo o negro o  si gana la banca.

