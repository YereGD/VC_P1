# VC_P1


En esta practica se han realizado 6 tareas propuestas:

1º Tarea

En esta tarea se ha creado un tablero de ajedrez para ello se ha establecido el tamaño del tablero a 800x800 pixeles. En este caso solo es necesario pintar cuadros blancos, porqué el tablero inicialmente está en negro, estos cuadros blancos se pintan de mánera que avanzan 100 píxeles por cuadro y se pinta en las columnas pares y en las no pares no se pinta,pero dependiendo de la fila si es impar se realiza un desplazamiento pintando así en las columnas impares realizando el proceso inverso. Así finalmente pintas el tablero de ajedrez.

2º Tarea

Esta tarea consiste en realizar un dibujo estilo mondrian. Para facilitar la realización de esta se creado un función que nos permite pintar rectángulos de manera más intuitiva. Para dibujar el dibujo estilo mondrian se han dibujado varias rectangulos por filas con diferente alturas y anchuras manteniendo la altura de los rectángulos en cada fila.

3º Tarea

Esta tarea se ha realizado una tarea anterior, se ha elegido dibujar el tablero de ajedrez, pero en este caso se ha empleado funciones del OpenCV. El funcionamiento de código es practicamente el mismo que la primera tarea solo que se emplea la función de dibujar rectangulos de OpenCV.

4º Tarea

En esta tarea se tiene que modificar los valores de un plano de la imagen, en nuestro caso se ha elegido el plano que corresponde al color azul de la imagen, en este plano se ha invertido los valores de los pixeles y finalmente dependiendo de un cierto umbral se ha establecido el valor del pixel al máximo valor 255 o el mínimo 0 haciendo esto último se consigue un alto contraste.

5º Tarea

Está tarea consiste en dibujar un circulo en el pixel más claro o más oscuro. Para esto se han recorrido todos los pixeles sumando sus 3 valores buscando el pixel con mayor y menor suma así obteniendo el pixel más claro y oscura mediante comparaciones. Este proceso es bastante lento, así que una alternativa más eficiente que hemos realizado es crear agrupaciones de pixeles 8x8 sumar los valores de estos 64 píxeles y compararlos con las demás agrupaciones de las misma manera que en la primera opción. 

6º Tarea

Esta tarea consiste en modificar tres imágenes iguales inicialmente, se modifican los 3 canales de color, en la primera el rojo, en la segundo el verde y por el último el azul. En el caso de la primera imagen, en primera instancia los 2 canales se van a sumar a su máximo valor 255, asimismo el canal que modificamos en este caso el rojo, primero se va a invertir y a partir de un umbral de luminisidad se va poner el valor al maxímo 255 o al mínimo 0, viendose así la zonas iluminadas como la suma de los dos colores y las zonas no iluminadas se van a ver totalmente blancas. 

Autores:

Yeremay García Déniz

Adonai Hernandez Bolaños
