
## ¿Si ejecutas el comand `git blame main.py` qué ocurre?


Permite ver que cambios se realizaron en el archivo `main.py` y quien los realizó, linea por linea

## Explica cómo funciona el comando log del paso 5

`git log --pretty=format:" - %h %an %as: %s"` es un comando de Git que se utiliza para ver el historial de commits con un formato personalizado

- `git log`: Este es el comando base para ver el historial de confirmaciones en Git.

- `pretty=format:" - %h %an %as: %s"`: Esto es una opción que le dice a Git cómo formatear la salida del registro. En este caso, el formato está definido entre comillas dobles y contiene varios marcadores de posición:
  - `%h` : Representa el hash corto (abreviado) de la confirmación.
  - `%an`: Representa el nombre del autor del commit.
  - `%as`: Representa la fecha de autoría en formato corto.
  - `%s` : Representa el mensaje del commit.


## ¿Cuántas veces modificó el archivo `README.md` el profesor? ¿Cómo determinaste ese número?

Con el comando `git log --pretty=format:" - %h %an %as: %s" --author="Eduardo Díaz" -- README.md` se puede obtener los cambios del archivo README.md del autor Eduardo Días (Profesor). Como resultado muestra lo siguiente:

```
 - 94c9920 Eduardo Díaz 2023-10-26: feat: add a question
 - 5a41842 Eduardo Díaz 2023-10-26: Update README.md
 - 335c0c2 Eduardo Díaz 2023-10-25: Update README.md
 - 329f5a9 Eduardo Díaz 2023-10-25: Update README.md
 - 886d0f0 Eduardo Díaz 2023-10-25: feat: Update README.md
 - 5c2c29d Eduardo Díaz 2023-10-25: feat: Create README.md
```  
Por lo tanto, se puede observar que el profesor ralizó en __6__ oportunidades cambios en el archivo README.md

## Anota los nombres de los integrantes del grupo que realizó la tareagit 
* Helena Alvarado
* Ariel Pinto
* Juan Barraza
* Claudio Galleguillos
* Rodrigo Navarro
