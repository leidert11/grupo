### DOCUMENTACION

## merge con Git

- el git merge es fusionar cambios por ejemplo estar en una rama secundaria hacer un cambio , subirlo , despues estar en la rama principal y hacer un merge con la rama que hizo los cambios

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

## Creación de un Release en GitHub

Un "release" es una versión estable de tu proyecto lista para ser usada por los usuarios. Aquí están los pasos para crear un release:

1. Navega a tu repositorio en GitHub y haz clic en la pestaña "Releases".
2. Haz clic en "Draft a new release".
3. Introduce el número de la versión en "Tag version" y un título para tu release en "Release title".
4. Describe los cambios realizados en esta versión en "Describe this release".
5. Haz clic en "Publish release".

