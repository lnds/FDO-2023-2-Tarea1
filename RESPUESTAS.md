¿Si ejecutas el comand git blame main.py qué ocurre?
R: Se despliega el código fuente que está dentro del archivo main.py, indicando en cada linea la fecha de creación y el responsable.

Explica cómo funciona el comando log del paso 5
R: La línea de comando git log --pretty=format:" - %h %an %as: %s" sirve para mostrar el archivo log en forma personalizada.
  --pretty=format: Esta opción permite personalizar el formato de la salida.
  %h: Se refiere al hash abreviado del commit.
  %an: Se refiere al nombre del autor del commit.
  %as: Se refiere a la fecha del commit en formato corto (YYYY-MM-DD).
  %s: Se refiere al mensaje del commit.

¿Cuántas veces modificó el archivo README.md el profesor? ¿Cómo determinaste ese número?
 R: 4 veces. Gracias al comando línea de comando git log --pretty=format:" - %h %an %as: %s" que nos permite visualizar los cambios y al autor del commit.
  - 5a41842 Eduardo Díaz 2023-10-26: Update README.md
 - 335c0c2 Eduardo Díaz 2023-10-25: Update README.md
 - 329f5a9 Eduardo Díaz 2023-10-25: Update README.md
 - 886d0f0 Eduardo Díaz 2023-10-25: feat: Update README.md

Anota los nombres de los integrantes del grupo que realizó la tarea
 R: Daniel Sáez
