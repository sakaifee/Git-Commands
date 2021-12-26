# Git-Commands

sudo apt install git-all -> Install Git (Linux/Mac)

git --version -> Check version 

git init -> To get Initialized *(if you already have code and you want to put it in a new Git repository)*


git config --global user.name "xyz"

git config --global user.email "xyz@abc"



### To check config:

git config --global user.name

git config --global user.email



code . -> Run VS Code using terminal


ls -> list of all files

ls-lart -> Show hidden files/folder


git status -> Show the status of git

git status -s -> Short status


git add . -> Add files in stagging area 
 
git add index.html -> Add particular file in staggging area


touch contact.html -> Make blank file using cmd


git checkout -> Revert back the last commit

git checkout -f -> Revert back all the files from last commit

git log -> Show history of commit

git log -p -2 -> Show history of last two commits

git diff -> Campare working tree with stagging area 

git diff --staged -> Compare stagging area with last commit

git commit -a -m -> Skip stagging area and commit

git commit -m "code updated" -> To commit the changes


git rm "index.html" -> Remove file from working directory and staging area

git rm --cached "index.html" -> Remove file only from stagging area


git ignore -> Ignore the useless files

touch .gitignore -> Make gitignore file



## Branches

git branch "QA" -> To create new branch

git branch  -> Show all branches

git checkout "QA" -> Switch branch

git checkout "master" -> To change the branch
 
git merge "QA" -> To merge master branch with QA branch

git checkout -b "Dev" -> To create branch and switch it in same branch
  

 

