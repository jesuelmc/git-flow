# GIT-FLOW
Despues de que Vincent Driessen presento su modelo de ramificacion, se volvio muy popular y de esta manera fue que nacio lo que es Git-Flow que es un conjunto de extensiones para git basados en su modelo. En escensia lo que hace git-flow es correr comandos de alto nivel en la consola que en realidad con son un conjunto de comandos tradicionales de git.

Git-flow se basa en el funcionamiento sobre ramas, por lo que la forma de organizar con git rebase no se aplica en esto.

## Instalación
Linux
```
apt-get install git-flow
```
Windows
```
wget -q -O - --no-check-certificate https://raw.github.com/petervanderdoes/gitflow-avh/develop/contrib/gitflow-installer.sh install stable | bash
```
## Forma de uso
>Inicializar:     `git flow init`

>Crear nuevo feature: `git flow feature start NewFeature`

>Finalizar feature: `git flow feature finish NewFeature`

>Empezar release: `git flow release start RELEASE`

>Publicar release: `git flow release publish RELEASE`

>Cierre de la publicación release `git flow release finish RELEASE`

>Empezar hotfix: `git flow hotfix start VERSION`

>Concluir hotfix: `git flow hotfix finish VERSION`

No obstante todo lo que hace git-flow tambien se puede realizar con puros comandos de git, aunque su potencial se halla en la manera que rectifica y delimita la forma de trabajo para ayudar a evitar conflictos futuros.
