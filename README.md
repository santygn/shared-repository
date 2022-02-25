# shared-repository

## Tarea 4
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
