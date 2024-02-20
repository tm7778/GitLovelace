# COMANDOS PARA GIT

## Comando para ver la versión instalada de git

- git -v
- git --version

## Comandos para configución inicial de github

- git config --global user.name "My first Name"
- git config --global user.email "tomas1213monto@gmail.com"

## Comando para editar o ver la configuración de git

- git config --global --edit
- git config --global --list

## Pasos para crear una versión de 

1. agregar todos los archivos al commit

2. Tomar la foto del código (Crear una versión nueva)

- git commit -m "Nombre del commit"
<!-- Para agregar todos -->
- git add . 
<!-- Para agregar de un lenguaje en especifico -->
- git add *.js
<!-- Para agregar una carpeta en especifico  -->
- git add style.css

## Comando para saber el estado de nuestro git

git status

## Comando para listar las versiones de mi proyecto

- git log
- git log --oneline

## Comando para cambiar de versión
- git checkout <Id del commit o nombre de la rama>