
- ¿Qué comando utilizaste en el paso 11? ¿Por qué?

He usado git reset —hard HEAD~1, con él deshago el último commit que realicé y
 todo aquello que tenía en el working copy, quedando así como estaba antes 
(con el staging area vacía). 


- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

Con un git reset —hard 52bfccd me voy a la posición donde realicé el commit.


- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué? 

No, es la primera vez que modifico el fichero.


- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué? 

Si hay conflicto, he tocado el mismo archivo en 2 ramas distintas.


- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué? 

No he modificado nada en la rama master, no hay conflicto.


- ¿Qué comando o comandos utilizaste en el paso 25?

git log —graph


- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué? 

Sí, con title voy por delante, no pasaría nada.


- ¿Qué comando o comandos utilizaste en el paso 27?

git reset —HEAD~1 


- ¿Qué comando o comandos utilizaste en el paso 28? 

git checkout — poem.md


- ¿Qué comando o comandos utilizaste en el paso 29? 

git braunch -D title


- ¿Qué comando o comandos utilizaste en el paso 30? 

git reset --hard 17e05bf


- ¿Qué comando o comandos usaste en el paso 32? 

git reset --hard 3a60589


- ¿Qué comando o comandos usaste en el punto 33? 

git reset --hard e0fbd21

