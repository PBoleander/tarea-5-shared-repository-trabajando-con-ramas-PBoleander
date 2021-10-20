[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-f059dc9a6f8d3a56e377f745f24479a46679e63a5d9fe6f495e02850cd0d8118.svg)](https://classroom.github.com/online_ide?assignment_repo_id=6053855&assignment_repo_type=AssignmentRepo)
# Tarea 5. Shared repository. Trabajando con Ramas

## Pascual Barrer Ferrer

En esta tarea vamos a trabajar en equipo. Uno de nosotros ha creado el repositorio en GitHub y nos ha invitado como colaboradores para que podamos contribuir en él.

Lo primero que debemos hacer es clonar el repositorio en una carpeta de nuestro ordenador para poder trabajar en local. Para hacerlo basta con hacer `git clone <dirección del repositorio>`.

![](Capturas/01.png)

Una vez finalizada la clonación, nos movemos a la carpeta recién creada por `git` en donde se encuentran todos los cambios (si hubiera) realizados hasta ahora en el repositorio remoto.

Para poder trabajar sin afectar al resto de compañeros es muy importante hacerlo desde nuestra propia rama. Allí podremos realizar todos los cambios que deseemos sin tocar para nada la rama `main`. Para crearnos una rama nueva lo hacemos mediante `git branch <nombre de la rama>` y nos posicionamos dentro mediante un `git checkout <nombre de la rama>`.

Una vez localizados en nuestra nueva rama empezamos a realizar los cambios que creamos oportunos. En nuestro caso, añadimos diversos programas en Python que tenemos en el ordenador. Para guardar los cambios en `git`, como siempre, hacemos un `add` y, luego, un `commit`.

![](Capturas/02.png)

Repetimos el proceso para añadir más cambios.

![](Capturas/03.png)

![](Capturas/04.png)

![](Capturas/05.png)

Al haber acabado nuestro trabajo podemos hacer un `push` a nuestra rama en remoto para, así, no tocar la rama `main`.

![](Capturas/06.png)

Si nos dirigimos a GitHub, donde se encuentra nuestro repositorio remoto, vemos que la rama que teníamos en local ahora se encuentra en remoto también.

![](Capturas/07.png)

Si nos movemos a la pestaña de *Pull requests* nos aparecerá un botón para crear un *New pull request*. Si le clicamos...

![](Capturas/08.png)

... nos aparece una nueva ventana donde nos da la opción de comparar dos ramas. Nosotros elegiremos como base la `main` y la compararemos con la nuestra (`pascual-branch`).

![](Capturas/09.png)

Una vez hecho esto GitHub se encarga de mirar si ambas ramas se pueden unir o si, por el contrario, existen conflictos entre ellas. Como vemos justo al lado de los desplegables para seleccionar ramas, nos ha aparecido un *check* en verde junto al texto *Able to merge* lo que significa que ambas ramas se pueden fusionar sin ningún problema. Pulsamos el botón verde *Create pull request* para crearlo y, así, el mantenedor del código eche un vistazo para saber si incluye los cambios en producción o, por el contrario, los rechaza o pide que se hagan algunos cambios.

![](Capturas/10.png)

En la siguiente pantalla que nos sale, nos da la opción (muy recomendable) de añadir un comentario para explicar qué hemos cambiado, por qué, etc. Cuando hemos acabado clicamos en *Create pull request* y listo.

![](Capturas/11.png)

Ahora nuestros cambios están incluidos en un *pull request* para que el encargado de revisar los cambios les dé el visto bueno o pida algunos cambios para mejorarlos.

![](Capturas/12.png)
