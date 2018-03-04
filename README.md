# Práctica GIT

### González Cagigas, Laura



# PracticaGit - Respuestas

--

**1. ¿Qué comando utilizaste en el paso 11? ¿Por qué?**

`git reset --hard HEAD~1` 

Porque nos pide descartar cambios y este comando reestablece el trabajo al punto en el que se encontraba en ese momento.

--

**2. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

`git reflog`  `git reset --hard HEAD e1386b0`   

Este comando reestablece el trabajo al punto en el que se encontraba en ese momento.

--

**3. El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**

No hay conflicto puesto que la rama htmlify es lineal. Va a tener el mismo acceso a master.

--

**4. El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**

Tampoco ha habido conflicto en el merge fasto-forward.

--

**5. El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**

Se hace sin conflicto alguno, como ocurre con el anterior.

--

**6. ¿Qué comando o comandos utilizaste en el paso 25?**

`git log --graph`

--

**7. El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**

No, puesto que, de serlo, desplazaríamos master al commit de title. Ahí,  title se mantendría en el mismo commit pero, master y head se desplazarían al commit de la unión. Hubiéramos mezclado los commits en una sola rama sin diferenciarlos.
--

**8. ¿Qué comando o comandos utilizaste en el paso 27?**

`git reset HEAD~1`

--

**9. ¿Qué comando o comandos utilizaste en el paso 28?**

`git checkout --don-quijote.md`

--

**10. ¿Qué comando o comandos utilizaste en el paso 29?**

`git branch -D title`

--

**11. ¿Qué comando o comandos utilizaste en el paso 30?**

`git reflog`   `git reset --hard be9a463`

--

**12. ¿Qué comando o comandos usaste en el paso 32?**

`git reflog`   `git reset --hard d0f3af8`

--

**13. ¿Qué comando o comandos usaste en el punto 33?**

`git reflog`   `git reset --hard 3e30e2d`

--

