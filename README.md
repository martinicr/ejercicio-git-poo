Ejercicio Git
=============

## Crear un repositorio local
```
git init <ruta>
git init .
```

## Annadir archivo
```
git add <ruta | expression regular>
git add README.md
git add README.md archivo.txt
git add *.md
git add .
```

## Confirmar los cambios
```
git commit -m <comentario>
git commit -m "Initial commit"
```

## Ver el estado del repositorio
```
git status
git log
git show
```

## Crear ramas (branches)
```
git branch # Nos dice en que branch estamos posicionados
git branch <nombre-branch> # No se pasa
git checkout -b <nombre-branch> # Crea el branch y se pasa
```


## Ver diferencias
```
git diff
```


