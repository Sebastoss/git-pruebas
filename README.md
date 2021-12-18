## Repositorio de pruebas
Creé este repositorio para hacer pruebas y de guía rápida para comandos git.

## Installation

- Comandos útiles

pwd // te indica en que ruta estás actualmente

mkdir nombre-del-directorio // crea una carpeta

git config --list // indica cómo está configurado git (user, mail, etc)

git config user.name y git config user.email // devuelve el nombre de usuario y el email asociado.

git init // crea un repositorio en la carpeta donde estás ubicado

git status // muestra si hay archivos sin trackear, modificados, en que branch (rama) estas ubicado, etc.

git log --oneline // muestra los commits del repositorio

git log -S linea-de-codigo // te muestra los commits donde fue insertada la linea de codigo especificada.

git log --graph --decorate --all --oneline // te muestra los commits de forma mas detallada con ramas incluidas.

git add nombre-archivo.txt // añade el archivo que no está trackeado o ha sido modificado a la zona de stage.

git add -i // abre un panel con 8 opciones interactivas, status, update, revert, add untracked, patch, diff, quit y help.

git commit -m "mensaje" // crea un commit, sirve para dejar mensajes de los cambios que se están enviando al repositorio.

git commit -a -m "mensaje" // añade a la zona de stage todo lo que está pendiente y hace un commit.

git commit --amend // edita el último mensaje de commit (esto cambia el código del commit).

git remote add origin https://nombreusuario:token@github.com/usuario-git/nombre-repo/ // crea la conexion con autentificacion de token y usuario al repo remoto.

git remote remove origin // borra la configuracion remota de git. No afecta al repo remoto

git push origin master // pushea el repositorio de la rama master (si es que indicas eso) al repo remoto.

git remote -v // muestra un listado con la conexion al repo remoto, tanto (fetch) como (push).

git fetch origin // descarga los cambios que encuentre en remoto aunque no los aplica

git pull // en caso de que haya cambios en remoto, haciendo pull se descargan al repo local

git branch nombre-rama // crea una nueva rama para trabajar, se estila  dev, testing, feature, etc.

git merge nombre-rama // fusiona la rama donde estas parado con la rama que especificas.


git revert hashcommit // revierte los cambios hechos en ese commit, sin embargo no borra el commit original, y agrega un commit al final con los cambios deshechos.

git blame -L 10,20 archivo.txt // blame busca entre las lineas de codigo especificadas ej, 10 a 20 del archivo en cuestion. Sirve para traer la informacion del commit, nombre del autor, fecha y hora. Es un comando útil para buscar el origen de los bugs ya identificados en un archivo.


git grep linea-de-codigo // grep busca en todos los archivos si hay una linea de codigo igual a lo que especificaste. Te mostrará el archivo que lo contiene y el fragmento de codigo.

git grep -n linea-de-codigo // te mostrará el nombre del archivo que la contiene y también en qué número de línea está, ejemplo: index.html:17 codigo.

git grep -c linea-de-codigo // te enseñará cuántas veces aparece la línea buscada en el archivo. Es un contador


## Usage



## Contributing
....

## License
[MIT](https://choosealicense.com/licenses/mit/)
