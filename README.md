-  **¿Qué comando utilizaste en el paso 11? ¿Por qué?** 

He utilizado git reset --hard HEAD~1 porque se utiliza para deshacer el último commit en Git y descartar todos los cambios realizados en el working copy. 

-  **¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

Aquí utilicé “git reflog”  para ver los movimientos que tenía hasta el momento, copié el identificador del movimiento al que quería desplazarme y lo ejecuté con un “git reset –hard” para volver al estado anterior tanto en el working copy como del head.


-  **El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**

No me causó ningún conflicto porque el merge es un fast forward.


-  **El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?** 

Si me causo conflicto, es un merge no fast forward, se encuentra cambios en las mismas líneas en el archivo git-nuestro.

-  **El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**

No me crea conflicto porque hace un merge Fast-forward


-  **¿Qué comando o comandos utilizaste en el paso 25?**
git log –graph

-  **El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?** 
No, porque la rama title se encuentra en una bifurcación diferente.

- **¿Qué comando o comandos utilizaste en el paso 27?**
Un git reset –hard HEAD~1

-**¿Qué comando o comandos utilizaste en el paso 28?** 
Un git reflog y con el identificador correcto hago un git checkout 

-  **¿Qué comando o comandos utilizaste en el paso 29?**

Primero me cambio de rama a la main por ejemplo con git checkout y desde ahí ejecuto git branch -D title para eliminar esa rama.

-  **¿Qué comando o comandos utilizaste en el paso 30?** 	
He utilizado git log y copio el identificador del commit que quiero rehacer. Con git checkout recupero ese merge.

-  **¿Qué comando o comandos usaste en el paso 32?**
He utilizado el git log listo todos los commit copio el primero y con el git checkout desplazo a HEAD al primer commit.

-  **¿Qué comando o comandos usaste en el punto 33?**
He utilizado git reflog, busco el commit correspondiente y con el git checkout me desplazo hasta allí.
