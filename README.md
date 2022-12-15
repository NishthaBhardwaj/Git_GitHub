# Git_GitHub


Reset the last commit
-----------------------

git reset --soft HEAD~1
git reset --hard HEAD~1

Delete the branch
----------------------

git branch -D (force delete) branch-name
git branch -d (if you merger the branch) branch-name

git clean -df (delete all the files that you have just created)

List data in staging area
----------------------------
git ls-files

git checkout commitID (checkout commit detached-head)

git branch branch-name or git switch branch-name -- create new branch
git brach branch-name -- go to branch
git branch -b branch-name git switch -c branch-name -- create and access new branch
git merge otherbranch -- bring other branch's changed in current branch

Delete Data
------------------

WD(Working Directory) files
git rm filename git add filename -- run command after file was deleted from working directory

unstaged changes
-----------------  not run the add command

git checkout filename or . 
git restore filename or .   revert changes in tracked file
git clean -df delete untracked files

staged changes
-----------------
remove files from staging are
------------------

git reset filename & git checkout -- filename
git restore --stage filename or .          


latest commit
--------

git reset HEAD~1
git reset --soft HEAD~1
git reset --hard HEAD~1 -- undo latest (~1) commit

Branch
------
git branch -D branch-name   delate branch


Useful Resources & Links
---------------------------

Official Git website => https://git-scm.com/

Git MacOS installation => https://github.com/git-guides/install-git

Git commands reference => https://git-scm.com/docs



