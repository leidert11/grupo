
# ALGUNOS COMANDOS GIT

A continuación se presentan algunos comandos comunes de Git y sus descripciones:

| Comando | Descripción |
| ------- | ----------- |
| `git rm <nombre archivo>` | Elimina un archivo de la staged area y agrega los cambios para su posterior commit. |
| `git restore --staged <nombre archivo>` | Elimina un cambio que se había añadido a la zona de stage. |
| `git restore <nombre archivo>` | Restaura un archivo que haya sido eliminado del repositorio. |
| `git add <nombre archivo antiguo> <nombre archivo que se le puso>` | Permite manejar cambios cuando se cambia el nombre de un archivo. |
| `git mv <nombre actual> <nombre a considerar>` | Es un atajo para cambiar el nombre de un archivo en Git. |
| `git reset <nombre archivo>` | Saca un archivo del stage area, deshaciendo los cambios. |
| `git reset --soft <nombre archivo>` | Deshace los cambios y saca el archivo del área de preparación. |
| `git status -s` | Muestra el estado de los archivos de manera resumida. |
| `git diff` | Muestra los cambios en un archivo antes de agregarlo al stage. |
| `git diff --staged` | Muestra los cambios en un archivo desde la zona de stage. |
| `git init` | Inicializa un nuevo repositorio Git. |
| `git add <nombre archivo>` | Agrega un archivo al área de preparación. |
| `git push -u origin <rama>` | Envía los cambios al servidor remoto (por ejemplo, en VS Code). |
| `git remote -v` | Muestra los repositorios remotos configurados. |
| `git config --global user.name "<nombre usuario>"` | Configura el nombre de usuario de Git globalmente. |
| `git config --global user.email "<correo usuario>"` | Configura la dirección de correo electrónico global de Git. |
| `git config user.name "<nombre usuario>"` | Configura el nombre de usuario de Git localmente. |
| `git config user.email "<correo usuario>"` | Configura la dirección de correo electrónico de Git localmente. |
| `git rm -r --cached nombre_de_la_carpeta` | Deja de seguir una carpeta en Git sin eliminarla del sistema de archivos local. |
| `rm -rf .git` | Revierte la inicialización de un repositorio Git. |
| `git branch` | Muestra todas las ramas. |
| `git branch <nombre rama nueva>` | Crea una nueva rama. |
| `git branch -d <rama a eliminar>` | Elimina una rama. |
| `git merge <rama a combinar>` | Combina los cambios de una rama en la rama actual. |
| `git branch -m <nombre a elegir>` | Renombra la rama en la que te encuentras. |
| `git switch <rama a cambiar>` | Cambia a una rama específica. |
| `git push origin --delete nombre_antiguo` | Elimina una rama del repositorio remoto. |
| `git push origin nombre_rama` | Agrega una rama a un repositorio remoto. |
| `git clone --branch <NombreRama> --single-branch <Repo>` | Clona una rama específica de un repositorio. |
| `git rebase -i <HEAD~(cambios a asociar)>` | Asocia varios cambios o edita commits de forma masiva. |
| `git log` | Muestra el historial de commits. |
| `git log --oneline` | Muestra el historial de commits en una sola línea. |
| `git checkout -b "nombre rama"` | Crea y cambia a una nueva rama en un solo paso. |


# Comandos Basicos Terminal Linux


A continuación se presentan algunos comandos comunes de terminal y sus descripciones:

| Comando | Descripción |
| ------- | ----------- |
| `ls` | Lista los archivos y directorios en el directorio actual. |
| `cd <nombre archivo>` | Cambia el directorio actual al especificado. |
| `cd ..` | Mueve el directorio actual un nivel hacia atrás (al directorio padre). |
| `rm <nombre archivo>` | Elimina un archivo. |
| `mv <nombre actual> <nombre a considerar>` | Permite renombrar un archivo. |
| `mkdir` | Crea una carpeta o directorio. |
| `touch` | Crea un archivo vacío. |
| `cat <nombre archivo>` | Muestra el contenido de un archivo en la terminal. |



