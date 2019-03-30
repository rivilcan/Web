# Parte 1: Usando Git for Windows

## a. [Control de versiones (VC)](https://git-scm.com/book/es/v1/Empezando-Acerca-del-control-de-versiones)

- Es un sistema que guarda los cambios hechos en un conjunto de archivos, para que estos se puedan recuperar en versiones específicas más adelante, o para combinar los avances de distintos integrantes.

## b. [Control de versiones distribuido (DVC)](https://git-scm.com/book/es/v1/Empezando-Acerca-del-control-de-versiones)

- Logra llevar un control simultaneo de versiones para todos los desarrolladores, lo que trae como consecuencia un respaldo del proyecto en comun, por lo que si se llega a perder el trabajo de un desarrollador, los otros pueden recuperarlo. 


## c. [Repositorio remoto y Repositorio local](https://git-scm.com/docs/gitglossary)

- Repositorio local es cuando se guardan las versiones del proyecto en el equipo, lo cual vuelve más dificil el trabajo grupal.

- El remoto es lo mismo pero alojado remotamente, permitiendo el intercambio entre los demas desarrolladores.

## [d. Copia de trabajo / Working Copy](https://www.thomas-krenn.com/en/wiki/Git_Basic_Terms)

-Existen muchas versiones y copias del repositorio, por lo que cualquier persona con un clon puede trabajar en él. Los cambios que han sido hechos en la copia de trabajo, se pueden subir al repositorio remoto, para hacer visibles estos cambios.

## e. [Área de Preparación / Staging Area](https://git-scm.com/book/es/v1/Empezando-Fundamentos-de-Git)

- Es el indice de archivos que se estan agregando o modificando en un sencillo archivo, se le denomina índice, pero se está convirtiendo en estándar el referirse a ella como el área de preparación.

## [f. Preparar Cambios / Stage Changes](https://softwareengineering.stackexchange.com/questions/119782/what-does-stage-mean-in-git)

- Añade los archivos que hayan sido modificados o agregados al area de preparacion.

## [g. Confirmar cambios / Commit Changes](https://www.git-tower.com/learn/git/commands/git-commit)

- Se confirma que una versión del archivo está subida en el directorio de Git, esta se considera confirmada.

## h. [Commit](https://www.git-tower.com/learn/git/commands/git-commit)

- Sube y actualiza los archivos en el repositorio.

## i. [clone](https://git-scm.com/docs/git-clone)

- Clona un repositorio en un directorio del desarrolador.

## j. [pull](https://git-scm.com/docs/git-pull)

- Agrega los cambios en un repositorio local.

## k. [push](https://git-scm.com/docs/git-push)

- Actualiza y fusiona repositorios remotos usando los archivos en los repositorios locales.

## l. [fetch](https://git-scm.com/docs/git-fetch)

- Obtiene ramas y / o etiquetas de uno o más repositorios, pero sin combinarlos con el repositorio local.

## m. [merge](https://git-scm.com/docs/git-merge)

- Incorpora cambios de las commit a la rama actual.

## n. [status](https://git-scm.com/docs/git-status)

- Muestra los estados de los archivos que poseen diferencias en el directorio de trabajo y en el área de pruebas

## o. [log](https://git-scm.com/docs/git-log)

- Muestra el historial de commits que se han hecho en el repositorio.

## p. [checkout](https://git-scm.com/docs/git-checkout)

- Actualiza los archivos en el árbol de trabajo para que coincidan con la versión en el índice o el árbol especificado. tambien sirve para cambiar la rama en que se esta trabajando.

## q. [Rama / Branch](https://www.arsys.es/blog/programacion/ramas-git/)

- Genera de forma paralela varias versiones del codigo, sin que estas afecten a la rama principal.

## r. [Etiqueta / Tag](https://git-scm.com/docs/git-tag)

- Agrega una referencia de etiqueta,  generalmente se usa para colocar la versión del codigo.
