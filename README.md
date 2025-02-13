# Git & Github Command 

## Global To Local 
    Clone any repo          -> git clone (repo https link)
    Show all files(hidden)  -> ls -a
    untracked files(U) || modified file (M)
    Check file status       -> git status
    Add file                -> git add fileName || Add all file -> git add . 
    commit file             -> git commit -m "(add massage)"
    push to local to global -> git push origin main

## Local To Global
    Create folder and push repo

    git init                -> used to create trackable git repo
    git add fileName        -> Add file || Add all file -> git add . 
    git commit -am "msg"    -> add & commit (modified)
    git remote add origin (repo link)
    git remote -v           -> check remote
    git branch              -> check branch
    git push origin main    -> push local to global
    
## Git Branches
    git branch                          -> check branch
    git branch -M branchName            -> rename branch
    git checkout (branch name)          -> to navigate (change branch)
    git checkout -b (new branch name)   -> create new branch
    git branch -d (branch name)         -> delete branch

## Git Merging code
    git diff (branch name)      -> to compare commits,branches,files & more
    git merge (branch name)     -> to merge 2 branches

## Pull Request
    git pull origin main -> pull global to local

## Fixing Mistakes
    git reset (file name) || git reset  -> staged changes ( back one stage 'git add' ka)
    git reset HEAD~1                    -> commited changes (back one commite 'git commit' ka)
    git log                             -> commit records with hash code
    git reset (commit hash)             -> commited changes (for many commits )
    git reset --hard (commit hash)      -> commited changes (for many commits remove code )

## Create a pull request on other github account
    Github---------------
    click fork                    -> fork repository
    copy link                     -> copy fork repo link 
    terminal-------------
    mkdir folder_name             -> create folder
    cd folder_name                -> open folder
    git clone <repo-link>         -> clone repository 
    cd repo                       -> open repository
    file exploral -------
    copy folder                   -> copy project folder 
    paste repo folder             -> paste project in repository
    terminal-------------
    git status                    -> check status	(show untracked)
    git add .                     -> add file or folder
    git commit -m "add file"      -> commit file or folder
    git push origin branch_name   -> push local to global
    github---------------
    refresh github account 		
    open repo
    click Pull requests
    click New pull request
    select branch_name 
    click Create pull request
    type Some message
    click Create pull request

## Terminal 

    List files               -> ls (Show files)
    Print Working Directory  -> pwd (Current directory, Where am I)
    Change directory         -> cd (file name)
    Back Button              -> cd..
    Outside directory        -> cd /
    Home directory           -> cd ~
    Make directory           -> mkdir folderName (make folder)
    Delete Empty folder      -> rmdir folderName
    Create file              -> touch app.js (New file with extension)
    Delete files             -> rm app.js

    //With Flags

    List files               -> ls -a (Show hidden files)
    Remove file forcefully   -> rm -rf fileName (rf = recursive force -delete folder that contain data)
    

# Coder
Siddhartha Raghuvanshi

## Thank you for Visit...