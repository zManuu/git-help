# git-help
A small collection of git explenations

## Basic workflow
``git status`` - show current changes (tracked & untracked)  
``git add <PATH>`` - add files to tracked files  
``git rm --cached <PATH>`` - remove a file from the repo without deleting it (make sure that the file is ignored!)  
``git commit -m "<MESSAGE>"`` - create a commit containing tracked files  
``git push`` - push to the remote repository  
``git reset --hard HEAD`` - rollback to last commit  

## Configuration
``git config --list`` - lokale config anzeigen  
``git config --global --list`` - globale config anzeigen  
``git config --global user.name "<NAME>"`` - username setzen  
``git config --global user.email "<EMAIL>"`` - email setzen  
