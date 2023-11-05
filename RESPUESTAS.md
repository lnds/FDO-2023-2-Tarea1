# Paso 6  

Agrega un archivo que se llame `RESPUESTAS.md` y anota allí las siguientes preguntas con sus respuestas:


1. ¿Si ejecutas el comand `git blame main.py` qué ocurre?

R. Se visualizan los cambios del archivo con el id de commit(hash) asociado y el usuario que lo realizó

2. Explica cómo funciona el comando log del paso 5

R. Este comando muestra el log de git con un formato "bonito(pretty)" seg{un argumentos que los acompaña, en la solicitud corresponde a:

  - %h:  corresponde al id(hash) de commit  
  - %an: corresponde al usuario que realizó el commit
  - %as: fecha en formato corto (YYYY-MM-DD) del commit realizado por el usuario.
  - %s: corresponde al mensaje asociado al commit
(Fuente [https://git-scm.com/docs/git-log](https://git-scm.com/docs/git-log#_pretty_formats))

3. ¿Cuántas veces modificó el archivo `README.md` el profesor? ¿Cómo determinaste ese número?

R. El archivo README.md fue modificado 6 veces por el profesor. Esto se obtuvo a través del comando 

```
git log --pretty=format:" - %h %an %as: %s" README.md
```

- Anota los nombres de los integrantes del grupo que realizó la tarea

R. Cristian Luttgue