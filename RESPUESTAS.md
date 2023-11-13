
- ¿Si ejecutas el comand git blame main.py qué ocurre?
  
   Muestra las líneas del archivo main.py y cual fue la ultima persona en modificar esa linea y hacer commit.  blame = culpable

- Explica cómo funciona el comando log del paso 5
  
   Permite ver el log o historial del proyecto mediante marcadores de posición de estilo printf, en este caso con un formato que muestra el hash autor fecha y comentario del commit

- ¿Cuántas veces modificó el archivo README.md el profesor? ¿Cómo determinaste ese número?
  
   Fue modificado 6 veces por el profesor.
   con este comando y contando las lineas donde aparece nombre del profesor pude determinar ese numero
  
           git log --pretty=format:" - %h %an %as: %s" README.md

- Anota los nombres de los integrantes del grupo que realizó la tarea
  
   Franklin Cruces
