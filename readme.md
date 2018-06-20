- ** ¿Qué comando utilizaste en el paso 11? ¿Por qué?**

$ git reset --hard Head\~1
si no utilizamos el hard, se mantiene lo que hacía en el working copy.

- **¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

A través del git reflog, podemos volver a encontrar el commit que hemos deshecho. Una vez descubierto el commit, mediante su identificador volvemos al commit: git reset --hard 6f1c577

- **El merge del paso 13, ¿Causó algún conﬂicto? ¿Por qué?**

desde la rama styled las uno mediante: git merge master

- **El merge del paso 19, ¿Causó algún conﬂicto? ¿Por qué?**

Al hacer el git merge me salta conflicto: Auto-merging git-nuestro.md
CONFLICT (content): Merge conflict in git-nuestro.md
Automatic merge failed; fix conflicts and then commit the result.

Ya que no coinciden las versiones del documento en ambas versiones

- ** El merge del paso 21, ¿Causó algún conﬂicto? ¿Por qué?**

Causa conflicto: Auto-merging git-nuestro.md
CONFLICT (content): Merge conflict in git-nuestro.md
Automatic merge failed; fix conflicts and then commit the result.

Corrijo el error actualizando el archivo.

- ** ¿Qué comando o comandos utilizaste en el paso 25?**

git log --graph --decorate

- ** El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**

git merge --no-ff title
Sí porque lo único que se ha hecho es añadir el título al texto de master.

- ** ¿Qué comando o comandos utilizaste en el paso 27?**

git reset HEAD\~1

- ** ¿Qué comando o comandos utilizaste en el paso 28?**

git checkout git-nuestro.md

- ** ¿Qué comando o comandos utilizaste en el paso 29?**

git branch -D title

- **¿Qué comando o comandos utilizaste en el paso 30?**

git checkout 8d233a0

- ** ¿Qué comando o comandos usaste en el paso 32?**

git reset e8385ce

- ** ¿Qué comando o comandos usaste en el punto 33?**

git reset 3c52ada