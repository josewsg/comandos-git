git init

git add .

git commit -m "first commit"

git remote add origin https://github.com/NOMBRE_USUARIO/NOMBRE_PROYECTO.git


# a continuación se utiliza para agregar un nuevo control remoto:

git remote add origin git@github.com:User/UserRepo.git
# a continuación se utiliza para cambiar la url de un repositorio remoto existente:

git remote set-url origin git@github.com:User/UserRepo.git
# a continuación empujará su código a la rama maestra del repositorio remoto definido con originy le -upermitirá apuntar su rama local actual a la rama maestra remota:

git push -u origin master
git push -f origin master

# Comandos para actualizar repositortio
- git init
- git add -A
- git commit -m 'Fix bad repo'
- git push
# En el último comando, es posible que deba establecer la rama.
- git push --all origin master

# revisar enlace https://github.com/volta2016/resumen-estudios-git/blob/master/resumen%20estudio.txt
