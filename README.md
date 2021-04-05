# Este es el primer proyecto del curso

## Creacion de repo:
git init

## Añadir un fichero:
git add <nombre_fichero>
git add * (NO añade ficheros ocultos)
git add . (SI añade ficheros ocultos)
Empezar a controlar el fichero. Para ello lo que hace es pasar el fichero al area de STAGING.



# OBJETOS EN GIT
## Workspace
La carpeta en la que tengo mi proyecto.
## Staging
Es un fichero que se guarda dentro de la carpeta .git, que va anotando los cambios que se van a mandar al REPO desde el área de STAGING.
## Repo
La carpeta del .git


## Información del estado del proyecto
git status

## Quitar un fichero del área de STAGING
git rm --cached <nombre_fichero>

## ¡¡¡OJO!!! Borra el fichero.
git rm <nombre_fichero>
Solo se elimina del Workspace y le dice al STAGING que en el próximo paquete de cambios se elimine el fichero. 
Pero no se borra el fichero del REPO.

