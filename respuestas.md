Alumno: Antonio

## ¿Qué es un sistema de control de versiones?
Es una herramienta que nos deja guardar y gestionar los cambios que se hacen en los archivos de un proyecto. Sirve para ver qué se modificó, cuando y quién lo hizo.

## ¿Cuál es la diferencia entre Git y GitHub?
Git es el sistema de control de versiones que se usa en local para llevar los cambios del proyecto. GitHub es una plataforma online donde se guardan repositorios Git.

## ¿Cómo creo una rama en Git?
Usando el comando `git checkout -b nombre_de_la_rama`

## ¿Cómo clono un repositorio?
Con el comando `git clone url_del_repositorio`

## ¿Cómo puedo bajar los últimos cambios de un repositorio?
Usando `git pull origin nombre_de_la_rama`

## ¿Cómo puedo generar un tag?
Con el comando `git tag nombre_del_tag` 

Para subirlo a GitHub se usa: 
`git push origin`

## ¿Cómo hago una mezcla de ramas?
Con el comando `git merge nombre_de_la_rama` 
Primero te aseguras de estar en la rama donde quieres hacer la mezcla y luego haces: 
`git merge rama`

## ¿Cómo puedo moverme a un commit específico?
Primero localizas el ID del commit con `git log`, luego haces: 
`git checkout ID_del_commit` 

## ¿Cómo puedo borrar una rama?
Si es una rama local: 
`git branch -d nombre_de_la_rama` 
Si es una rama remota: 
`git push origin --delete nombre_de_la_rama`

## ¿Cómo puedo borrar un tag?
Para borrar un tag local: 
`git tag -d nombre_del_tag` 
Para borrarlo también en GitHub: 
`git push origin --delete nombre_del_tag`

## ¿Cómo puedo ver los cambios que están por enviarse al repositorio?
Con el comando `git status`

## ¿Para qué sirve el comando git remote -v?
Muestra las direcciones URL asociadas al repositorio remoto . Sirve para ver a qué repositorio estas conectado y desde dónde se hará el push o pull.

## ¿Cómo le digo a Git cuál es mi nombre y correo?
Con estos comandos:
git config --global user.name "Antonio"
git config --global user.email "antonio@email.com"
