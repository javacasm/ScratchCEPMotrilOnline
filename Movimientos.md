## Movimientos de personajes

Vamos a aprender a mover nuestros personajes por el escenario.
Veremos que podemos hacerlo de diferentes forma,  con movimientos absolutos (usando las coordenadas x,y) y también con movimientos relativos (dando **N** pasos desde la posición actual en la dirección en la que apunta el personaje).

También veremos que podemos hacer que nuestro personaje gire, apuntando en distintas direcciones.

### Coordenadas

Empezamos por ver el sistema de coordenadas que utiliza Scratch:

![Coordenadas Scratch](./images/CoordenadasScratch.png)

Las coordenadas del escenario de Scratch son las siguientes:

* La coordenada horizontal **X** entre -240 y 240
* La coordenada vertial **Y** entre -180 y 180
* Estando el punto **(0,0)** es el centro de la pantalla.

### Movimientos

Vamos a ver las distintas formas de mover nuestro personaje.

#### Movimientos absolutos

Decimos que el movimiento es absoluto cuando se indican las coordenadas **x** e **y** que tendrá el personaje. Si damos distintas

![Movimientos absolutos](./images/MovmientosAbsolutos.png)

* Ir a (x,y) es instántaneo, como un "teletransporte".
* Deslizar va moviendo poco a poco desde la posición inicial hasta la coordenada indicada en el tiempo que le hemos dicho.

Si damos varias órdenes de movimiento, estas se realizarán de manera consecutiva. Si son varias "Ir a" al hacerse tan rápido, quizás solo veamos la última posición.

#### Direcciones/Orientación (en grados)

Además de movernos podemos hacer que el personaje apunte en una dirección dada entre 0 y 360 grados. Estas son 4 posiciones para giros de 90º.

![Direcciones Scratch](./images/DireccionesScratch.png)

Podemos apuntar en cualquier dirección (Puede ser cualquier valor) usando el bloque "apuntar en dirección"

![Apuntar en una dirección](./images/ApuntarDireccion.png)

Al pulsar sobre el valor aparecerá un selector de ángulo que nos facilita la tarea.

#### Movimiento relativos

Los movimientos relativos se hacen a partir de la posición y dirección actual, y se indican cuantos grados se quiere girar a partir de la orientación actual o cuantos pasos avanza en la dirección en la que está actualmente apuntando.

Para ello tenemos los siguientes bloques:

![Movimientos Relativos](./images/MovimientosRelativos.png)

#### Tipos de rotaciones

Al rotar el personaje, el disfraz de este gira también. Por eso existen diferentes tipos de rotaciones de disfraz, unas más indicadas para cada tipo de disfraz, como veremos. 

Podemos seleccionar el tipo pulsando sobre alguna de las 3 opciones que aparecen bajo el selector de ángulo.

El tipo de rotación **Giro** rota el disfraz actual de nuestro personaje los grados indicados:

![Rotacion tipo Giro](./images/RotacionGiro.png)

El tipo de rotación **horizontal** solo tiene en cuenta el signo de los grados indicados, haciendo que el disfraz "mire" hacia la izquierda cuando el signo es negativo y hacia la derecha cuando es positivo:

![Rotación tipo Horizontal](./images/RotacionHorizontal.png)

Si no queremos que el disfraz se modifique con las rotaciones usaremos **Sin rotación**.

![Sin Rotación](./images/SinGiro.png)

También podemos fijar este tipo de rotación con este bloque:

![FijarTipoRotacion](./images/FijarTipoRotacion.png)

¡¡Cuidado!! ¡Los giros no afectan igual a todos los personajes!

![Giro a 44º](./images/Giro44.png)

![Giro a -75º](./images/Giro_75.png)

Hay disfraces diseñados para poder moverse en cualquier dirección otros pensados para verlos lateralmente. Busca los distintos disfraces de Gato en la biblioteca de personajes y verás las distitnas opciones.

