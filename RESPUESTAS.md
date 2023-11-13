## ¿Si ejecutas el comand git blame main.py qué ocurre?
  R: Lista el datalle a nivel de modificaciones en el archivo main.py, el detalle es linea a linea y muestra el usuario, fecha y hora del commit.

## Explica cómo funciona el comando log del paso 5
  R:el comando log muestra la informacion sobre los commit, adicionado el pretty se muestra de forma legible/bonita la informacion. con format se maneja la salida, en este caso el string en donde "%h" muestra el id/hash del commit, "%an" nombre usuario/autor, "%as" la fecha y %s el mensaje/subject del commit. Con esto se forma un mensaje de log ordenado y facil de comprender.

## ¿Cuántas veces modificó el archivo README.md el profesor? ¿Cómo determinaste ese número?
  R: Por el subject en los commit fueron 4 veces, lo que se puede ver con el comando log, tambien es coherente al ejecutar blame del archivos que muestra cambios en 4 ocaciones (el 25/10 a las 17:33 y 18:12 hrs y el 25/10 a las 14:01 y 14:46)

## Anota los nombres de los integrantes del grupo que realizó la tarea
 R: Alejandro Montoya