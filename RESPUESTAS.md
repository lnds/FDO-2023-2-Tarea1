¿Si ejecutas el comand git blame main.py qué ocurre?
R: Muestra un log detallado de los cambios en el archivo main.py, mostrando información de la referencia al commit correspondiente a cada línea del archivo, junto con el usuario y fecha de la inserción/cambio.

Explica cómo funciona el comando log del paso 5
R: El comando git log acepta la orden --pretty, esta orden acepta el valor 'format' que permite indicar a git cómo y qué datos queremos ver. En este caso se usa la cadena " - %h %an %as: %s", permite ver la salida del comando con caracteres fijos y algunos variable donde los variables son: %h, muestra el identificador del commit (hash). %an, muestra el nombre del autor del commit. %as, muestra la fecha del cambio. %s, muestra el asunto del commit.

¿Cuántas veces modificó el archivo README.md el profesor? ¿Cómo determinaste ese número?
R: Con la ejecución del comando git log se ve que luego de creado el archivo, este fue modificado 4 veces. Lo determino con el comando git log.

Anota los nombres de los integrantes del grupo que realizó la tarea
R: Roberto Catalán H.