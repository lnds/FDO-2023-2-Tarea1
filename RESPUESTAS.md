¿Si ejecutas el comand git blame main.py qué ocurre?
R: Se despliega el código fuente que está dentro del archivo main.py

Explica cómo funciona el comando log del paso 5
R: La línea de comando git log --pretty=format:" - %h %an %as: %s" sirve para mostrar el archivo log en forma personalizada.
  --pretty=format: Esta opción permite personalizar el formato de la salida.
  %h: Se refiere al hash abreviado del commit.
  %an: Se refiere al nombre del autor del commit.
  %as: Se refiere a la fecha del commit en formato corto (YYYY-MM-DD).
  %s: Se refiere al mensaje del commit.

¿Cuántas veces modificó el archivo README.md el profesor? ¿Cómo determinaste ese número?
 R: 10 veces. Gracias al comando %an que nos permite visualizar al autor del commit.

Anota los nombres de los integrantes del grupo que realizó la tarea
 R: Daniel Sáez - Julio Soto - Ariel Veliz - Javier Teillier
