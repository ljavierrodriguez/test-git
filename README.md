### Iniciar proyecto con git

    $ git init

### Consultar estado del proyecto

    $ git status

### Saber que Ramas (branch) existen

    $ git branch

### Crear una nueva rama (branch)

    $ git branch dev

    $ git checkout -b dev 

### Activar una rama (branch)

    $ git checkout dev

### Preparar Archivos para Commit

    $ git add .

    $ git add -A

    $ git add *

### Guardar en Repositorio Local

    $ git commit -m "Mensaje"


### Configurar datos de usuario

    $ git config --global user.name "Luis J. Rodriguez O."
    $ git config --global user.email "ljavierrodriguez@gmail.com"


### Unir ramas (merge)

    $ git merge master dev