# Introduction to git

# Basics Commands

- git init (se realiza una sola vez, esto con la finalidad de añadir el proyecto a git)
- git add . or git add nombre-archivo (adicionar los archivos al staging area)
- git commit -m " " (guardar los archivos que están en el stage area con un comentario)
- git push origin main (subir los cambios al repositorio github/gitlab)
- git status (verificar los archivos que están dentro y fuera del stage area)
- git log (visualizar los commits de nuestro proyecto)
- git branch (visualizar las ramas del proyecto)
- git log --oneline (visualizar commits y ramas del proyecto)
- git branch nombre-rama (crear nueva rama)
- git checkout nombre-rama (cambiar de rama)
- git merge nombre-rama (unir commits de dos ramas)
- git branch -d nombre-rama (eliminar rama)

# Config

start-ssh-agent (Habilitar agente ssh en windows)
- git config --local user.name "Tu nombre aquí"
- git config --local user.email "Tu@email.aqui”

# Tools
Fig -> autoComplete (mac or linux)
oh-my-zsh (mac or linux)