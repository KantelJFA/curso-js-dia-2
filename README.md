# Proyecto del día 2.
## Preguntas Docker.
### 1 ¿Qué ha pasado al ejecutar hello-horld? ¿Qué mensajes ha mostrado?
Que ha comprobado si existia la imagen hello de podman, la descarga si no existe, y ha creado un contenedor a base de ella. Tras eso, ha ejecutado el contenedor, el cual ha impreso un hola mundo con arte ascii (mostrado abajo) y unos cuantos enlaces.
```
         .--"--.           
       / -     - \         
      / (O)   (O) \        
   ~~~| -=(,Y,)=- |         
    .---. /`  \   |~~      
 ~/  o  o \~~~~.----. ~~   
  | =(X)= |~  / (O (O) \   
   ~~~~~~~  ~| =(Y_)=-  |   
  ~~~~    ~~~|   U      |~~
``` 
### 2 ¿Qué diferencia hay entre una imagen y un contenedor?
Una images es un modelo a partir del que se crean instancias de codigo ejecutable, y los contenedores son dichas instancias.
### 3 ¿Docker ha instalado Apache en tu sistema o lo ha ejecutado de forma aislada?
Lo ha ejecutado de forma aislada.
### 4 ¿Qué significa -p 8080:80? ¿Por qué tiene dos números?
Es una instrucción que le indica a docker que mapee el puerto 8080 de la maquina local al puerto 80 de internet.
### 5 ¿Qué pasaría si modificas el index.html mientras el contenedor está corriendo?
Que el contenedor muestra la versión actualizada.
## Preguntas Git y GitHub.
### 1 ¿Qué es un repositorio? ¿Para qué sirve?
Es un lugar donde se guardan los registros de cambios en un archivo o conjunto de archivos.<br>Sirve para facilitar el desarrollo de un proyecto de sofware, a todos los niveles.
### 2 ¿Qué es un commit? ¿Por qué son importantes los mensajes de commit?
Es un registro de los cambios realizados.<br>Porque es la única manera de saber qué ha cambiado sin mirar el codigo.
### 3 ¿Qué diferencia hay entre Git y GitHub?
Git es el sistema de control de versiones, y GitHub es una plataforma online que aloja repositorios remotos de Git.
### 4 ¿Qué hace el comando git push? ¿Y git pull?
Git push sube los cambios a un repositorio remoto.<br>Git pull trae los cambios de un repositorio remoto a un repositorio local.