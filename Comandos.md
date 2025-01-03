# Git

## Usuario
git config --global user.name <"usuario">  
git config user.name                            = Ver el usuario  
git config --global user.email <"correo">  
git config user.email                           = Ver correo

## Carpetas
cd <"Nombre de la carpeta">         = Cambiar de directorio  
cd "Nombre de la carpeta"           = Entrar a la carpeta  
mkdir <"Nombre de la carpeta">      = Crear una carpeta  
ls                                  = Mostrar los archivos y/o carpetas  
cd ..                               = Volver a la carpeta anterior  
cd                                  = Empezar desde 0 (Estar en ninguna carpeta)  
rmdir                               = Eliminar

## Truquillos
git --version                       = cuando hay 2 guiones es la palabra completa  
git -am                             =cuando hay 1 guion es la abreviatura

## Comandos
git branch                  (nos dice en que rama estamos trabajando)  
git status                  (nos da información sobre los commits)  
git init                    (crear el repositorio local)  
git add <archivo.archivo>   (agregar cambios de un archivo al repositorio)  
git add .                   (agregar todos los cambios al repositorio)  
git add *.html              (agregar todos los archivos html)  
git add ruta/*.js           (agregar todos los archivos con una ruta)  
git commit                  (es como hacer un screenshot de como está quedando el proyecto)  
git checkout -- .           (regresa el proyecto a como estaba en el ultimo commit)  
git log                     ()

## Repositorio
|   Comando |   Significado |
|-|-|
git init                                        | Crear Repositorio  
git config --global init.defaultBranch main     | Cambiar (master) por main  
git status                                      | Verificar el estado  
git add                                         | Agregar al commit (Pasarlo al area de preparación)  
git commi                                       | Se abre en Vs Code para escribir el commit  
git commit -m "Agregar comentario"              | Crear un commit  
git commit --amend                              | Modificar un commit  
git reset --soft HEAD~1                         | Eliminar commit  
git log                                         | Ver el commit (e historial de commits.IMPORTANTE: estar en la rama que queremos ver sus commits)  
git log --oneline                               | Lo mismo que arriba (git log) pero mas resumido  
git log -p                                      | Mostrar el commit, y que muestre los cambios que se hicieron  
Q                                               | Para salir del modo de commits  
git branch <nombre.de.la.rama>                  | Crear rama  
git branch version-javascript                   | Rama con nombre  
git branch                                      | Ver la rama  
git branch -a                                   | Ver las ramas incluyendo las ramas remotas  
git checkout <nombre.de.la.rama>                | Moverse de rama  
git checkout <id_commit>                        | Moverse de commit  
git branch -b <nombre.de.la.rama>               | Crear e ir a esa rama  
git branch -m <nombre de la rama>               | Editar el nombre de una rama (Estar en la rama que queremos modificar)  
git branch -m <nombre.actual.de.la.rama> <nombre.nuevo.de.la.rama>  | Editar el nombre de una rama (No es necesario estar en la rama que queremos modificar)  
git push origin -d <nombre.de.la.rama>                              | Eliminar rama remota (En GitHub)  
git branch -d <Nombre de la rama>                                   | Eliminar rama (Sirve para ramas locales, de preferencia estar en la rama principal)  
git merge <La rama que queremos fusionar>                           | Fusionar ramas (IMPORTANTE: estar en la rama con que queremos combinar)  
git merge --continue                                                | Continuar con el proceso de fusionar cuando sale un conflicto en merge  

## Asociar editor de texto
git config --global core.editor "code --wait"

## Mandar el repositorio a GitHub
git init  
git add <archivo.archivo> o git add .  
git commit -m <comentario.>  
git branch -M main  
git remote add origin <pegar.el.link.del.repositorio>  
git push -u origin main