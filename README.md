# ExamenEntornos
\
![download](https://github.com/Marcgb2003/ExamenEntornos/assets/122601138/c6240820-17c4-44a7-86d3-071481ed0a61)

\
Hay que tener en consideración que en mi diagrama a la clase Planta se la considera un contenedor de Libros nada más, por lo que no tiene ningún método.
Al ser el mismo bibliotecario el que se presta un libro a si mismo, no tiene porque llamar a otro en la función préstamo, pero sí que necesita un int porque, al tener su prestamo condiciones especiales de tiempo, en vez de recibir el tratado de 30 días, lo que se recibe es  el número de días que se lo llevará. A parte de eso la clase biliotecario es más una clase de interacción fuera de ella, tanto en Biblioteca como en Prestamo, que una que haga cosas en si misma.
\
Préstamo depende tanto de Usuario como de Bibliotecario, ya que si no existe un Bibliotecario no puede haber un préstamo, ya que son quienes los efectuan, y los usuarios quienes los piden. A su vez los usuarios y los bibliotecarios no pueden existir fuera de la biblioteca como tales.
\
Por último, la relación Libro-Prestamo es de 1-0...* ya que un libro puede ser prestado n veces, mientras su int EjemplaresDisp sea mayor que 0, pero también puede estar sin prestar; y a sui vez si no existe la planta que le corresponda, no existirá el libro, y a su vez, si no existe la biblioteca, la planta no puede existir.
