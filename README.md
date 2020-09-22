# test
contains all the test repos

# Steps to merge 2 repos

test - > 

test-git
desktop-tutorial
git_vscode_test
demo
hello-world


trainings ->nodecamp to become a folder in trainings repo


git clone git@github.com:jababanik/test.git

cd test/

git remote -v

git branch -a -vv

git remote add demo git@github.com:jababanik/demo.git

git fetch demo

git checkout -b demo demo/master

git branch

ls

git checkout master

git checkout demo

ls

git status

mkdir demo

ls

git mv code.py demo/

git mv README.md demo/

ls

git status

git commit -m "Moved all files into a subfolder demo"

git checkout master

ls

git checkout demo

ls

git checkout master

git merge demo --allow-unrelated-histories

git commit -m "Merged with demo repository"

ls

git push

git remote rm demo

git branch -d demo

git branch -a -v





