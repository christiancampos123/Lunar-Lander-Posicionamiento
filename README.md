# Proyecto Lunar Lander

Mi proyecto de Lunar Lander: https://rawgit.com/christiancampos123/Lunar-Lander-Posicionamiento/master/LunarLanding.html

En este proyecto he tratado de mantener la estetica que se me habia proporcionado desde un principio por "Ach".



#### Modificaiones visibles respecto al modelo inicial:

En la versión de mobil, en el css cambié el botón de power de posición con el objetivo de situarlo en el punto inferior izquierdo de la pantalla para mayor comodidad en esta versión.



### Modificaciones no visibles respecto al modelo inicial:

Muchas de las imagenes han tenido que ser recortadas debidamente para su posicionamiento y manejabilidad mas cómoda:
-imagen de la nave
-imagen de el "oil"
-imagen del marcador de aguja (este no es redondo de modo que ha sido dificil ajustar una aguja en el)
-imagen de la aguja
-imagen indivisible del mení (mal borrada y con restos de pintura en zonas que tenian que ser transparentes)


### Proyecto en la version PC:

#### Visualmente:

-La disposición de los sprites ha sido la siguiente:

  ·4 Divs grandes que dividen la pantalla verticalmente en 3 tramos de 30%,40%,30% respectivamente y uno abajo horizontalmente      
   del 40%.
   
  ·En el div izquierdo se dispone un div mas pequeño y y de la mitad de altura para disponer los paneles de fuel,altura y 
   velocidad en columna ocupando el ancho maximo de este div y un tercio con el "margin-bottom" aproximadamente de la altura. En
   particular el marcacdor de oil se compone de dos imagenes superpuestas que seran retocadas con java para que la barra
   dibujada inicialmente sea la que baje, por este motivo no esta hecho con divs superpuestos de colores. Y el marcador de aguja
   tiene independientemente la aguja y el marcador.(cada marcador esta en un div individual con las medidas proporcionales de 
   las imagenes).
   
  ·En el div central esta un div mas pequeño con la imagen de la nave en el y que ocupa el ancho maximo de el div central y una                       
   altura proporcional al 20% de la pantalla para hacer que la nave ocupe el 20% que se pide.
   
  ·En el div derecho se encuentra un div mas pequeño en la parte superior que ocupa el ancho del div que lo contiene y a su 
   misma vez contiene pequeños divs anchos que contienen la imagen de cada boton con sus medidas y cada imagen redirecciona a 
   un enlace a la misma pagina para demostrar que son funcionales.
   
  ·En el div inferior se encuenra la imagen de la luna que llega de punta a punta, y dentro contiene dos divs, uno para situar 
   la base de aterrizaje situada en la posición indicada en el modelo inicial y el botón de power situado a la derecha de la
   base, este ulitmo tambien funcional y con la misma dirección que los anteriores.
   
  ·Finalmente esat el menú con un "z-index" mayor a los demas objetos situados
  
-Las imagenes no eran proporcionales a una imagen 1080p de modo que sprites como la luna (para respetar el modelo) se han 
 estirado o comprimido (como en la version movil, que se tretará después).
-Los botones no han sufrido cambios y se han adaptado tal y como el proyecto inicial.
-El sprite del menú era indivisible y fijo, por tanto así se ha mantenido.


