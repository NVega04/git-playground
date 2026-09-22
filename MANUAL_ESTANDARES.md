# Manual de Estándares y Convenciones de Git

## 1. Visión General
Este documento define el flujo de trabajo estándar, las convenciones de nombres y las buenas prácticas para la gestión del código fuente en este repositorio. El cumplimiento de estos estándares garantiza un control de versiones limpio, revisiones de código sencillas y una colaboración fluida entre los miembros del equipo.

## 2. Resolución de Conflictos
Cuando ocurra un conflicto durante un pull o merge:

Identifica los archivos en conflicto ejecutando git status.

Abre los archivos marcados y resuelve las diferencias manualmente.

Una vez resueltos, agrega los cambios:

``` 
Bash
git add .
``` 

Finaliza el proceso de fusión continuando el commit:

``` 
Bash
git commit -m "fix: resolve merge conflicts with develop"
```
