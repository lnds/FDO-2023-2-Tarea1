# Respuestas

### Pregunta 1 : ¿Si ejecutas el comand git blame main.py qué ocurre?

Cuando se ejecuta el comando git blame main.py nos entrega un historial, o log de los cambios que han ocurrido en el archivo, con su respectivo commit hash, usuario que realizó el respectivo cambio y el respectivo texto que fue agregado.

### Pregunta 2: Explica cómo funciona el comando log del paso 5

El comando de log, nos indica que commits han sido realizados históricamente en el repositorio, dentro de la rama en la cual estamos situados. De la misma manera se realiza el formateo del log, de manera que tengo un formato " - %h %an %as: %s"
%h: abbreviated commit hash
%an: author name
%as: author date, short format (YYYY-MM-DD)
%s: subject

Esta información fue obtenida desde: https://mirrors.edge.kernel.org/pub/software/scm/git/docs/git-log.html#_pretty_formats

### Pregunta 3: ¿Cuántas veces modificó el archivo README.md el profesor? ¿Cómo determinaste ese número?

179 veces, esto fue obtenido realizando el comando de git blame README.md, lo que nos dice que se realizan todas esas modificaciones.
Si uno habla con respecto a commits donde estuvo presente algún cambio de este archivo, también con el git blame README.md se puede obtener que fueron 4 commits.

### Pregunta 4: Anota los nombres de los integrantes del grupo que realizó la tarea

Sebastián Urbano