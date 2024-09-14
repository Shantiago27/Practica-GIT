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


- ¿Qué comando o comandos utilizaste en el paso 25?


- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?


- ¿Qué comando o comandos utilizaste en el paso 27?


- ¿Qué comando o comandos utilizaste en el paso 28?


- ¿Qué comando o comandos utilizaste en el paso 29?


- ¿Qué comando o comandos utilizaste en el paso 30?


- ¿Qué comando o comandos usaste en el paso 32?


- ¿Qué comando o comandos usaste en el punto 33?