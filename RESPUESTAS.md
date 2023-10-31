
1) ¿Si ejecutas el comand git blame main.py qué ocurre?

Aparece linea por linea quien ha hecho cambios en el archivo y cuando los hizo. En este caso, por ejemplo:

1bdeaa07 (Eduardo Díaz 2023-10-25 17:34:24 -0300  1) import os
1bdeaa07 (Eduardo Díaz 2023-10-25 17:34:24 -0300  2) import psycopg2
eeeac5f7 (Replit user  2023-10-30 23:06:35 +0000  3) from flask import Flask, render_template, request, url_for, redirect
1bdeaa07 (Eduardo Díaz 2023-10-25 17:34:24 -0300  4) 
3e86031f (Replit user  2023-10-25 20:48:53 +0000  5) VERSION = "v0.1.0"


2) Explica cómo funciona el comando log del paso 5

La funcion del comando: git log --pretty=format:" - %h %an %as: %s", es mostrar un historial de commits del repositorio. Además, con "pretty= format" se indica un formato para mostrarlo. En este caso, se muestra el hash del commit, autor, fecha y comentarios.

3) ¿Cuántas veces modificó el archivo README.md el profesor? ¿Cómo determinaste ese número?
4 veces. Lo determine contando estos commits

 - 886d0f0 Eduardo Díaz 2023-10-25: feat: Update README.md
 - 35c0c2 Eduardo Díaz 2023-10-25: Update README.md
 - 329f5a9 Eduardo Díaz 2023-10-25: Update README.md
 - 5a41842 Eduardo Díaz 2023-10-26: Update README.md

4) Anota los nombres de los integrantes del grupo que realizó la tarea
Sebastian Jara
