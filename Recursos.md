## Trabajando con recursos
 
Llamamos recursos a todos aquellos materiales que usamos dentro de nuestro programa:
* Textos, que podemos copiar o redactar. Serán los que lean o se muestren en el programa.
* Imágenes, que buscaremos o que tendremos que crear, o fotografiar. Serán los fondos y los personajes de nuestro programa.
* Sonidos, que tendremos que buscar.
* Música, normalmente la descargaremos, cuidado con las licencias.
* Grabaciones, que haremos nosotros mismos. Para ello necesitamos un micro en  nuestro ordenador o bien usar un móvil o tableta para grabarlo y luego pasarlo al ordenador.

Muchas veces el preparar estos recursos es la parte más importante del proceso y donde nuestros alumnos trabajan más los contenidos.

También será necesario en ocasiones saber editar mínimamente estas imágenes, sonidos y músicas, así como compartirlas entre los distintos dispositivos.

## Ejemplo: "Canción del Pirata" de Espronceda

Vamos a hacer un programa que muestre a un personaje recitando "Canción del Pirata" de Espronceda, añadiremos música, y nos grabaremos nosotros mismos recitándolo.

### Elegimos personaje, fondo y mostramos el texto

Vamos a hacer un programa que recite la "Canción del Pirata" de Espronceda, mostrando texto en pantalla:
* Borramos a nuestro gatito. Recordamos que cada componente tiene sus propios bloques: el personaje tiene sus bloques y  el fondo también tiene los suyos (no incluye los de movimiento)
* Elegimos un nuevo personaje de la galería, viendo los distintos pasos de sus animaciones o los diferentes disfraces. Podemos filtrar por tipos de personajes o buscar por palabras
* Elegimos un nuevo fondo, en este caso un escenario de la galería de fondos, donde también podemos buscar o ver las distintas categorías. 

En un proyecto posterior veremos que podemos subir imágenes para usar como fondos y para crear personajes.

* Movemos el personaje arrastrándolo con el ratón a la posición que más nos guste. 
* Podemos cambiar el tamaño del personaje usando los controles que hay encima del personaje (debajo del escenario): **x** e **y** para la posición y **Tamaño**. Dirección se refiere hacia donde mira el personaje. Más adelante lo usaremos.

![Posición y tamaño del personaje](./images/PosicionTamañoPersonaje.png)

Más adelante veremos que podemos mover nuestros personaje y cambiar su tamaño usando bloques.
* Ponemos el evento de "Al pulsar la bandera"
* Cambiamos entre los distintos pasos de animación a lo largo del poema usando "Cambiar disfraz a ..." 
* Buscamos el texto del poema (recordar luego añadir la fuente del texto como reconocimiento)
* Añadimos bloques de "Decir ... durante x segundos" .
* Copiamos los distintos versos a distintos bloques.

### Ampliaciones/Mejoras

* Añadir movimientos al personaje
* Incluir más fotogramas de animaciones o más posturas del personaje
* Usar distintos fondos a lo largo del poema 


