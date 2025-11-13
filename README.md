# git-help
A small collection of git explenations

## Basic workflow
``git status`` - show current changes (tracked & untracked)  
``git add <PATH>`` - add files to tracked files  
``git rm --cached <PATH>`` - remove a file from the repo without deleting it (make sure that the file is ignored!)  
``git commit -m "<MESSAGE>"`` - create a commit containing tracked files  
``git fetch`` - fetch from remote  
``git pull`` - pull from remote (with merge commit)  
``git pull --rebase`` - pull (rebase mode)  
``git push`` - push to remote  
``git reset --hard HEAD`` - rollback to last commit  
``git reset --mixed HEAD~1`` - undo last commit (all changes will be unstaged)

## Branches
``git branch`` - show branches  
``git checkout <BRANCH>`` - switch branch

## Origin
``git origin -v`` - show remote  
``git remote set-url origin <URL>`` - change remote  
-> ``git push --all`` - push all to remote (for new repos)

## Configuration
``git config --list`` - lokale config anzeigen  
``git config --global --list`` - globale config anzeigen  
``git config --global user.name "<NAME>"`` - username setzen  
``git config --global user.email "<EMAIL>"`` - email setzen  
