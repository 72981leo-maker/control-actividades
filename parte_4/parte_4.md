4. CONCEPTO

1.Diferencia entre Git y GitHub:
Git:Es el sistema de control de versiones que se ejecuta en tu computadora local para rastrear cambios en el código.
GitHub:Es un servicio en la nube que aloja repositorios Git para respaldar el código y colaborar en equipo.


2.¿Para qué sirve `.gitignore`?:
Es un archivo de texto que le indica a Git qué archivos o carpetas debe ignorar completamente para que no se rastreen ni se suban al repositorio.


3.¿Por qué `.venv` no debe subirse a GitHub?:
Contiene el entorno virtual de Python con archivos binarios pesados y dependencias específicas de tu sistema operativo. Ocupa espacio innecesario y puede causar fallas en la computadora de otras personas. En su lugar, solo se comparte el archivo `requirements.txt`.


4.¿Para qué sirve `requirements.txt`?:
Es una lista con los nombres y versiones de todas las librerías de Python que necesita el proyecto. Permite que cualquier otro desarrollador las instale fácilmente con `pip install -r requirements.txt`.


5. Diferencia entre Stage, Commit y Push:
Stage (`git add`): Área de preparación donde eliges qué cambios van a entrar en la próxima foto.
Commit (`git commit`):Guarda una foto/punto de control de esos cambios en el historial local de tu computadora.
Push (`git push`):Sube todos los commits guardados localmente hacia el servidor de GitHub.

6.¿Por qué un repositorio puede tener varios commits antes de un push?:
* Porque los commits son locales y no requieren internet. Puedes hacer un commit por cada avance pequeño o función completada en tu computadora, y cuando termines la jornada o el módulo completo, enviar todos los commits juntos a GitHub con un solo `push`.

#### 1. Modifica el archivo

Agrega estas explicaciones a tu archivo `README.md` (o crea un archivo `conceptos.md` en tu proyecto) y guarda los cambios (`Ctrl + S`).

#### 2. Comandos en la terminal (`Ctrl + ~`)

```bash
git status
git add .
git commit -m "Agrega conceptos teoricos de Git y entorno Python"
git push

```