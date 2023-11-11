1. ¿Si ejecutas el comand git blame main.py qué ocurre?  
R: Aparece un listado de los cambios realizados en el archivo y qué usuario los realizó.

2. Explica cómo funciona el comando log del paso 5  
R: `git log` muestra un listado de todos los commit realizados en orden inverso, del más nuevo al más antiguo. En este caso de la rama main.  
La opción `--pretty=format` permite definir en qué formato queremos ver el listado de commits.  
La cadena de formato `" - %h %an %as: %s"` se compone de la siguiente manera:  
`-`: muestra un guión al inicio de cada línea.  
`%h`: Muestra el hash del commit abreviado.  
`%an`: Muestra el nombre del autor del commit.  
`%as`: Muestra la fecha del commit.  
`%s`: Muestre el mensaje que se agrega al crear el commit.    

3. ¿Cuántas veces modificó el archivo README.md el profesor? ¿Cómo determinaste ese número?  
R: Lo modificó 6 veces. Usé el comando `git log README.md`

4. Anota los nombres de los integrantes del grupo que realizó la tarea   
R: Javier Teillier