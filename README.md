# git-cheat-sheet

# Setting Up Git

git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
git config --list

# Getting & Creating Projects

git init
git clone ssh://git@github.com/[username]/[repository-name].git

# Basic Snapshotting

git status
git add [file-name.txt]
git add -A
git commit -m "[commit message]"
git remote -v

# Branching & Merging

git branch
git branch -a
git branch [branch name]
git branch -d [branch name]
git push origin --delete [branch name]
git checkout -b [branch name]
git checkout -b [branch name] origin/[branch name]
git branch -m [old branch name] [new branch name]
git checkout [branch name]
git checkout -
git checkout -- [file-name.txt]
git merge [branch name]
git merge [source branch] [target branch]
git stash
git stash pop
git stash clear

# Sharing & Updating Projects

git push origin [branch name]
git push -u origin [branch name]
git push
git push origin --delete [branch name]
git pull
git pull origin [branch name]
git remote add origin ssh://git@github.com/[username]/[repository-name].git
git remote set-url origin ssh://git@github.com/[username]/[repository-name].git

# Inspection & Comparison

git log
git log --summary
git log --oneline
git diff [source branch] [target branch]
