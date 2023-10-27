# examenDAM

## 1 Para hacer un fork del repositorio...

Lo primero que hay que hacer es ir a la URL del repositorio que se quiere clonar 
y una vez dentro **hacer clic sobre "FORK"** que se encontrará como *opción* arriba a la derecha.

Al hacer esto le ponemos otro nombre al repositorio clonado, en mi caso `examen_cod_parte2`. 
Ahora desde una terminal hacemos un `git clone URLrepositorioClonado` para tener el repositorio en nuestro PC.

## 2 GIT IGNORE
Para crear un git ignore voy a lanzar el comando `touch .gitignore` seguido de `nano .gitignore`
para ir metiendo la ruta de los archivos que no quiero que se suban al repositorio.

Como hay que añadir un proyecto a mayores de Java hecho de antes, lo lógico es que se suba el compilado ejecutable
y no el código fuente por ejemplo. Yo lo que hago es pegar la ruta de la carpeta del programa en el *.gitignore*
pero dejo fuera el resto para que sí que se suba el ejecutable.

## 3 Cómo crear un ejecutable con IntelliJIDEA
Para crear un ejecutable es necesario ir al IDE y desde allí entrar a **Project Structure** desde donde iremos a
`artifacts > + > nuestro programa > OK`. Una vez hecho esto, se generará una carpeta en *./out* que contendrá
el ejecutable dentro de una carpeta del mismo nombre del proyecto.

Este ejecutable se puede lanzar con el comando `java -jar NombreArchivo.jar`

## 4 Subir el .jar al repositorio remoto

