# PracticaGit - Respuestas

--

**1. ¿Qué comando utilizaste en el paso 11? ¿Por qué?**

`git reset --hard HEAD~1` 


Con 'git reset HEAD~1' se deshace el commit anterior, y el Stating Area queda vacio, pero el commit queda en el working copy.

Para deshacer el ultimo commit perdiendo los cambios realizado en el working copy utilizaremos: 
'git reset --hard HEAD~1'

--
**2. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

`git reset --hard 3c128a3` 

Para conseguir rehacer el ultimo commit he puesto 'git reflog' donde me aparece el historial de los commits realizados y he copiado el identificador 3c128a3 "Modifico el archivo don-quijote".

'git reset --hard 3c128a3' rehace el ultimo commit.

--
**3. El merge del paso 13, ¿Causó algun conflicto? ¿Por qué?**

`git merge master` 

Para que 'styled' absorba a 'master' vemos en que rama estamos 'git branch'. Vamos a la rama styled con 'git checkout styled'. y hacemos un merge con la rama 'master', con 'git merge master' 

No causó ningún conflicto.
--

**4. El merge del paso 19, ¿Causo algún conlicto? ¿Por qué?**

`git merge htmlify` 

Para que 'styled' absorba a 'htmlify' vemos en que rama estamos 'git branch'. Vamos a la rama styled con 'git checkout styled'. y hacemos un merge con la rama 'htmlify', con 'git merge htmlify'.

Al hacer un merge me crea conflictos. He puesto 'git merge --abort'
--
**5. El merge del paso 21, ¿Causo algún conflicto? ¿Por qué?**

`git merge styled`

El merge causó un fast-forward?? 

--

**6.¿Qué comando o comandos utilizaste en el paso 25?**

`git graph`

--
 
**7. El merge del paso 26, ¿Podría ser un fast forward? ¿Por qué?**

``

--
**8. ¿Qué comando  comandos utilizaste en el paso 27?**

``

--
**9. ¿Qué comando  comandos utilizaste en el paso 28?**

``

--

**10. ¿Qué comando  comandos utilizaste en el paso 29?**

``

--


**11. ¿Qué comando  comandos utilizaste en el paso 30?**

``

--
**12. ¿Qué comando  comandos utilizaste en el paso 32?**

``

--

**13. ¿Qué comando  comandos utilizaste en el punto 33?**

``

--