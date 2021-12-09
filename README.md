## Repositorio de pruebas
Creé este repositorio para hacer pruebas y de guía rápida para comandos git.

## Installation

- Comandos útiles
pwd // te indica en que ruta estás actualmente

git config --list // indica cómo está configurado git (user, mail, etc)

git config user.name y git config user.email // devuelve el nombre de usuario y el email asociado.

git init // crea un repositorio en la carpeta donde estás ubicado

git status // muestra si hay archivos sin trackear, modificados, en que branch (rama) estas ubicado, etc.

git log --oneline // muestra los commits del repositorio

git add nombre-archivo.txt // añade el archivo que no está trackeado o ha sido modificado a la zona de stage.

git add -i // abre un panel con 8 opciones interactivas, status, update, revert, add untracked, patch, diff, quit y help.

git commit -m "mensaje" // crea un commit, sirve para dejar mensajes de los cambios que se están enviando al repositorio.

git commit -a -m "mensaje" // añade a la zona de stage todo lo que está pendiente y hace un commit.

git commit --amend // edita el último mensaje de commit (esto cambia el código del commit).

git remote add origin https://<nombreusuario>:<token>@github.com/<usuario-git>/<nombre-repo> // crea la conexion con autentificacion de token y usuario al repo remoto.

git remote remove origin // borra la configuracion remota de git. No afecta al repo remoto

git push origin master // pushea el repositorio de la rama master (si es que indicas eso) al repo remoto.

git remote -v // muestra un listado con la conexion al repo remoto, tanto (fetch) como (push).


## Usage



## Contributing
....

## License
[MIT](https://choosealicense.com/licenses/mit/)