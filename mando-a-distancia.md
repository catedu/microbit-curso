#Rento 5 Mando a distancia
Esta vez **vamos a utilizar dos micro:BITs** 

{% youtube %}https://youtu.be/oxumk9GYoVU{% endyoutube %}

##Descripción del programa
###Microbit que hace de mando
Este microBIT hay que alimentarlo con pilas o utilizando una batería típica de móvil. 

El mando se inicia en un grupo (en este caso el 222) y simplemente realiza lo siguiente:
* Si se pulsa A manda un 1 y lo visualizo
* Si se pulsa B manda un 2 y lo visualizo
* Si se pulsa A+B manda un 3 y lo visualizo

![](/assets/2018-12-05 14_10_27-Microsoft MakeCode for micro_bit.jpg)

El programa te lo puedes descargar [aquí](https://makecode.microbit.org/_cWz6s9aeTPXr):

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_cWz6s9aeTPXr" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

###Microbit que está en SmartCar

Al iniciar el programa asigna este microbit al mismo grupo de radio que el mando y además asigna una nueva variable con valor 0

![](/assets/2018-12-05 14_03_41-Microsoft MakeCode for micro_bit.jpg)

Al recibir un número lo asigna a esa variable y además lo muestra:

![](/assets/2018-12-05 14_04_43-Microsoft MakeCode for micro_bit.jpg)

Y establecemos un bucle por siempre que :

* Si no ha recibido nada, es por lo tanto dato=0 luego que siga hacia delante
* Si recibe 1 que gire hacia la derecha y hacia atrás
* Si recibe 2 igualmente pero al otro lado
* Si recibe 3 que pare
* En los tres casos anteriores damos un tiempo para que ejecute la instrucción con una pausa y luego reseteamos dato para que siga el robot su camino

![](/assets/2018-12-05 14_07_56-Microsoft MakeCode for micro_bit.jpg)

El proyecto te lo puedes descargar [aquí](https://makecode.microbit.org/_ftuFv8AReFYq) :

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_ftuFv8AReFYq" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>