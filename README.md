# Informacion de ayuda

## Renombrar ramas

Para poder renombrar una rama utilizamos el comando : `git branch -m "nombre de la rama"`,

**ACLARACION** : Este comando debe ejecutarse desde la rama a la cual se le desea cambiar el nombre

## Eliminar el ultimo commit

para poder eliminar el ultimo **_commit_** en mi repositorio local debo ejecutar el comando: `git reset --hard HEAD~1`, esto eliminara tambien el contenido del archivo correspondiente a ese commit, si queremos simplemente eliminar el **_commit_** manteniendo el contenido del archivo lo hariamos con: `git reset --hard SOFT~1`, es como si volvieramos en el tiempo al momento en que el archivo estaba en el **WD** (_working directory_) antes de ser commiteado.

## Diferencias entre git pull y git fetch

`git pull` sirve para incorporar los cambios hechos en un repositorio remoto en nuestro repositorio local y `git fetch` sirve unicamente para verificar los cambios realizados en el repositorio remoto (sin combinarlos) desde la ultima vez que se hizo un pull, para previsualizar los cambios antes de hacer el pull puedo ejecutar el siguiente comando: `git checkout origin/main`, luego puedo regresar a la rama deseada con `git checkout`.
