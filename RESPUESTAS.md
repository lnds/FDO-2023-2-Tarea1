# Respuestas

¿Si ejecutas el comand git blame main.py qué ocurre?
  Git mostrará la información de quién realizó cada línea de un archivo particular, junto con el último commit en el que se modificó dicha línea
Explica cómo funciona el comando log del paso 5
  1. Muestra historial de los commit
  2. muestra en orden cronologico descendente
  3. puede proporcionar informacion detallada
  4. muestra el seguimiento
  5. sirve para la depuracion y analisis
     
¿Cuántas veces modificó el archivo README.md el profesor? ¿Cómo determinaste ese número?
  con comando
  git log --author="Eduardo Díaz" --pretty=oneline --count README
    .md
    94c9920a4312f38100e82b2dfaebcf9721b91fbc feat: add a question
    5a418424b2c8cb6f2529b3a64b6b0b87839abf57 Update README.md
    335c0c2133a2b42eeccd0a183b9d07c597fd5ab3 Update README.md
    329f5a9051883cea94a4810b71258b1321a8e797 Update README.md
    886d0f09e87b286f7f00e9cc46dd3fa6267fc6d8 feat: Update README.md
    5c2c29d467940616f0f486833fdb5633e8521d0b feat: Create README.md

Anota los nombres de los integrantes del grupo que realizó la tarea
  Daniela Julio
  Marisleydis Socas 
  Erikson Fuenzalida
  Eugenio Bravo