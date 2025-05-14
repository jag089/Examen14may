# Crear repositorio en GitHub
Aprendemos a crear un repositorio en **GitHub** a través de **Git** (consola de comandos)

## Tutorial
1. Descargar [Git](https://git-scm.com/downloads).
2. Abrirse una cuenta en [GitHub](https://github.com/).
3. En el botón superior identificado con un + ("create new"), creamos un nuevo repositorio. Le damos un nombre y una descripción.
4. En nuestro ordenador, creamos una carpeta donde se alojará el repositorio. Dentro de ella, abrimos consola de comandos de Git.
5. Añadimos los archivos y los directorios del proyecto en la carpeta.
6. Usamos los siguientes comandos:
   
   `git init`
   
   `git remote add origin https://github.com/<usuario>/<repositorio>.git`
   
   `git add .`
   
   `git commit -m "comentario"`
   
   `git push`

> [!IMPORTANT]
> Seguramente el `git push` dará error, por lo tanto, copiamos el comando `git push --set-upstream origin master`
