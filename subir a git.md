## iniciar repsoitorio 
- git init
## ver cambios 
- git status
## añadir archivos a github
- git add 
## añadir todos los archivos a github
- git add -A   
## añadir mensaje 
- git commit -m 
## para ver los commits agregados
- git log 
## para volver a un commit
git checkout <id commit>

## para volver al ultimo commit
- git checkout master

## para borrar el solo commit 
- git reset soft 

## para borrar el commit y el codigo
- git reset hard
## Para subir a github
- git remote add origin url del repsoitorio
## Para probar el repositorio
- git remote -v
## Para eliminar repositorio
- git remote remove origin
## cambiar el repositorio
- git remote set-url origin git@github.com:User/UserRepo.git
## para subir codigo al repositorio
- git fetch origin master
- git push origin master 
