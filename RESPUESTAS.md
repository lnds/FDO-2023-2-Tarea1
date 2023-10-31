# Respuestas

## ¿Si ejecutas el comand git blame main.py qué ocurre?
Se lista el historial de cambios respecto del archivo main.py, detalla línea por línea cual fue la última vez que se tocó/modificó mostrando el hash asociado al commit, nombre del autor, fecha de commit, número de línea y contenido de la línea.

Ejemplo:
~/Tarea-1-FDO-2023-2JaimeNorambuena$ git blame main.py
1bdeaa07 (Eduardo Díaz 2023-10-25 17:34:24 -0300  1) import os
1bdeaa07 (Eduardo Díaz 2023-10-25 17:34:24 -0300  2) import psycopg2
a43b0cb3 (Replit user  2023-10-31 01:00:33 +0000  3) from flask import Flask, render_template, request, url_for, redirect

## Explica cómo funciona el comando log del paso 5
Se utiliza git log para ver el historial de commit, se utiliza la opción pretty format para definir el formato de la salida de git log, de tal manera de que muestre el hash del commit (%h), seguido del nombre del autor (%an), luego la fecha del commit (%as), seguido de un dos puntos y espacio (: ) y finaliza con el mensaje del commit (%s).

## ¿Cuántas veces modificó el archivo README.md el profesor? ¿Cómo determinaste ese número?
Se modificó en total 5 veces (sin considerar la creación), se verificó con el comando git log.

~/Tarea-1-FDO-2023-2JaimeNorambuena$ git log --pretty=format:" - %h %an %as: %s" -- README.md 
 - 94c9920 Eduardo Díaz 2023-10-26: feat: add a question
 - 5a41842 Eduardo Díaz 2023-10-26: Update README.md
 - 335c0c2 Eduardo Díaz 2023-10-25: Update README.md
 - 329f5a9 Eduardo Díaz 2023-10-25: Update README.md
 - 886d0f0 Eduardo Díaz 2023-10-25: feat: Update README.md
 - 5c2c29d Eduardo Díaz 2023-10-25: feat: Create README.md

## Anota los nombres de los integrantes del grupo que realizó la tarea
