# git-practica1


¿Qué comando utilizaste en el paso 11? ¿Por qué?
Utilice git reset --hard HEAD~1 que permite deshacer el último commit perdiendo los cambios locales, si no se quieren perder podemos sustituir --hard por --soft
- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
Puesto que el cambio lo tenemos en el repo hacemos un git pull y volvemos a recibir los datos que están subido en el repositorio.
- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
Un mensaje: merge: master - nada que podamos fusionar. Esto es porque la rama styled ya contiene todo lo que hay en master y no en master no hay ningún cambio que styled  no contenga.
- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
Sí, porque la rama styled tiene cambios y la rama htmlify también.
- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No, porque master no contiene cambios y los que contiene styled no entran en conflicto.
- ¿Qué comando o comandos utilizaste en el paso 25?
git log --graph
- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
Sí porque no afecta al código solo a como se visualizan los cambios.  
- ¿Qué comando o comandos utilizaste en el paso 27?
git reset --soft HEAD~1
- ¿Qué comando o comandos utilizaste en el paso 28?
git reset --hard
- ¿Qué comando o comandos utilizaste en el paso 29?
git branch -d title
- ¿Qué comando o comandos utilizaste en el paso 30?
git reset HEAD
- ¿Qué comando o comandos usaste en el paso 32?
git reset --hard HEAD~1
- ¿Qué comando o comandos usaste en el punto 33?
git reset
