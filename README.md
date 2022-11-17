# Practica1Softca
comandos utilizados
ls, cd, pwd, mkdir, git status, git add, git commit, git push, git config --global

utilice los comandos "mkdir" para crear carpeta privada y el comando 
"touch" para crear todos los ficheros de la practica.

luego los ignore al incluirlos en el archivo .gitignore que hice guarde los cambios he hice un commit, posteriormente los subi al repositorio.

hice la nueva rama utilizando el codigo "git branch" y el codigo "git checkout" para moverme entre las ramas, subi la rama creada al repositorio con el codigo "git push origin v0.2", v0.2 es el nombre de la rama.

fusione la rama v0.2 con la rama main utilizando el comando "git merge v0.2" estando en la rama main. Posteriormente los liste usando el comando "git branch --merged" para las ramas que han sido fusionadas, y para las ramas que no han sido fusionadas utilice el comando "git branch --no-merged".

los tags son creados usando el comando "git tag -a" y el nombre del tag.

para borrar la rama crada v0.2 utilice el comando "git branch -d v0.2" y la rama v0.2 fue borrada.

y por ultimo para listar los tag con sus respectivos commits use el comando "git show-ref --tags".