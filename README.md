# shared-repository

## Tarea 5
## Entornos de desarrollo

# Pasos del proceso
***
## Parte de Santiago
***
- Una vez creado el repositorio hemos de clonarlo en nuestra conosla de git con el comando `git clone`
- Tras clonarlo hemos de movernos a ese directorio con el comando `cd shared-repository`

![git clone](https://github.com/santygn/shared-repository/blob/d7a2a61ef02ff53a4847837481689af0da9682eb/multimedia/clone.png)

- Al ser un proyecto en grupo, hemos de crear una rama para cada uno de los participantes con el comando `git branch santy-branch`
- Nos movemos a la rama que acabamos de crear con el comando `cd santy-branch` 
- En dicha rama hemos de crear el arcchivo CSS para el html con el comando `touch style.css` 
- Una vez creado, lo editamos con el comando `nano style.css`

![nano](https://github.com/santygn/shared-repository/blob/d7a2a61ef02ff53a4847837481689af0da9682eb/multimedia/branch.png)

- Añadimos el CSS al archivo y lo guardamos

![css](https://github.com/santygn/shared-repository/blob/d7a2a61ef02ff53a4847837481689af0da9682eb/multimedia/nano.png)

- Añadimos el archivo con los cambios con el comando `git add style.css`
- Hacemos el commit de nuestras modificaciones con el comando `git commit -m`
- Finalmente hacemos push de nuestro commit con el comando `git push --set-upstream origin santy-branch`

![push](https://github.com/santygn/shared-repository/blob/d7a2a61ef02ff53a4847837481689af0da9682eb/multimedia/final.png)

***

## Parte de Alex
***

- Cuando el repositorio este creado por el miembro que lo creo, tendremos que clonar desde el git bash con el `git clone`
- Despues de clonarlo lo moveremos al directorio que ha creado Santy.
- En esta parte habra que crear la rama que unira al repositorio de Santy con el `git branch`
- Nos movemos a la rama que hemos creado con `cd alex-branch`

![git clone](https://github.com/santygn/shared-repository/blob/2d1410aec444058d90a2b4b9c0fd34b29d1a3960/multimedia/alex.png)

- Cuando tengamos las modificaciones hechas haremos un `git commit -m`
- Y justo despues haremos el push al commit que hemos hecho `git push --set-upstream origin alex-branch`

![git push](https://github.com/santygn/shared-repository/blob/9ef8ddf1f99c5c0ff27c4f6d3c93df0cd88bce38/multimedia/2.1.PNG)

***

## Parte de Marlo
***

- Despues de pedir y que nos cedieran permisos para este proyecto , nos disponemos a clonarlo con el comando `git clone https:...`
![git clone](https://github.com/santygn/shared-repository/blob/4f47773264b7c53be8f5288fa160ce1abdc2994c/multimedia/marlo1.PNG)

- Una vez tenemos el repositorio en nustra máquina, debemos dirigirnos al repositorio con el comando `cd repo_name`
![cd repositorio](https://github.com/santygn/shared-repository/blob/4f47773264b7c53be8f5288fa160ce1abdc2994c/multimedia/marlo2.PNG)

- Creamos la rama que vamos a usar en mi caso `git branch marlo-branch`
![git branch](https://github.com/santygn/shared-repository/blob/4f47773264b7c53be8f5288fa160ce1abdc2994c/multimedia/marlo3.PNG)

- Nos dirigimos a la rama que hemos creado con el comando checkout
![git checkout](https://github.com/santygn/shared-repository/blob/4f47773264b7c53be8f5288fa160ce1abdc2994c/multimedia/marlo4.PNG)

- Para comprobar que la rama se nos ha creado correctamente y comprobamos con el comando `ls` el contenido de la carpeta (coincide con el que hay en la rama main del repositorio que hemos clonado)
![ls](https://github.com/santygn/shared-repository/blob/4f47773264b7c53be8f5288fa160ce1abdc2994c/multimedia/marlo5.PNG)

- Editaremos el archivo proyecto.html para aportar nuestra parte al proyecto con el comando de edicion `nano proyecto.html`
![nano](https://github.com/santygn/shared-repository/blob/4f47773264b7c53be8f5288fa160ce1abdc2994c/multimedia/marlo6.PNG)

- Comprobamos que los cambios se han realizado, con el `git status` (el cual para que nos fuera bien deberia salir el archivo en rojo)
![git status](https://github.com/santygn/shared-repository/blob/4f47773264b7c53be8f5288fa160ce1abdc2994c/multimedia/marlo7PNG.PNG)

- Debremos hacer un `git add proyecto.html`
![git add](https://github.com/santygn/shared-repository/blob/4f47773264b7c53be8f5288fa160ce1abdc2994c/multimedia/marlo8.PNG)

- Hacemos un commit para poder realizar el push `git commit -m "Comentario a añadir"`
![git commit](https://github.com/santygn/shared-repository/blob/4f47773264b7c53be8f5288fa160ce1abdc2994c/multimedia/marlo9.PNG)

- Para finalizar realizamos un `git push --set-upstream origin my-branch` para subir a la plataforma de git nuestros cambios
![git push](https://github.com/santygn/shared-repository/blob/4f47773264b7c53be8f5288fa160ce1abdc2994c/multimedia/marlo10.PNG)


***
## Parte de Adrián
***
-Despues de pedir y que nos cedieran permisos para este proyecto , nos disponemos a clonarlo con el comando `git clone https:...`

- Una vez tenemos el repositorio en nustra máquina, debemos dirugirnos al repositorio con el comando `cd repo_name`

- Creamos la rama que vamos a usar en mi caso `git branch Adrian-branch`

- Nos dirigimos a la rama que hemos creado con el comando checkout

- Para comprobar que la rama se nos ha creado correctamente y comprobamos con el comando `ls` el contenido de la carpeta (coincide con el que hay en la rama main del repositorio que hemos clonado)

- Editaremos el archivo proyecto.html para aportar nuestra parte al proyecto con el comando de edicion `nano proyecto.html`, en mi parte he añadido los parrafos dentro del html.

- Comprobamos que los cambios se han realizado, con el `git status` (el cual para que nos fuera bien deberia salir el archivo en rojo)

- Debremos hacer un `git add proyecto.html`

- Hacemos un commit para poder realizar el push `git commit -m "Comentario a añadir"`

- Para finalizar realizamos un `git push --set-upstream origin my-branch` para subir a la plataforma de git nuestros cambios