[![Vídeo: Programa Scratch que muestra el texto de la "Canción Pirata" de Espronceda](https://img.youtube.com/vi/M1dhIRl6muI/0.jpg)](https://youtu.be/M1dhIRl6muI)

[Vídeo:  Programa Scratch que muestra el texto de la "Canción Pirata" de Espronceda](https://youtu.be/M1dhIRl6muI)

### Añadimos algo de música

Añadimos música de fondo a nuestra "Canción del Pirata"

* Seleccionamos una música (cuidado con las licencias).
* Subimos el fichero al proyecto como sonido (pueden ser mp3, au, wav, AIFF como indica en la documentación de [Scratch](https://en.scratch-wiki.info/wiki/What_sound_formats_can_I_import_into_Scratch%3F) ) Pero podemos convertir otros formatos con Audacity por ejemplo.
* Usando el editor de Scratch 3.0 podemos recortar el sonido o cambiar su volumen si no lo necesitamos.
* Seleccionamos el bloque de la paleta de sonido de "Iniciar sonido" (la alternativa sería "reproducir sonido" pero esperaría hasta terminar y no es lo que queremos).
* Para dejar un poco de tiempo entre el comienzo de la música y que se muestren los textos podemos añadir un bloque "Esperar" desde la paleta "Control" con los segundos necesarios.

Tenemos que tener cuidado con las licencias de los sonidos, como veis he tenido que cambiar el sonido del vídeo por tema de licencias con youtube.

Existen muchas colecciones de música libre, por ejemplo la [biblioteca de música libre de Youtube](https://www.youtube.com/audiolibrary/music?feature=blog&nv=1).

Si entráis en el proyecto https://scratch.mit.edu/projects/391768718/ sí que se oye la música de "Piratas del Caribe".

[![Vídeo: Añadimos música de fondo a nuestra "Canción Pirata"](https://img.youtube.com/vi/WOX6ig3TkXI/0.jpg)](https://youtu.be/WOX6ig3TkXI)

[Vídeo: Añadimos música de fondo a nuestra "Canción Pirata"](https://youtu.be/WOX6ig3TkXI)

### Mejoramos los movimientos y animación del personaje

Vamos a modificar las imágenes de los disfraces de nuestro personaje para darle más movimientos.

* Entramos en la pestaña de los disfraces del personaje.
* Vemos los distintos fotogramas que tiene el personaje.
* Duplicamos el fotograma que queremos que sea la base para el nuevo.

La mayoría de los disfraces son dibujos vectoriales, eso quiere decir que están creados a partir de formas y trazos. Es como si contuvieran las instrucciones para generarlos.

Nosotros estamos acostumbrados a las imágenes de mapa de bits, formadas por la información de color de cada uno de los píxeles que lo forman.

El editor de imágenes de los disfraces es un editor vectorial donde  podemos seleccionar las distintas formas con la herramienta de selección (la flecha) y modificar su tamaño, girarlos o cambiar su color.

* Podemos Reflejarlo (como en un espejo o cámara de selfie) para que mire en otra dirección.
* Seleccionar alguna de las partes y girarla, rotarla o cambiarla de tamaño.

Es conveniente renombrar los distintos fotogramas para que luego podamos usarlos fácilmente desde los bloques.

[![Vídeo: Animación de los personajes de Canción del Pirata. Editando los Disfraces](https://img.youtube.com/vi/kfv99XMgIqI/0.jpg)](https://youtu.be/kfv99XMgIqI)


[Vídeo: Animación de los personajes de Canción del Pirata. Editando los Disfraces](https://youtu.be/kfv99XMgIqI)


### Nos grabamos leyendo el poema

Vamos a grabarnos leyendo la Canción del Pirata para mostrar los versos y oírlos a la vez.

* En la pestaña de sonidos, nos grabarnos leyendo los versos de uno en uno.
* Podemos usar el editor de sonidos para arreglar las grabaciones, recortando los silencios iniciales o finales.
* Si pulsamos con el botón derecho sobre uno de los sonidos podemos exportar a un fichero para usarlo en otro lugar.
* Si queremos modificar una parte del sonido, seleccionando esa parte, y modificamos el tono de la grabación haciéndola más aguda o grave.  pulsando en "Más rápido" o "Más lento", también darle más o menos volumen , o invertirlo e incluso hacer que suene robótica.
* Al reproducirse a la vez que la música, conviene ajustar los volúmenes de ambas.

[![Vídeo: Nos grabamos leyendo la Canción del Pirata y lo añadimos a nuestro programa](https://img.youtube.com/vi/LR9n8gcgjYA/0.jpg)](https://youtu.be/LR9n8gcgjYA)

[Vídeo: Nos grabamos leyendo la Canción del Pirata y lo añadimos a nuestro programa](https://youtu.be/LR9n8gcgjYA)


### Mejoras/Ampliaciones
* Completar los versos
* Usar distintas voces para distintas partes
* Jugar con los efectos

## Ejemplo: Mostrando nuestro patrimonio andaluz

Vamos a hacer una aplicación que nos permita mostrar un  recorrido por las provincias andaluzas, mostrando imágenes de diferentes monumentos y contándonos información sobre lo mostrado.

Hablaremos de:
* Licencias de contenidos
* Movimiento d epersonajes
* Fondos: Añadir imágenes como fondos
* Extensiones: Texto a voz

![Recorrido Andalucia: Mapa](./images/RecorridoAndaluciaMapa.png)

Es importante que recordemos la importancia de usar fuentes de información con la licencia adecuada y las citemos.

### Recorrido por Andalucía: el mapa

Comenzamos seleccionando el personaje y buscando una imagen de un mapa de Andalucía:

* Buscamos una imagen de un mapa de Andalucía con buena resolución y la licencia adecuada.
* Cargamos la imagen como fondo.
* Adaptamos el tamaño de la imagen.
* Buscaremos un personaje de entre los disponibles en la galería.

[![Vídeo: Recorrido por Andalucía: Mapa](https://img.youtube.com/vi/1JZNGv_Eb0k/0.jpg)](https://youtu.be/1JZNGv_Eb0k)


[Vídeo: Recorrido por Andalucía: Mapa](https://youtu.be/1JZNGv_Eb0k)

### Recorrido por Andalucía: movimiento y textos

Vamos a hacer que nuestro personaje se mueva por el mapa y muestra la información sobre los monumentos:

* Nuestro personaje se presenta.
* Aprenderemos a situar al personaje en unas coordenadas adecuadas.
* Buscaremos imágenes con licencia libre sobre el monumento que  queremos mostrar.
* Crearemos fondos con las distintas imágenes.
* Buscaremos información y elaboraremos los textos que se mostrarán.

El personaje irá recorriendo las distintas provincias, moviéndose por sobre el mapa y deteniéndose sobre cada provincia.

* Aprenderemos a hacer que el personaje se desplace a una nueva posición.
* Al llegar cambiaremos el fondo al de monumento a mostrar.
* El personaje nos mostrará los textos creados sobre el monumento en cuestión.

[![Vídeo: Recorrido por Andalucía: movimiento y textos](https://img.youtube.com/vi/XX4XMdLFpgI/0.jpg)](https://youtu.be/XX4XMdLFpgI)

[Vídeo: Recorrido por Andalucía: movimiento y textos](https://youtu.be/XX4XMdLFpgI)

### Narrando textos de manera automática con la extensión "Texto a voz"

Podíamos grabar los textos nosotros mismos, pero en esta caso vamos a explorar la posibilidad de usar una extensión que nos permite leer los textos, con diferentes voces, incluso en diferentes idiomas.

* Añadimos la extensión Text to Speech, que necesita conexión a Internet (no funciona en modo desconectado)
* Añadimos bloques de decir "texto".

[![Vídeo: Recorrido por Andalucía: añadimos  Voz](https://img.youtube.com/vi/C2iAbpmEHOE/0.jpg)](https://youtu.be/C2iAbpmEHOE)

[Vídeo: Recorrido por Andalucía: añadimos  Voz](https://youtu.be/C2iAbpmEHOE)


### Mejoras/Ampliaciones: 
* Añadir más textos
* Añadir más monumentos
* Completar todas las provincias

### Ideas/Otras Aplicaciones:
* Mapa e información del centro
* Explicación de las partes de un planta
* Partes de una máquina/motor