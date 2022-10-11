# **Git Cheat-Sheet**

## Indice
    1.¿Qué es Git?
    2.Comandos más usados
      -El Guardando cambios
      -Habilitación de la colaboración
    3.Glosario de términos
### ¿Qué es Git?

![](git.jpeg)

    Git es un software de control de versiones diseñado por Linus Torvalds. Software de código abierto Seguimiento de cambios en cualquier conjunto de archivos, generalmente utilizado para coordinar el trabajo entre programadores que desarrollan código fuente de forma colaborativa durante el desarrollo del software.
de JavaScript de un subconjunto de Git.

## **Comandos mas usados**

[Descarga git](https://git-scm.com)

### El Guardando cambios
Los cambios en el repositorio de Git se realizan mediante los comandos git addy . git commitEl git addcomando agrega archivos al área de preparación, mientras que el git commitcomando aplica los cambios preparados al repositorio.

El git addcomando utiliza la siguiente sintaxis:

    git add [file/directory name]

### Habilitación de la colaboración
Git te permite copiar y compartir repositorios con otros desarrolladores usando los comandos *git pushy* *.git pull*

El git pushcomando le permite compartir todas las confirmaciones y archivos en el repositorio actual con uno o más repositorios remotos. El git pushcomando utiliza la siguiente sintaxis:

    git push [remote repository] [branch name]

**Dónde:**

*[remote repository]:* el nombre del repositorio remoto con el que desea compartir sus confirmaciones y archivos.
*[branch name]:* El nombre de la rama de su repositorio local que desea compartir.
Use el git pullcomando para copiar el contenido de un repositorio remoto y fusionarlo con su copia local: 
   
    git pull [remote repository]