[![Vídeo: Movimiento de personajes](https://img.youtube.com/vi/4O_lxBaApnY/0.jpg)](https://youtu.be/4O_lxBaApnY)


[Vídeo: Movimiento de personajes](https://youtu.be/4O_lxBaApnY)

### Ejemplo: movámonos alrededor del escenario

Vamos a poner en práctica estos movimientos moviendo nuestro personaje alrededor de toda la pantalla formando un rectángulo.

Usa si quieres el [fondo de coordenadas](./images/CoordenadasScratch_sinGato.png)



#### Movimientos absolutos

En este primer ejemplo utilizaremos bloques con movimientos absolutos.

Vamos a elegir un personaje que podamos girar en cualquier dirección, porque su disfraz parezca que se ve desde arriba, como es "Escarabajo"

Para encontrar los valores adecuados de las coordenadas  movemos nuestro personaje con el ratón por el escenarios, tomando nota de las coordenadas **X** e **Y** que aparecen debajo del Escenario.

Para movernos de una posición a otra usaremos "Deslizar ..." y así podremos ver el movmiento. 

Tras cada movimiento giramos el personaje para que parezca que se mueve en esa dirección.

El programa queda muy sencillo:

![Programar Movimientos Absolutos](./images/MovimientosAbsolutos.png)

[Programa: Movimientos Absolutos](https://scratch.mit.edu/projects/394209879/)


[![Vídeo: Movimientos absolutos del personajes por el escenario](https://img.youtube.com/vi/dEVWnlP5EGk/0.jpg)](https://youtu.be/dEVWnlP5EGk)


[Vídeo: Movimientos absolutos del personajes por el escenario](https://youtu.be/dEVWnlP5EGk)


#### Movimientos relativos

Vamos a hacer ahora el mismo recorrido pero usando movimientos relativos. Iremos girando 90º y moviéndonos un cierto número de pasos.

Hemos intercalado unas esperas entre los movimientos para poder apreciarlo más fácilmente.

El programa queda sencillo, pero repetitivo...

![Programa Movimientos Relativos](./images/ProgramaMoimientosRelativos.png)

[Programa: Movimientos Relativos](https://scratch.mit.edu/projects/394215273/)

[![Vídeo: Movimientos relativos](https://img.youtube.com/vi/qC9IGAoevLw/0.jpg)](https://youtu.be/qC9IGAoevLw)

[Vídeo: Movimientos relativos](https://youtu.be/qC9IGAoevLw)

#### Repetición con bucles

Si en lugar de movernos con forma de rectángulo nos movemos haciendo un cuadrado, veremos que nuestro programa es muy repetitivo.

Es algo muy frecuente tener que repetir un grupo de bloques varias veces. Por eso existen en la paleta de control los bloques "Repetir". 

Vemos que muchos de estos bloques tiene forma de "C". El hueco central es donde pondremos todos aquellos bloques que queremos repetir.

Uno de los más utilizados es el bloque "Repetir N veces", que será el adecuado para nuestro caso usando 4 repeticiones de los 3 bloques:

![Bloque Repetir N veces](./images/BucleRepetir.png)

El programa queda así de sencillo:

![Programa Dibujando Cuadrados](./images/DibujandoCuadrados.png)

[Programa: Dibujando Cuadrados](https://scratch.mit.edu/projects/394066829/)

[![Vídeo: Bucle repetición](https://img.youtube.com/vi/_QsXbvNzuzE/0.jpg)](https://youtu.be/_QsXbvNzuzE)


[Vídeo: Bucle repetición](https://youtu.be/_QsXbvNzuzE)

### Pintando cuadrados

Ya que sabemos mover nuestros personajes por la pantalla, vamos a utilizar para dibujar sobre ella. Haremos que al moverse dejen un rastro formando dibujos y figuras geométricas.

Para ello usaremos la extensión **Lápiz**. Una extensión es un complemento de Scratch que añade bloques con nuevas funcionalidades. Hay extensiones para dibujar, para hacer música, para controlar dispositivos como Lego o micro:bit.

Podemos añadir extensiones pulsando el botón azul abajo a la derecha

![Botón Añadir Extensiones](./images/AñadirExtensiones.png)

Pulsamos y añadimos la extensión "**Lápiz**"

![Extensión Lapiz](./images/ExtensionLapiz.png)

Al seleccionarla nos aparecerá una nueva paleta de bloques con los siguientes:

![Bloques de la Extensión Lápiz](./images/BloquesExtensionLapiz.png)


![PintandoCuadrados](./images/PintandoCuadrados.png)

[Pintamos un cuadrado](https://scratch.mit.edu/projects/394212879/)

Vemos que hay bloques para **cambiar el grosor** o el **color** del lápiz, para **bajar** (deja rastro) o **subir el lápiz** cuando queremos que nuestro personaje no deje rastro al moverse.

Vamos a usarlo para dibujar un cuadrado en pantalla. Aprenderemos:
* A incluir más bloques con una extensión.
* A usar la extensión **Lápiz** para dibujar.
* A que hay que bajar el lápiz para dejar rastro.
* A borrar la pantalla (mejor al principio del programa)
* Los colores de la paleta de colores están ordenados de 0 a 100, siendo rojo en los dos extremos y verde/azul en el centro:

![Paleta de Colores](./images/PaletaColores.png)
* A seleccionar color y groso del lápiz.
* A modificar el color del lápiz.
    * Podemos **fijar** un color.
    * **Cambiar** el color, incrementando su valor.

[![Vídeo: Pintando Cuadrados](https://img.youtube.com/vi/VppOn52tlpQ/0.jpg)](https://youtu.be/VppOn52tlpQ)


[Vídeo: Pintando Cuadrados](https://youtu.be/VppOn52tlpQ)


### Pintando polígonos

Vamos a generalizar el programa que dibuja cuadrados para que nos permita dibujar polígonos de cualquier número de lados.

Para ello haremos una copia del programa que dibuja cuadrados para trabajar sobre él.

Lo vamos a revisar para pensar qué habría que cambiar si queremos dibujar un hexágono...

Vemos que cláramente tendríamos que cambiar el número de repeticiones, que será el número de lados de nuestro polígono y el ángulo que giramos.

Si repasamos algo de geometría veremos que el giro también depende del número de lados y que es 360º dividido entre el número de lados

![Geometría del ángulo de giro para el polígono](./images/GeometriaAnguloGiroPoligono.png)

Comprobamos que para el caso del cuadrado concuerda con los 90º que girábamos.

Podemos comprobar que funciona poniendo 6 en el número de repeticiones y calculando el ángulo de giro y poniéndolo en el bloque "girar ".

Para hacer este cálculo podemos usar operadores aritméticos en la paleta "Operadores" y así usando el operador división sustituimos el ángulo por:

![Giro para el hexágono](./images/GiroHexagono.png)

Vemos que tenemos el bucle de la siguiente forma:

![BucleHexagono](./images/BucleHexagono.png)

El número de repeticiones siempre será igual al que usamos para calcular el ángulo. 

Tenemos ya claro lo que tenemos que hacer para un polígono genérico. Esta forma de pensar abstracta es lo que se conoce como **Algoritmo**: el listado de los distintos pasos que tenemos que hacer para completar una tarea de forma abstracta.

Vamos a trabajar un poco en abstacto, algebráicamente, suponiendo que el número de lados es NumeroLados y para ello vamos a crear una **Variable**: una cajita con un nombre, donde podemos guardar un valor. De esta manera podremos definir todo en el proceso en función de **NumeroLados** sin tener que especificar un valor concreto.

Vamos a la paleta **Variables** pulsamos "Crear una variable":

![Creamos la Variable NumeroLados](./images/VariableNumeroLados.png)

(Más adelante veremos la distintas opciones)

Ahora nos aparecen varios bloques:

* **Dar valor a**: nos permite asignar un valor a la variable. Siempre tenemos que utilizar este bloque para dar un valor a la variable antes de usarla. Si no lo hacemos ésta valdrá 0. Es un bloque con la típica forma rectangular de todos los bloques que representan **acciones**.

![Dar Valor a NumeroLados](./images/DarValorNumeroLados.png)

* **NumeroLados**: nos permite usar el valor de la variable y que será el que emplemos en los cálculos. Este bloque tiene forma redondeada, como los huecos donde tenemos que poner los valores de las cosas. Es un bloque de tipo **Valor**.

![Valor de NumeroLados](./images/ValorNumeroLados.png)

Y otros bloques que ya iremos viendo más adelante.

El bucle quedará ahora así:

![Bucle usando variable NumeroLados](./images/BucleVariable.png)

Donde hemos dado un valor a la variable NumeroLados y utilizamos su valor en el cálculo, para lo que habremos arrastarado el bloque redondeado "NumeroLados" en los correspondientes huecos.

Vemos que estamos calculamos el ángulo que tenemos que girar que será 360/NumeroLados.

Para terminar vamos a añadir un **Comentario**: Una indicación que incluímos en nuestro programar como información extrar para quien lo vea. Los comentarios no son instrucciones para el ordenador, son aclaraciones para las personas que vean el programa.

Hemos aprendido a calcular usando los operadores algebráicos.

El programa completo queda así:

![Programa Pintado Poligónos](./images/PintadoPoligonos.png)

[Programa Pintado Poligónos](https://scratch.mit.edu/projects/39420307)

Vemos la potencia para trabajar la geometría con Scratch.

[![Vídeo: Pintando polígonos](https://img.youtube.com/vi/xgVTnHNKFyo/0.jpg)](https://youtu.be/xgVTnHNKFyo)


###  3.6 La mochila

Usar **mochila**

Vamos a aprender a usar la mochila, que nos permite compartir grupos de bloques entre diferentes proyectos.

A mi juicio, es una de las mayores ventajas del uso de la versión online.


[![Vídeo: Uso de la mochila](https://img.youtube.com/vi/T8OXsgJQRbI/0.jpg)](https://youtu.be/T8OXsgJQRbI)

[Vídeo: Uso de la mochila](https://youtu.be/T8OXsgJQRbI)



3.7 Spirograph

Cómo descargar un programar
copiar bloques entre objetos
recuperar objetos borrado
Bucles anidados

Usamos la mochila para recuperar unos bloques de código que creamos en otro proyecto y que nos permitían dibujar polígonos
Añadimos un giro y un bucle que repite todo el proceso
Guardamos en nuestro disco duro el programa
Vemos cómo copiar los bloques de un objeto a otro

recuperar objetos borrado

![Programa Spirograph](./images/SpirographV2.png)
[Programa Spirograph](https://scratch.mit.edu/projects/394219217)


[![Vídeo: dibujando estrellas complejas](https://img.youtube.com/vi/tzjHbXfAJFA/0.jpg)](https://youtu.be/tzjHbXfAJFA)


[Vídeo: dibujando estrellas complejas](https://youtu.be/tzjHbXfAJFA)



### Tareaa 4.1: Dibujar una estrella

**No dar demasiadas explicaciones de cómo hacerlo**
