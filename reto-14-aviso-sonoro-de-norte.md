##Reto 14 Aviso sonoro de orientación Norte.

Cuando se necesita orientarse con un mapa, lo que primero que hay que hacer, es situar el mapa con orientación norte. Para ellos se debe usar una brújula.

### Objetivo. {#objetivo-0}

Crear un programa que mediante un aviso acústico se advierta de que la micro:BIT está orientada al Norte.

### Descripción del código. {#descripci-n-del-c-digo-0}

Usar el evento para siempre, para iniciar el programa.

Crear una variable donde se almacenará el valor del sensor obtenido por el bloque dirección de la brújula (º).

Se introduce el condicional si entonces si no para comprobar en qué intervalo se encuentra el valor obtenido por el sensor.

Si el valor se encuentra entre 315º y 45º la micro:BIT se encuentra orientada al Norte, por lo que se mostrará una N y se reproducirá una nota. Si no se cumple la hipótesis, se borra la pantalla.

![](images/image2.png)

### Propuesta. {#propuesta-0}

Hacer un código que ubique de forma más precisa el Norte Magnético.