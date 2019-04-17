## Ariel -> COMANDOS APRENDIDOS



|       COMMAND         |USE                                                   |
|----------------|-------------------------------
|`git init`|initializes git repo in the directory
|`git config (--global) user.name "[insert username]"  `     |sets the username   
|`git config (--global) user.email "[insert email]"`|set the email
|`git add` 	|stages a file
|`git commit -m "commit message"`|commits staged files with message
|`git remote add origin [insert repo URL] `|set the origin of the repo
| `git push -u origin master`|pushes commit to the master branch in the origin for the first time
|`git checkout -b feature/nome`|create branch and changes to it
|`git checkout master`|change to branch
| `git pull`| gets any new commits and applies to the project


### Comandos utilizados

    git init
    git config user.name "aiml150"
    git config user.email "ariel.molina@gft.com"
    echo "bem bestinha" >> bemBestinha.txt
    git add .\bemBestinha.txt
    git commit -m "commit bestinha"
    git status
    git remote add origin https://github.com/starters-gft/aimlGit.git
    git push -u origin master
    rm *
    git clone https://github.com/starters-gft/aimlGit.git
    git checkout -b FEATURE/mudar-texto
    git add .
    git commit -m "Texto alterado"
    git push origin FEATURE/mudar-texto
