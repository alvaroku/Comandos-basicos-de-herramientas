#------------------------------
#COMANDOS BÁSICOS DE GIT
#------------------------------
####CONFIGURACIÓN INICIAL
##### usuario
`git config --global user.name "Alvaro Kú"`
##### correo
`git config --global user.email "tucorreo@gmail.com"`

----
####PARA LAS REPOS
##### iniciar repo
`git init`
##### agregar todo
`git add .`
##### agregar archivo especifico
`git add .gitignore`
##### commits
`git commit -m "<mensaje>"`
##### repo remoto, crearlo en [github](http://https://github.com/ "github")->copiar el enlace del apartado code
`git remote add origin <pegar el enlace>`
##### mandar cambios a repo remoto
`git push origin master`
##### traer cambios de remoto a local
`git pull origin master`
##### comandos para ver info
- ###### estado de cambios y commits 
`git status`
- ###### historial de cambios 
`git log`

----
####PARA LAS RAMAS
##### eliminar origin(repo de github)
`git remote rm origin`
##### crear rama y saltar a ella
`git checkout -b <nombrerama>`
##### lo anterior paso a paso
- ###### crear rama
`git branch <nombrerama>`
- ###### saltar a ella
`git checkout <nombrerama>`

----
####PARA REGRESAR A CAMBIOS ANTERIORES
##### volver a un commit y eliminar los cambios siguientes a ese commit
`git reset --hard <id-del-commit>`
##### para lo anterior si al hacer un push se presenta problemas, usar lo siguiente para forzar el reset en el origin
`git push -f origin  <nombrerama>`
##### reparar el último commit
`git commit --amend -m "<nuevomensaje>"`

---
#### Otros
##### para el error unable to access
`git config --global http.sslverify "false"`