### DOCUMENTACION

## merge con Git

- el git merge es fusionar cambios por ejemplo estar en una rama secundaria hacer un cambio , subirlo , despues estar en la rama principal y hacer un merge con la rama que hizo los cambios

El comando `merge` de Git se utiliza para combinar dos o más ramas en tu repositorio. Este comando toma el contenido de una rama secundaria y lo integra con la rama actual.

### Código

Aquí tienes los pasos para hacer un merge:

1. Primero, debes asegurarte de estar en la rama donde quieres fusionar la rama secundaria. Puedes usar el comando `git checkout` para cambiar a la rama deseada. Por ejemplo, si quieres fusionar en la rama `main`, debes hacer:


`git checkout main`
Luego, puedes usar el comando git merge para fusionar la rama secundaria en tu rama actual (en este caso, main). Por ejemplo, si quieres fusionar una rama llamada feature, puedes hacer:
`git merge feature`

Esto fusionará la rama feature en la rama main.

Ejemplo
Supongamos que tienes dos ramas: main y feature. Has hecho algunos cambios en la rama feature que ahora quieres fusionar en la rama main. Aquí están los comandos que usarías:


`git checkout main`
`git merge feature`


# datos extras

- para eliminar una rama te debe de poner en dichaa rama y con el siguiente comando se elimina   git branch -d leider

- para cambiar nombre una rama te debe de poner en dichaa rama y con el siguiente comando se cambiara   git branch -m leider

## Cherry-Pick con Git

Cherry-pick permite aplicar cambios de un commit específico a tu rama actual. Aquí están los pasos básicos usando Git Graph y la línea de comandos:

1. En Git Graph, localiza el commit que deseas y copia su hash.
2. En la terminal, asegúrate de estar en la rama donde deseas aplicar el commit con `git branch`.
3. Aplica el commit con `git cherry-pick HASH_DEL_COMMIT`.
4. Si hay conflictos, resuélvelos y luego ejecuta `git cherry-pick --continue`.

## tags en git

es darle un alias a un commit bien puedes darle uun tag al ultimo commit o referirte a uno antiguo con el hash 

- Aplica el commit con `git tag V1.0.0 345a330d67303eca4746d46c8c93689e8a2cf6a1`.

[video de explicacion](https://www.youtube.com/watch?v=5DkX3HFgklM&t=186s)


## Creación de un Release en GitHub

Un "release" es una versión estable de tu proyecto lista para ser usada por los usuarios. Aquí están los pasos para crear un release:

1. Navega a tu repositorio en GitHub y haz clic en la pestaña "Releases".
2. Haz clic en "Draft a new release".
3. Introduce el número de la versión en "Tag version" y un título para tu release en "Release title".
4. Describe los cambios realizados en esta versión en "Describe this release".
5. Haz clic en "Publish release".

[video de explicacion](https://www.youtube.com/watch?v=wwHtJWS1haA)

## pull request en GitHub

Un “Pull Request” en GitHub es una solicitud para que los cambios que has hecho en una rama de tu repositorio sean incorporados (o “fusionados”) en otra rama, generalmente la rama principal o “main”. Aquí te dejo una explicación breve y precisa de cómo hacer un Pull Request

[video de explicacion](https://www.youtube.com/watch?v=Tfxo6P0wZ1s)
