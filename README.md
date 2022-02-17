# handbook
***
## Tarea 4 de Entornos de desarrollo
***
### Pasos del proceso de la tarea

- Craer un nuevo repositorio con un archivo README.md

![create repository](https://github.com/santygn/handbook/blob/3d1138035bde2080ff21bcc1e202dca6ab98966f/multimedia/1.png)

- Copiar el link del repositorio para clonarlo en git

![clone](https://github.com/santygn/handbook/blob/3d1138035bde2080ff21bcc1e202dca6ab98966f/multimedia/2.png)

- Con el comando `git clone` clonamos el repositorio que acabamos de crear

![clone](https://github.com/santygn/handbook/blob/3d1138035bde2080ff21bcc1e202dca6ab98966f/multimedia/3.png)

- En git usamos el comando `cd handbook` para movernos a nuestro repositorio

![cd](https://github.com/santygn/handbook/blob/3d1138035bde2080ff21bcc1e202dca6ab98966f/multimedia/4.png)

- Creamos una rama con el comando `git branch` y nos movemos a ella con el comando `checkout`

![create branch](https://github.com/santygn/handbook/blob/3d1138035bde2080ff21bcc1e202dca6ab98966f/multimedia/5.png)

![use branch](https://github.com/santygn/handbook/blob/3d1138035bde2080ff21bcc1e202dca6ab98966f/multimedia/6.png)

- Creamos los archivos *readme1.md* y *readme2.md* y después los añadimos a la rama actual con el comando `git add`

![add files](https://github.com/santygn/handbook/blob/3d1138035bde2080ff21bcc1e202dca6ab98966f/multimedia/7.png)

- Hacemos commit de los cambios realizados con el comando `git commit -m "snapshot"`

![commit](https://github.com/santygn/handbook/blob/3d1138035bde2080ff21bcc1e202dca6ab98966f/multimedia/8.png)

- Para acabar con este proceso, hacemos push del contenido de la rama con el comando `git push --set-upstream origin new-branch`

![push](https://github.com/santygn/handbook/blob/3d1138035bde2080ff21bcc1e202dca6ab98966f/multimedia/9.png)
***
### Segunda parte de la tarea
- Creamos un nuevo repositorio como hicimos previamente pero esta vez sin ningún archivo adjunto
- Una vez creado el repositorio, en git, lo iniciamos con el comando `git init`
- Con el comando `cd` nos movemos a dicho repositorio
- Creamos un archivo README.md con el comando `touch` y lo añadimos con el comando `git add`
- Hacemos commit de los cambios realizados con el comandon `commit -m "add README to initial commit"`
- Añadimos un origen con el link del repositorio que tenemos en GitHub
- Para acabar con esta parte del proceso hacemos push con el comando `git push --set-upstream origin main`

![parte 2](https://github.com/santygn/handbook/blob/3d1138035bde2080ff21bcc1e202dca6ab98966f/multimedia/10.png)
***
### Tercera parte de la tarea
- Usamos el primer repositorio, creado en la parte 1 de la tarea y nos movemos a él con el comando `cd`
- Hacemos un pull con el comando `git pull`
- Nos dirijimos a la rama que creamos en este repositorio con el comando `git checkout new-branch`
- Creamos el archivo *archivo1.md* con el comando `touch archivo1.md` y lo añadimos a la rama con el comando `git add archivo1.md`
- Guardamos los cambios con un commit usando el comando `git commit -m "edit archivo1"`
- Finalmente hacemos un push con el comando `git push`

![parte 3](https://github.com/santygn/handbook/blob/3d1138035bde2080ff21bcc1e202dca6ab98966f/multimedia/11.png)
