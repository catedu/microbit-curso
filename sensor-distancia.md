#Sensor distancia
![](https://i.imgur.com/t4vFZ0y.jpg)

Al poner la extensión micromotor se añade la instrucción de sonar que está en otro apartado:

![](/assets/2018-12-05 11_28_59-Microsoft MakeCode for micro_bit.jpg)

Este sensor, en nuestro kit lo conectaremos en **PIN 10** aunque puede estar conectado en cualquier otro. Además recomendamos crear una variable (por ejemplo "distancia") y poner las unidades de medida en cm que son más intuitivas. Esta instrucción se pone al principio del bucle y sólo hay que utilizar la variable **distancia**:

![](/assets/2018-12-05 11_31_09-Reto evitar obstáculos · Micro_bit.jpg)

El sensor de distancia funciona igual que los sónares: Uno "ojo" es realmente un altavóz que emite un sonido con frecuencia alta (*ultrasonido, por eso no lo oímos*) y el otro "ojo" es un micrófono que recibe ese pulso. El circuito electrónico calcula la distancia con la diferencia de tiempo en emisión y la recepción del eco, igual que los rádares, sónares...

<iframe src="https://giphy.com/embed/4xGCaTMCO59le" width="480" height="357" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/vintage-tech-4xGCaTMCO59le">via GIPHY</a></p>

O incluso los murciélagos, delfines...

<iframe src="https://giphy.com/embed/3o7TKu5aIDY4tU3SXm" width="480" height="272" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/3o7TKu5aIDY4tU3SXm">via GIPHY</a></p>