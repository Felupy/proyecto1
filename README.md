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


# Operaciones GIT
## Información del estado del proyecto
git status

## Quitar un fichero del área de STAGING
git rm --cached <nombre_fichero>

## ¡¡¡OJO!!! Borra el fichero.
git rm <nombre_fichero>
Solo se elimina del Workspace y le dice al STAGING que en el próximo paquete de cambios se elimine el fichero. 
Pero no se borra el fichero del REPO.

## Mandar los cambios que hay apuntados en el área de STAGING al REPO
git commit -m 'mensaje'

## Configurar parámetros de Git
git config --global user.email you@example.com
La etiqueta "--global" configura los valores por defecto para Git para todos los proyectos. Si la quitamos, solo se configura para el proyecto actual.

## Arreglar un commit
git commit --amend [-m "MENSAJE"]

## Listar ficheros en el git
git ls-files

## Staging+Commit directo de los cambios de los ficheros que YA se estan controlando (-a)
git commit -am 'Superheroes DC'


