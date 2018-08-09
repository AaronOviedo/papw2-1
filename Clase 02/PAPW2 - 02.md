<!-- $theme: default -->

PAPW 2
===

##### Alberto Benavides
###### Ago - Dic 2018

<!-- footer: Universidad Autónoma de Nuevo León | Facultad de Ciencias Físico Matemáticas | Multimedia y Animación Digital -->

---

# 2. Servidores remotos

---

## Observaciones tarea

* Alternativas:
    * Git Kraken
    * Git Desktop
* Repositorio: carpeta que tiene `.git` (álbum)
* ¡Cuidado con el plagio! Traducir un texto íntegro y ponerlo como propio también es plagio.
* verSiones, utilicÉ, usÉ, línea, más (cantidad)

---

## Servidores de Git

GitHub | Bitbucket
---|---
<img src="https://image.flaticon.com/icons/svg/25/25231.svg" alt="drawing" width="350px"/> | <img src="https://cdn.freebiesupply.com/logos/large/2x/bitbucket-logo-png-transparent.png" alt="drawing" width="330px"/>
---

## Ramas

```git
rem Muestra las ramas
git branch

rem Crea una rama
git checkout -b <rama>

rem Une la rama en la actual
git merge <rama>
```

---

## Ver cambios y [revertirlos](https://githowto.com/undoing_local_changes)

* Dedicatoria: 4074

```git
rem Ver cambios
git diff

rem Quita cambios preparados
git reset HEAD <archivo>

rem Revierte los cambios no preparados
git checkout <archivo>
```

---

## Repositorios remotos

```git
rem Añade la url como remoto
git remote add <nombre> <url>

rem Envía actualizaciones a un remoto
git push <remoto> <rama>

rem Busca cambios en remoto
git fetch <remoto> <rama>

rem Descarga cambios de remoto
git pull <remote>
```

---

## Ejemplo

1. Hacer un repositorio local con una rama adicional llamada `develop`
2. Crear un commit en dicha rama.
3. Crear un repositorio público.
4. Subir el repositorio a un servidor.

* Mostrar flujo de trabajo recomendado por [Atlassian](https://es.atlassian.com/) en Sourcetree.

---

## :warning: Tarea :warning:
###### +2 en primer parcial

* Crear un repositorio con un archivo de texto y hacer un commit.
* Agregar un archivo (`txt`, `md`, `pdf`, `html`) que explique cómo crear un repositorio con una rama adicional en Git o Sourcetree. Hacer un commit.
* Subir el repositorio a GitHub o Bitbucket.

---

# Fuentes

* https://www.atlassian.com/git/tutorials
* https://confluence.atlassian.com/bitbucket/create-a-git-repository-759857290.html
* https://www.atlassian.com/dam/jcr:8132028b-024f-4b6b-953e-e68fcce0c5fa/atlassian-git-cheatsheet.pdf
