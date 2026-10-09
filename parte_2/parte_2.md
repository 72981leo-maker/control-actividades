1.FLUJO COLABORATIVO: Ordena y explica los siguientes elementos: Push, Fork, Pull Request, Clone, Merge, Commit, Review, Branch y Modificar archivos. Agrega cualquier operación que consideres necesaria.
Push: Subes tus commits locales a GitHub.
Fork: Copia un repositorio ajeno (Compañero,maestro,etc.) de GitHub a tu cuenta personal.
Pull Request: Solicitas formalmente integrar tus cambios a la rama principal del proyecto ya sea main o master.
Clone: Descarga el proyecto de GitHub a tu computadora.
Merge: Une tus cambios aprobados a la rama principal (main)
Commit: Guarda instanteas de tus cambios locales con un mensaje explicativo del cambio que se hizo.
Review: Otros miembros del equipo examinan tu código, comentan o lo aprueban.
Branch: Crea una rama de trabajo independiente para no alterar el código principal.
Modificar archivos: Escribes y editas o borras código en tu editor (VS Code).

2. Fork y Clone
Analiza la afirmación: “Clone crea una copia del proyecto dentro de mi cuenta de GitHub”. Indica si es correcta
y explica la diferencia entre Fork y Clone. R= Falso,no copia nada a tu cuenta de GitHub solo descarga el proyecto a tu computadora.

3. Pull Request
Supón que realizaste Fork, Clone, Branch, Modificar, Commit y Push. Responde: ¿los cambios ya forman parte
del repositorio original? ¿Qué debe ocurrir para incorporarlos? R= No,los cambios NO forman parte del repositorio original.
Crear un Pull Request: Abres una solicitud desde tu GitHub pidiéndole al dueño del repositorio original que revise e integre tus cambios.
Review: El dueño o el equipo del proyecto examina tu código y lo aprueba.
Merge: El dueño realiza el Merge para unir tu trabajo a la rama principal del repositorio original.
Universidad de León Ing. Alejandro Montes

4. Request Changes
El propietario revisa tu Pull Request y selecciona Request Changes. Explica qué debes hacer, si necesitas crear
otro Pull Request y qué ocurre cuando realizas nuevamente push.
Debes corregir tu código en tu computadora tomando en cuenta las observaciones del propietario:
-Modificas los archivos en tu editor (VS Code).
-Haces un nuevo git commit con las correcciones.
-Haces git push a tu rama.

5. Merge y repositorio local
Un Pull Request fue aceptado y se realizó Merge en GitHub. Sin embargo, el repositorio local del propietario no
contiene los cambios. Explica por qué sucede y qué operación debe realizarse.
-Al hacer el Merge en la plataforma de GitHub, la rama principal en la nube se actualizó, pero los archivos en el disco duro del propietario siguen en la versión antigua porque la computadora no se sincroniza automáticamente en segundo plano.
-git checkout main y despues un -git pull origin main.

6. Sync Fork
Tu Fork fue creado varios días atrás y el repositorio original recibió nuevos commits. Explica qué herramienta
utilizarías, qué repositorio se actualiza y qué diferencia existe entre Sync Fork y git pull.
Registra este cambio en un cuarto commit con un mensaje descriptivo y súbelo a github.
-Herramienta a utilizar: El botón Sync Fork directamente en la interfaz web de GitHub (en la página principal de tu Fork).Repositorio que se actualiza: Se actualiza tu Fork remoto (tu copia del repositorio en GitHub), poniéndolo al día con el repositorio original (upstream).Diferencia entre Sync Fork y git pull:Sync Fork: Sincroniza dos repositorios remotos en la nube (Repositorio Original en GitHub - Tu Fork en GitHub). git pull: Sincroniza un repositorio remoto con tu máquina local (Tu Fork en GitHub - Tu computadora).