# Git-Commands

sudo apt install git-all -> Install Git (Linux/Mac)

git --version -> Check version 

git init -> To get Initialized *(if you already have code and you want to put it in a new Git repository)*


git config --global user.name "xyz"

git config --global user.email "xyz@abc"



### Basics:

git config --global user.name -> To check

git config --global user.email -> To check



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
  

## Github Repository *(if you already have code on Localhost and you want to put it in a new Git repository)*

Step 1: Create a new git repository on github. 

Step 2: Go to the project folder and open terminal or git bash

Step 3: git init (*To initialize the git in the project forlder)*

Step 4: git config --global user.name <username> 

Step 5: git config --global user.email <email>
 
Step 6: git remote add origin https://github.com/username/repo-name.git -> Connect local system with remote repository
*or* 
git remote set-url origin git@github.com:username/repo-name.git -> Connect local system with remote repository


Step 7: git remote -v -> *(To check connection)*

git push -u origin master -> Push to github

git push -u origin "QA" -> Push to github with different branch


## Github Repository *(if you want to clone the project from github to your local system)*

git clone https://github.com/sakaifee/Git-Commands.git
 
 

