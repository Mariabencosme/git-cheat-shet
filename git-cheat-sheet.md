# **Git Cheat-Sheet**

## Indice
    1.¿Qué es Git?
    2.Comandos más usados
      -El Guardando cambios
      -Habilitación de la colaboración
    3.Glosario de términos
### ¿Qué es Git?

![](git.jpeg)

    Git es un software de control de versiones diseñado por Linus Torvalds. Software de código abierto Seguimiento de cambios en cualquier conjunto de archivos, generalmente utilizado para coordinar el trabajo entre programadores que desarrollan código fuente de forma colaborativa durante el desarrollo del software de JavaScript de un subconjunto de Git.

## **Comandos mas usados**


### El Guardando cambios
Los cambios en el repositorio de Git se realizan mediante los comandos git addy . git commitEl git addcomando agrega archivos al área de preparación, mientras que el git commitcomando aplica los cambios preparados al repositorio.

El git addcomando utiliza la siguiente sintaxis:

    git add [file/directory name]

### Habilitación de la colaboración
Git te permite copiar y compartir repositorios con otros desarrolladores usando los comandos *git pushy* *.git pull*

El git pushcomando le permite compartir todas las confirmaciones y archivos en el repositorio actual con uno o más repositorios remotos. El git pushcomando utiliza la siguiente sintaxis:

    git push [remote repository] [branch name]

### **Dónde:**

*[remote repository]:* el nombre del repositorio remoto con el que desea compartir sus confirmaciones y archivos.
*[branch name]:* El nombre de la rama de su repositorio local que desea compartir.
Use el git pullcomando para copiar el contenido de un repositorio remoto y fusionarlo con su copia local: 
   
    git pull [remote repository]

### Glosario de terminos

[Glosario de git](https://deustopweb2018.github.io/glosario.html)

***Repositorio:*** Es una base de datos de contenido digital con un conjunto asociado de métodos de gestión, búsqueda y acceso de datos que permite el acceso independiente de la aplicación al contenido, como una biblioteca digital, pero con la capacidad de almacenar y modificar contenido además a la búsqueda y recuperación.

***CMD*** abrir la consola, cuando estas dentro de console, te dice la versión y los derechos reservados.
***Cls*** para borrar historial del console.


***git commit -a*** "Introduccion a Git agregado"
git brach para crear ramas como la rama master y rama development.

***Rmdir*** para borrar una carpeta.
***Cd.. *** Para dar atrás a una carpeta.

***git lock***esto para ver un tipo de historial que vizualiza quien lo hizo y la fecha.NO puede haber repositorios con el mismo nombre.

***pull***Literalmente, tirar. Se refiere a traer los cambios del servidor remoto y combinarlos con tu copia local. Por ejemplo, si alguien ha editado el archivo remoto en el que ambos estáis trabajando, querrás hacer pull de esos cambios a tu copia local para que esté actualizada.

***branch***
Un branch o, literalmente, rama, es una versión paralela de un repositorio. Está contenido dentro del repositorio, pero no afecta al branch principal o master, permitiéndote trabajar libremente sin estropear la versión “real”. Cuando has terminado de realizar los cambios que querías hacer, puedes hacer merge de tu branch al branch principal para publicar tus cambios.

***merge*** Literalmente, combinar. Hacer merge toma los cambios de un branch (en el mismo repositorio o también desde un fork), y los aplica en otro. Esto a menudo ocurre como un pull request (que se puede entender como una solicitud de hacer merge), o a través de la línea de comandos. Un merge puede realizarse automáticamente a través de un pull request en la interfaz web de GitHub siempre y cuando no haya cambios que generen conflictos, o puede hacerse siempre via línea de comandos.

***remote*** La versión remota es una versión de algo que está alojada en un servidor, muy probablemente GitHub en este contexto. Puede estar conectado a clones locales de forma que los cambios se sincronicen.

***clone*** Un clon es la copia de un repositorio que se aloja en tu ordenador, en lugar de en un servidor en alguna parte, o el acto de realizar esa copia. En tu clone puedes editar los archivos en tu editor preferido y utilizar Git para llevar un registro de esas modificaciones sin necesidad de tener conexión a internet.
