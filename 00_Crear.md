## Definir
* El `jugador` va a `ubicaciones`.
* El `jugador` puede necesitar ciertos `elementos` para ingresar a una `ubicación`.
* En la `ubicación` podría tener una `misión` disponible.
* Para completar una `misión`, el `jugador` debe recoger ciertos `objetos` y entregarlos.
* El `jugador` puede recoger `objetos` yendo a un lugar y luchando contra `monstruos` allí.
* El `jugador` lucha contra `monstruos` con `armas`.
* El `jugador` puede usar una `poción` para sanarse mientras lucha.
* El `jugador` recibe objetos después de derrotar a un `monstruo`.
* Al finalizar la `misión`, el jugador recibe `objetos` de recompensa.




Los sustantivos serán las **clases / objetos** :

* Jugador
* Ubicación
* Objeto
* Misión
* Monstruo
* Arma
* Poción




## Propiedades 
Las propiedades de las clases u objetos se almacenan en una variable y podemos cambiarla segun el programa este corriendo. Un ejemplo es la cantidad de oro que tiene el jugador.


### scope
Principalmente vamos a utilizar Publica/privada. Las podemos poner delante tanto de una clase como de una propiedada.
_Public_ significa que va a ser visible desde todo el programa.

{ get; set; }
Esto detras de una propiedad signica que va a obtener un valor (_get_), que va a leer lo que esta almacenado en la propiedad. Y va a establecer un valor (_set_), almacenar un valor en la propiedad.

### class level variant
Este tipo de variable va a ser vista por todo en la clase.

### inheritance
Herencia. Cuando las clases representan el mismo tipo de cosas y tienen propiedades similares.
Se crea una clase BASE por ejemplo **Objeto** y las subclases serán **Arma** y **Poción**. Tambien crearemos una clase BASE llamada **Personajes** en la que estarán los Mounstros y el Jugador y compartiran las propiedades de salud maxima y salud actual.


## Tipos de datos
Que tipo de datos van a ser cada variable.

Principalmente son: Números enteros (integers) o palabras/frases (strings).


#### Propiedades de la clase: Jugador
* La salud actual del Jugador  (in case they've lost any during battle)
* La salud maxima del Jugador (when they are fully healed)
* La cantidad de oro del Jugador
* La cantidad de experencia del Jugador
* El nivel del jugador

El tipo de dato sera para todas estas propiedades Números enteros (integer). 
