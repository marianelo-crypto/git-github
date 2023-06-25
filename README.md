# git-github
𝙿𝚛𝚒𝚖𝚎𝚛𝚊 𝚙𝚛á𝚌𝚝𝚒𝚌𝚊 𝚍𝚎 𝚖𝚒 𝙱𝚘𝚘𝚝𝚌𝚊𝚖𝚙 𝚍𝚎 𝙳𝚎𝚜𝚊𝚛𝚛𝚘𝚕𝚕𝚘 𝚆𝚎𝚋 𝚎𝚗 𝙺𝚎𝚎𝚙𝚌𝚘𝚍𝚒𝚗𝚐.

**Ejercicio 1**

Se deberá crear un repositorio y realizar una serie de operaciones desde la consola de comandos sobre el mismo para posteriormente subir el repositorio a Github.

Se deberá entregar a través del formulario de prácticas indicando la URL del repositorio. En el repositorio, deberá existir un archivo readme.md con las respuestas a las siguientes preguntas:

1. ¿Qué comando utilizaste en el paso 11? ¿Por qué?

   Use el comando **git reset --hard HEAD~1** porque devuelve el ultimo commit y todos los cambios. De modo que, en nuestro caso, el HEAD se encuentra en el commit inicial.

2. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

   Use el comando **git reflog** para ubicar el commit que queria rehacer y **git reset --hard <id commit>** para rehacer el commit y todos los cambios.

3. El merge del paso 13, ¿Causó algún conﬂicto? ¿Por qué?

   No hay conflicto porque el commit de la rama styled es hijo directo del último commit de la rama main. De modo que ya contiene los cambios de ese commit.

4. El merge del paso 19, ¿Causó algún conﬂicto? ¿Por qué?

   Sí, causo un conflicto. Debido a que, se han realizado cambios en casi todas las líneas de ambos archivos, en styled usando estilos markdown y en htmlify usando estilos HTML. 

5. El merge del paso 21, ¿Causó algún conﬂicto? ¿Por qué?

   No, no ha habido ningún conflicto. Ha sido un merge Fast Forward.  De modo que, al encontrarse el puntero en la rama main, en el commit inicial, para absorber los cambios de la rama styled, sólo se ha movido el puntero hasta el commit final de styled.

6. ¿Qué comando o comandos utilizaste en el paso 25?

   Use **git log --graph**.

7. El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

   Sí, podría serlo porque bastaría con mover el puntero al último commit de title.

8. ¿Qué comando o comandos utilizaste en el paso 27?

   Use el comando **git reset HEAD~1**.

9. ¿Qué comando o comandos utilizaste en el paso 28?

   Use el comando **git restore git-nuestro.md**.

10. ¿Qué comando o comandos utilizaste en el paso 29?

    Use el comando **git branch -D title**.

11. ¿Qué comando o comandos utilizaste en el paso 30?

    Use el comando **git checkout <id commit>**, **git branch title** y **git checkout main** y repetí el paso 26 donde usé el comando **git merge --no -ff title**.

13. ¿Qué comando o comandos usaste en el paso 32?

    Use **git reflog** y **git checkout<id commit INICIAL>**.

15. ¿Qué comando o comandos usaste en el punto 33?

    Use **git reflog** y **git checkout<id commit FINAL>**.

    
