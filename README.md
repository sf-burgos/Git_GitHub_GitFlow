# Git_GitHub_GitFlow

# Repositorios locales

### Área de ensayo y repositorio local

> git init

### Seguimiento de archivos

> git add "nombre_archivo"

### Enviar todo lo añadido con el comando add al repositorio local

> git commit 

![image](https://user-images.githubusercontent.com/45188320/129400858-a7c2f40a-fea8-471f-afbe-d4bd2a572fa3.png)

### Observar todos los archivos con seguimiento

> git status -s 

- ? archivos sin seguimiento
-  A archivos con seguimiento
-  M archivos modificados, sin respaldo

### Listado de todas las copias que existen desde la creación del proyecto

> git log --one line 

### Restaurar el archivo "donde queremos ir"

> git reset --hard "code_before"

# Repositorios en GITHUB

### Agregar todos los archivos

> git add .

### Es un git add y un git commit -m "mensaje" en una sola linea 

> git commit -am "mensaje del commit"

### Subir de un repositorio local a GITHUB

> git remote add origin "url del repositorio en GITHUB"

### Descargar los cambios de GITHUB al repositorio local

> git pull

### Agregar los tags al repositorio local 

> git tag "nombre version" -m "version y comentario"

### Subir los tags a GITHUB

> git push --tags

### Clonar un repositorio desde GITHUB a un repositorio local

> git clone "url del Repositorio"

# RAMAS o BRANCH

![image](https://user-images.githubusercontent.com/45188320/129415918-6638dcd3-8e6c-4c3d-80af-2a8aaefda3dd.png)

### Crear una nueva rama 

> git branch "nombre de la rama"

### Ver las ramas que existan

- * un asteristico representa donde estamos trabajando

> git branch

### Cambiar de rama 

> git checkout "nombre de la rama a la que me quiero trasladar"

- Luego de trasladarme a master o donde quiera que sea, donde quiero mezclar ramas

> git merge "rama que quiero que se mezcle"

### Borrar un rama 

> git branch -d "nombre de la rama que quiero borrar

### Borrar y recuperar cambios con git (stash) 

https://styde.net/deshacer-y-recuperar-cambios-con-git/







   






