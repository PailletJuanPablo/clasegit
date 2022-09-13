# Git

## Que es 
App que les permite trabajar en conjunto, poder revertir el código a un commit, tener un respaldo del código en la nube.

## Como funciona
El código se va versionando a través de commits
Un commit contiene:
    - Comentario
    - Archivos
    - Usuario
    - Fecha

- Uno crea un commit en su repositorio local
- Sincronizar (subir/bajar los demas commits) el commit con el repositorio remoto

1 Repositorio remoto por cada proyecto
n repositorios locales por cada proyecto


# Inicializar repositorio local

git init
Crea carpeta .git que permite el funcionamiento del software

# Crear un commit
- Agregue uno o varios archivos para ser commiteados
    git add nombreArchivo
    git add .
- Añadir comentario al cambio 
    git commit -m "Mensaje"

# Vincular con repositorio remoto
- Crear un repositorio remoto (vacío)
- Vincular mi repositorio local con el repositorio remoto creado

# Agregar commits desde local a remoto
- git add .
- git commit -m "Mensaje informando los cambios realizados"
- git push

# Sincronización
- Sincronizamos remoto con local
    git pull
NO van a poder pushear nuevos commits sin antes haber hecho pull


