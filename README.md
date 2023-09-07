# Git guide
---
## Usual commands  

`c` - change directory  
`ls` - list directory  
`~` - user's main directory  
`..` - directory up to current  
`touch` - make new file 
`mkdir` - make new directory  
`pwd` - print working directory  
`mv` - move file or directory  
`cp` - copy file or directory  
`cat` - print file.txt  
`rm` - remove file  
`rmdir` - remove directory  
`rm -r` - remove not empty directory and all files in it  
----
## You may also rope yor repository with github  

`git init` - initialize repository  
`rm -rf .git` - undo previous action  
`git status` - see status of working repository  
`git add` - add new or modified file in repository  
`git commit -m` - save added files and write comment  
`git log` - see all commits  
`ls -la .ssh` - print list of ssh-keys  
`ssh-keygen -t ed25519 -C "users@mail.ru"` - create ssh-keys  
`clip < ~/.ssh/id_ed25519.pub` - copy public ssh-key  
`git remote add origin git@github.com:%ИМЯ_АККАУНТА%/first-project.git` - add remote repository  
`git remote -v` - check if remote and local repository are roped  
`git push -u origin master` - load local repository first time  
`git push` - load local repository  
`git commit --amend --no-edit` - add new file in last commit (add files before)  
`git commit --amend -m` - change comment of last commit  
`git restore --staged <file>` - remove <file> from staged area  
`git reset --hard <commit A hash>` - delete all commits after A  
`git restore <file>` - undo changes with `modified` files  
<<<<<<< HEAD
`git clone <ssh of repository>` - load repository from github  
`git branch` - show branchs in repository  
`git branch <name of branch>` - make new branch  
`git checkout <name of branch>` - swich branch  
`git checkout -b <name of branch>` - make new brench and swich on it  
= ======
>>>>>>> 5bef594b7255b8cd48c34192b67381a97b07bba2
----
## Markdown guide 
 
[click here](https://gist.github.com/fomvasss/8dd8cd7f88c67a4e3727f9d39224a84c#links)
----
## Git Log  

Function return Hash of commit, it's author, data and comment  
Hash is a unique code of commit  
Head is a file keeping hash of latest commit  
----
## Status  

file have status: `untracked`, `tracked`, `staged` and `modified`  
`tracked` = `staged` || `modified` = `~untracked`  
