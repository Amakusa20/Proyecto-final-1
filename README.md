8# Proyecto-final-1
Hola profe, en su momento el proyecto funciono medianamente bien, luego la compu en el q estaba se perdio por lo que lo termine en mi compu vieja, y no me funciona el maven entre otras cosas por lo que no se que tan bien esta este preoyecto.
En principio era un proyecto de una inmobiliaria, pero se me rabo mucho por lo que fui a lo seguro, ademas que erroneamente no subia los cambios del proyecto a mi github.
Me apoye en investigar en internet y en mi hermana quien ya egreso de ADA y trabaja felizmente en una multinacional hace dos años, el proyecto lo hice sola 
ya que soy policia, mis guardias son de entre 24 y 72 hs por lo que me manejo de forma off line y me atraso mucho, y si bien entiendo las clases, me cueta mucho
desenvolverme sola por lo que no quise atrasar a ninguna compañera o ponerlas en compromiso porque yo no entiendo tal vez tanto como ellas.
Espero que se entienda lo que quise hacer.
Alguna vez  A las detención descargado se abre en el visual studio code
 Ahora aparecen varios archivos del por.xml, No acabe de la configuración del spring booth de las dependencias.
 Ya te entendemos dejo mi código,
 Secret una carpeta llamada services y ahí la estructura básica de springboot.
 En aplicación.properi  Lo puse las propiedades que necesito para colectar conmigo hace de datos,
 Ya tenía amiga se datos creada  Aunque vacía.
 Para ver qué funciones cree usuario model. java, tengo un ID de tipo Long, nombre y email tipo string y prioridad que es tipo entero.
Tengo que tener set y get .
 Importe de las bibliotecas.
ENTINITY
 Pongo las propiedades del id, Digo que se genera automáticamente, Se autoincrementa,  Es único y puede ser  nulo.
 En la terminal corro mvnw.cmd Spring-boot:run.
 Reviso mi base de datos Cómo se llama el y tengo en las tardes con las propiedades que les di.
 De las ahora toca el controlador repositorio de servicio del usuario,
 Es mi todo inicia el controlador, inicia la petición web que manda a llamar al servicio que es el que ejecuta la lógica de la aplicación, luego utiliza el repositorio que hace las conexiones a la base de datos
Desarrollo el metodo obtener usuario y va a ser de tipo arraylist y me va a regresar varios objetos de tipo usuario model. Osea q espero ver la lista de usuarios q tengo en la.base de datos y para eso uso el.repositorio q ya importe.
El siguiente método q sería registrar un usuario en la base de datos, la información la mandamos por medio de algo q ya tiene su información pero no tiene el ID, lo q regresa es la misma información  pero con el.id asignado.
Ya en el controlador , le agrego la etiqueta restcontroller que le dice a springboot  q es su función, y un requestMappin que dice en que dirección del.servidor se va a activar esta clase, en mi caso /usuario. creo otro getMappin 
para q cuando llegue una petición get ejecute ese flujo, en este caso el usuario.
Ahora la etiqueta postMappin me regresa el usuario pero con el.id.
Yo uso el postman agrego la ruta, en mi caso localhost/usuario ahí ingreso el usuario, y me regresa el mis.o usuario con id, y si lo abro en el navegador también voy a ver los usuarios con sus id.
