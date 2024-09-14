# Practica-GIT

- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
Utilice el git reset --hard HEAD~1 porque elimina el ultimo commit hecho junto con los cambios en el working copy.

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
Para rehacer los cambios realizados, tuve que hacer un git reflog para poder ver todos los commits que se realizaron en mi proyecto git, entonces hice un checkout al commit anterior el cual es un detached HEAD para recuperar los cambios perdidos, luego cambie a la rama styled e hice un merge del commit dentro de styled y recupere los cambios perdidos.

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
El merge del paso13 no causo ningún conflicto, ya que el progreso de la rama styled previamente ya contiene todos los cambios de la rama main y main no sufrió ningún cambio aparte.

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
Si causo conflicto porque existe una version de los datos guardados dentro de la rama styled la cual se quiere combinar con los datos de htmlify, entonces se debe decidir sobre el contenido del archivo git-nuestro donde escogemos la version de styled y realizamos un commit para después realizar el merge donde styled absorbe a htmlify.

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No causo ningún conflicto ya que main no tiene nuevos commits desde la ultima vez que se trabajo en ella, entonces realizo un merge fast-forward y se adelanto el puntero de main hasta los cambios que tiene styled.

- ¿Qué comando o comandos utilizaste en el paso 25?
Utilice el comando git log --graph --oneline --all para realizar el diagrama en la terminal de Git.

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
Si podría ser fast forward porque el progreso de la rama main no tiene ninguna bifurcación diferente al progreso de title, por ende es posible realizar el merge sin la necesidad de agregar un commit ya que solo se adelantaría el puntero de main a donde se encuentra el puntero de title.

- ¿Qué comando o comandos utilizaste en el paso 27?
Utilice el comando git reset --soft HEAD^ para regresar un paso anterior en el grafo de Git manteniendo los cambios del merge No Fast Forward.

- ¿Qué comando o comandos utilizaste en el paso 28?
Utilice el comando git restore --source=HEAD --staged --worktree .

- ¿Qué comando o comandos utilizaste en el paso 29?
Para eliminar la rama utilice el comando git branch -D title

- ¿Qué comando o comandos utilizaste en el paso 30?
Para rehacer el merge, revise el progreso del proyecto con un git reflog, luego hice un git checkout al commit en donde realice el merge, después hice un checkout a la rama main e hice un merge con el commit en donde hice el merge con title

- ¿Qué comando o comandos usaste en el paso 32?
Utilice un git reflog para ver el commit cuando se creo el poema y realice un checkout al commit en donde se realizó eliminando todos los cambios. 

- ¿Qué comando o comandos usaste en el punto 33?
Revise los cambios en un git reflog y luego realice un cambio al git commit para realizar al final un cambio a la rama main en donde tenia los cambios hechos.