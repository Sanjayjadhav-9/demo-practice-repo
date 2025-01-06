Git Bash commands: 
------------------
we are having several git commands to perform operations with git repository.

Note: We have created git repository in github.com

Git Repo URL : https://github.com/Sanjayjadhav-9/demo-practice-repo.git

git bash commands:
------------------
init
clone
add
status
commit
push
pull
checkout
reset
log
rm
branch
merge
rebase
stash

git help --> It provides frequently used several git commands

git help <cmd-name> --> It opens documntation of that particular command

ex: git help init

git init --> It is used to create empty repository or re-initialize existing repo

git status --> This command will display status of current repository

staged files
------------
Files which are added and they are ready to commit.
These file names will be displayed in green color.

un-staged files
---------------
Modified files will be displayed here, we need to stage these files to commit.
These files names will be displayed in red color.

un-tracked files
----------------
Newly created files, we need to stage them to commit.
These file names also will be displayed in red color. 

git add : This command is used to add the file to staging area.

    syntax: git add <file-name>
    syntax: git add --a --> To add all files at a time.

git rm : This command is used to un-stage newly created files

    syntax: git rm --cached <filename>

