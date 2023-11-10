1.- ¿Si ejecutas el comand git blame main.py qué ocurre?
R: Muestra quién modificó por última vez cada línea del archivo main.py, junto con la confirmación (commit) en la que se realizó la modificación. Esta información permite rastrear quién modificó cada línea del archivo y cuándo se ejecutó la modificación 

2.- Explica cómo funciona el comando log del paso 5
R: Este comando se utiliza para ver el registro de commit de forma perzonalizada. La opción "--pretty=format" permite especificar un formato de salida personalizado para los registros de commits. En este caso, se está proporcionando un formato específico entre comillas.
Cada elemento del comando se detalla a continuación:
-: Simplemente agrega un guion y un espacio al principio de cada línea del registro.
%h: Se reemplaza con la abreviatura del hash del commit.
%an: Se reemplaza con el nombre del autor del commit.
%as: Se reemplaza con la fecha del autor del commit.
%s: Se reemplaza con el mensaje del commit.

3.- ¿Cuántas veces modificó el archivo README.md el profesor? ¿Cómo determinaste ese número?
R: Se modificó 5 bveces el archivo. Lo determiné revisando con el comando git blame README.md la cantidad de commit que se realizaron.

4.- Anota los nombres de los integrantes del grupo que realizó la tarea
R: Robert Valenzuela