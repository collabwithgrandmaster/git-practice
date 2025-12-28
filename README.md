# git-practice
trying out basic git commands

git config --global user.name "<username_here>"

git config --global user.email "<email_here>"

## this one lists the config
git config list

## to track a changes to a project folder / turn on the git switch
git init

## to get the current status and see what has been done so far
git status

## this one is for setting alias

git-practice % git config --global alias.i init

git-practice % git config --global alias.s status

now you can use git i for git init & git s for git status

## to add any untracked file to staging area
git add <file_name>
or
git add . # to stage all untracked files 

## to save changes made to the staged file commit is used
git commit -m "initial commit" 

## to create a local copy of a remote repository(Https) 
git clone <repo_url.git>