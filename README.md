# Programacion
Aprender desde 0 python
COMANDOS BASICOS 
* git init Oye Git, voy a usar estos documentos contigo ¿vale?
* git add <file> Pasa los docs a staging area 
* git add . Pasa todos los archivos
* git commit Pasa los docs de staging area a repository (Después de esto se te va a abrir el editor de código VIN en donde tendrás que escribir un comentario, si te quieres evitar abrir VIN entonces utiliza los siguientes comandos:)
* git commit -m "comentario" Lo mismo que el commit regular, pero ahora no necesitas entrar a VIN
* git status Ver en que status (wd, sa, r) están los docs
* git push Subir los docs a un server (Github)
* git pull  Traer los docs de un server, traer los cambios de tus compañeros
* git clone Hacerte una copia de lo que está en el server a tu PC
* git checkout -- <file> Para revertir los cambios de los archivos
* git diff <file> Para ver las diferencias hechas en los archivos
* git branch Ver las ramas que hay ("master" es la rama default)
* git branch "nombre" Crear una nueva rama
* git checkout "nombre" Ir a una rama en especifico 

*  git config -- global user.email "email" Para configurar email del usuario
*  git config -- global user.name "nombre" Para configurar nombre del usuario


vin Es el editor de código de git desde la consola, ahí escribes un comentario para la nueva versión que estés versionando (si no te deja escribir presiona a letra i). Cuando termines presiona esc y luego :wq (write & quit)pasa salir.

.gitignore Es un archivo reservado de git que tenemos que crear si queremos decirle a git los archivos que no vamos a utilizar y así decida ignorarlos.
Escribe dentro de el archivo .gitignore los nombres de los archivos que desees ignorar.
Nota: Las carpetas se escriben solas y los archivos con su terminación.
