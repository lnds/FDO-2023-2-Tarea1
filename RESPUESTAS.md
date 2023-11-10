-¿Si ejecutas el comand git blame main.py qué ocurre?
Se puede ver quién, ha hecho cambios en un archivo específico, en este caso en main.py, línea por línea, lo cual es útil si trabajas en equipo.


-Explica cómo funciona el comando log del paso 5

git log --pretty=format:" - %h %an %as: %s" ---> Historial de commits, en donde:

--pretty="..." define el formato de la salida.
%h   = es el hash abreviado del Commit
%an  = el nombre del autor
%as  = es la fecha en que se realizó 
%s   = el comentario


¿Cuántas veces modificó el archivo README.md el profesor? 
El profesor modificó 6 veces el archivo README.md 

94c9920 feat: add a question
5a41842 Update README.md
335c0c2 Update README.md
329f5a9 Update README.md
886d0f0 feat: Update README.md
5c2c29d feat: Create README.md




-¿Cómo determinaste ese número?
Obtuve el conteo de las 6 veces que modificó el archivo con el siguiente comando:

git log --author="Eduardo Díaz"  -- README.md   | wc -l



-Anota los nombres de los integrantes del grupo que realizó la tarea
Jimena ESter Silva Navarrete