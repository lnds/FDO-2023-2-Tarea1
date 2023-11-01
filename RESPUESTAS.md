## ¿Si ejecutas el comand git blame main.py qué ocurre?

Va a mostrar línea por línea del archivo quién realizo el último cambio

## Explica cómo funciona el comando log del paso 5

git log muestra el historial completo de los commit realizados en el proyecto, a este comando se le puede dar parametros para poder ver los campos especificos en el orden que se le defina. 

- El %h muestra el hash del commit de confirmación abreviado
- El %an muestra el nombre de quien realizo el commit
- El %as muestra la fecha del commit, formato corto ( YYYY-MM-DD)
- El %s muestra el mensaje que se agregó al commit

## ¿Cuántas veces modificó el archivo README.md el profesor? ¿Cómo determinaste ese número?

Se modificó 6 veces, se puede ver por medio del comando anterior agregando al final -- nombrearchivo

```
git log --pretty=format:" - %h %an %as: %s" -- README.md
```

## Anota los nombres de los integrantes del grupo que realizó la tarea
Rodrigo Sáez