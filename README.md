# JavaCollabExercise

## Creación y Clonación de Repositorios

Inicia un nuevo repositorio de Git en tu directorio actual:

```sh
git init

## Clona un repositorio existente en GitHub a tu máquina local:
```sh
git clone https://github.com/username/repo.git


# JavaCollabExercise

Este es un ejercicio colaborativo para aprender a usar Git y GitHub en el contexto de un proyecto de Java.

## Configuración Inicial de Git

Configura tu identidad en Git, importante para los commits.
```sh
git config --global user.name "Tu Nombre"
git config --global user.email "tuemail@example.com"
```

## Creación y Clonación de Repositorios

Inicia un nuevo repositorio de Git en tu directorio actual:
```sh
git init
```
Clona un repositorio existente en GitHub a tu máquina local:
```sh
git clone https://github.com/username/repo.git
```
## Estadios y Commits

Verifica el estado de tus archivos y los cambios pendientes:
```sh
git status
```
Agrega archivos modificados al área de preparación:
```sh
git add <archivo>
git add .  # Agrega todos los archivos modificados
```
Commitea los cambios en el área de preparación:
```sh
git commit -m "Mensaje del commit"
```
Envía commits al repositorio remoto:
```sh
git push origin <rama>
```
Actualiza tu repositorio local al commit más nuevo:
```sh
git pull
```
## Ramas

Muestra todas las ramas locales:
```sh
git branch
```
Crea una nueva rama:
```sh
git branch <nombre-rama>
```
Cambia a otra rama:
```sh
git checkout <nombre-rama>
```
Crea una nueva rama y cámbiate a ella:
```sh
git checkout -b <nombre-rama>
```
Elimina una rama local:
```sh
git branch -d <nombre-rama>
```
## Trabajando con Remotos

Muestra los repositorios remotos configurados:
```sh
git remote -v
```
Vincula tu repositorio local con un repositorio remoto:
```sh
git remote add origin https://github.com/username/repo.git
```
Elimina la vinculación a un repositorio remoto:
```sh
git remote remove origin
```
