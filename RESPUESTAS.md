# ¿Si ejecutas el comand git blame main.py qué ocurre?
Muestra quién, cuándo, y en qué línea de código se hizo modificación (inserción/modificación)

# Explica cómo funciona el comando log del paso 5
El comando git log --pretty=format:" - %h %an %as: %s" sirve para personalizr el formato de salida del git log. En este caso:

%h: hash del commit
%an: autor del commit
%as: fecha del commit
%s: mensaje del commit

# ¿Cuántas veces modificó el archivo README.md el profesor? ¿Cómo determinaste ese número?
De acuerdo a lo reportado por git log, el archivo README.md se creó una vez y luego se le realizó update cuatro veces por parte del profesor

# Anota los nombres de los integrantes del grupo que realizó la tarea
Rodrigo Muñoz Soto