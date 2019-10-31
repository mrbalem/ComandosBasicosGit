# ComandosBasicosGit
comandos basicos de git para poder integrar github y gitlab


### Instrucciones de la línea de comando
#### También puede cargar archivos existentes desde su computadora utilizando las instrucciones a continuación.

## Configuración global de Git
  git config --global user.name "Mrvalem"
  git config --global user.email "mylovepre16@gmail.com"

## crear un nuevo repositorio
  git clone https://gitlab.com/mylovepre16/nkbkhb.git  || https://github...git
  cd nkbkhb
  touch README.md
  git add README.md
  git commit -m "add README"
  git push -u origin master

## Empuje una carpeta existente
  cd existing_folder
  git init
  git remote add origin https://gitlab.com/mylovepre16/nkbkhb.git
  git add .
  git commit -m "Initial commit"
  git push -u origin master

## Empuje un repositorio Git existente
  cd existing_repo
  git remote rename origin old-origin
  git remote add origin https://gitlab.com/mylovepre16/nkbkhb.git
  git push -u origin --all
  git push -u origin --tags
