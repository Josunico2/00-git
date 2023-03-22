# Apunte sobre git

## Comandos basicos



### Innit
crea el repositorio de git
### Add 
añade un archivo al proximo commit
### commit -m
crea una version del proyecto en el repositotio
### commit --amend
modifica el commit anterior
### status
te muestra el estado devtu proximo commit
### log
muestra la lista devtodos los commits creado

```bash
git init
git add *nombre del archivo*
git commit -m "mensaje del commit"
git commit --amend
git status
git log 
```

## Descargar repositorio de la nube


### clone
copia el repositorio del link que se le es dado en el link
### pull
actualiza el repositorio a la ultima version en la nube

```bash
git clone  
git pull
```

## .gitignore

git ignora lo que este dentro de este archivo a la hora de usar el git add

```
passwords.txt
build/
*.jpg
```



