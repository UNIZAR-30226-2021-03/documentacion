                                Pasos para la gestión de documentos mediante comandos en un repositorio GitHub:

-Clonar un repositorio GitHub 
    git clone URL_repositorio_a_clonar
-Comprobar el estado del repositorio en el que estás actualmente
    git status
-Añadir ficheros a un respositorio:
    git add new_file.txt
    //el siguiente añade todos los ficheros
    git add .
-Commit de los archivos añadidos
    //campo '-m' para añadir mensaje en la misma línea
    git commit -m "mi primer commit"
-Actualizar desde local los cambios a repositorio GitHub:
    git push
-Descargar a local los cambios a repositorio GitHub:
    git pull
-Para volver atrás tras hacer un commit
    git revert (HEAD)
-Lista de los commits realizados (de arriba a abajo de más reciente a menos reciente)
    git log --oneline
-Volver a la rama (main)
    git checkout (main-->se podría poner cualquier otra rama... )
-Volver atrás sin que nadie se entere de tu error
    git reset --hard el_hash_anotado
-Crear una rama nueva y saltar a ella
    git branch -b nombre_rama
-Mostrar las ramas que hay en el repositorio
    git branch
-Mezclar los cambio de una rama (prueba) con el main(rama en la que nos encontramos actualmente)
    git merge prueba
-Borrar una rama (a la que nunca queremos volver)
    git branch -D prueba

