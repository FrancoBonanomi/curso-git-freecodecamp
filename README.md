# Informacion de ayuda

## Renombrar ramas

Para poder renombrar una rama utilizamos el comando: `git branch -m "nombre de la rama"`,

**ACLARACION**:Este comando debe ejecutarse desde la rama a la cual se le desea cambiar el nombre

## Eliminar el ultimo commit

para poder eliminar el ultimo **_commit_** en mi repositorio local debo ejecutar el comando: `git reset --hard HEAD~1`, esto eliminara tambien el contenido del archivo correspondiente a ese commit, si queremos simplemente eliminar el **_commit_** manteniendo el contenido del archivo lo hariamos con: `git reset --hard SOFT~1`, es como si volvieramos en el tiempo al momento en que el archivo estaba en el **WD** (_working directory_) antes de ser commiteado.
