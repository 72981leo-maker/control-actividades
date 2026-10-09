1. Analiza
git status: Revisa: Muestra los archivos modificados que aún no se han preparado.
git add README.md: Prepara (Stage): Coloca el archivo README.md en la lista de cambios listos para guardarse.
git commit -m "Actualiza documentación": En esta se plante la forma de subir tu trabajo a un repositorio que a la vez va a github
git push: Este comando hace subir cualquier cambio a tu githyb o repositorio que ya allas hecho previamente.

2. Identifica qué falta
Caso A
Modificar archivo
↓
git add .
↓
¿?
↓
git push
R= podria ser el git status para checar si ya esta para poder subir y asignarle un nombre del cambio

Caso B
Repositorio GitHub
↓
¿?
↓
Repositorio local
R= este podria ser el git commit -m "nombre del proyecto"

Caso C
Repositorio remoto actualizado
↓
¿?
↓
Repositorio local actualizado
R= este seria el git pull