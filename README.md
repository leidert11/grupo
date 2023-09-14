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