# Tarefa Terminal Básico

- Pon aquí que comando usarías para crear el repositorio en local: 

`git init`

- Queremos guardar lo que llevamos de proyecto (el fichero principal.md) en la base de datos de Git que tenemos en local ¿Qué comandos podemos ejecutar para hacer esto?

`git add .`

`git commit -m "commit inicial"`

- Antes de subir a staging los cambios queremos ver en que estado están los ficheros, para ello ejecutamos el comando:

`git status`

- ¡Anda! Queremos hacer commit del fichero detalle.md pero no queremos que se suban los ficheros con extension .bak, así que decidimos añadir una entrada al .gitignore ¿Qué contenido tendríamos que añadir? Indica aquí tu .gitignore

`*.bak`

- Ahora que lo tenemos vamos a meter los cambios en la base de datos de git (el fichero detalle.md), ¿Que comandos o comando te harían falta?

`git commit -am "segundo commit"`

- Crea un repositorio público en tu cuenta de Github, pon aquí el enlace al mismo:

	[O meu repositorio de terminal básico](https://github.com/odocente/terminal-basico)

- Enlace tu local a ese servidor, pon aquí el comando: 

`git remote add origin git@github.com:odocente/terminal-basico.git`

- Sube el contenido al servidor, pon aquí el comando:

`git push -u origin main`
