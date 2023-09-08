# Resumen de Comandos de Git

Este archivo resume los comandos de Git más utilizados durante nuestro trabajo.

## Configuración Inicial

| Comando                 | Descripción                                     |
| ------------------------| ----------------------------------------------- |
| `git config --global user.name "<nombre>"` | Configurar nombre de usuario global. |
| `git config --global user.email "<correo>"` | Configurar correo electrónico global. |

## Creación de Repositorios

| Comando                 | Descripción                                     |
| ------------------------| ----------------------------------------------- |
| `git init`              | Inicializar un nuevo repositorio local.       |
| `git clone <URL>`      | Clonar un repositorio remoto en local.        |

## Trabajo con Cambios

| Comando                 | Descripción                                     |
| ------------------------| ----------------------------------------------- |
| `git add <archivo>`     | Agregar cambios al área de preparación.        |
| `git commit -m "<mensaje>"` | Confirmar cambios con un mensaje.          |
| `git status`            | Ver el estado de los archivos en el repositorio. |

## Trabajo con Repositorios Remotos

| Comando                 | Descripción                                     |
| ------------------------| ----------------------------------------------- |
| `git remote -v`         | Mostrar repositorios remotos configurados.     |
| `git remote add <nombre> <URL>` | Agregar un repositorio remoto.            |
| `git push -u <remoto> <rama>` | Enviar cambios a un repositorio remoto. |