¿Si ejecutas el comand git blame main.py qué ocurre?

- Se puede visualizar las líneas de código del archivo main.py indicado las modificaciones del archivo con los signos + y - . Además se logra identificar a la persona que ejecutó los cambios, junto con la fecha y hora.
- Las modificaciones además tienen un código abreviado, que es con el cual podemos hacer seguimiento con git log, dado que indica el commit que tiene asociado ese cambio.


Explica cómo funciona el comando log del paso 5

- El comando ejecutado realiza un git log con formato, es decir:
  - %h  -> indica que traiga el hash de forma abreviada
  - %an -> indica quien realizó el commit.
  - %as:-> indica la fecha en que se realizó el commit agregando al final un ":"
  - %s  -> indica el nombre del commit ejecutado.
- Con toda estos commandos podemos dar formato al git log y así poder ver de forma más ordenada y simple.

¿Cuántas veces modificó el archivo README.md el profesor? ¿Cómo determinaste ese número?

- El archivo fue modificado 4 veces
- Se realiza la ejecución del comando del paso 5 y determinamos el autor del commit y el comentario del commit: El autor es Eduardo díaz, el profesor, y el comentario del commit indica "UPDATE" y el nombre del archivo en cuestión, por lo que se realiza 4 veces esa acción.


Anota los nombres de los integrantes del grupo que realizó la tarea
- Julio Soto Sánchez.