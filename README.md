## Commonly used ```git``` commands

```git init``` initializes a Git repository

```git status``` shows the current state of the project

```git add <file(s)>``` adds file(s) to the staging area

```git commit -m "<message>"``` stores the staged changes with a message describing the changes

```git log``` shows the changes that have been made in the order they were made

```git remote add origin <Repository URL>``` adds a remote repository

```git push -u origin master``` pushes changes to the origin repository (GitHub), -u tells Git to remember the parameters

```git pull origin master``` pulls any new changes to the repository

```git diff HEAD``` shows the what is different since the most recent commit

```git reset <file(s)>``` unstages the specified files

```git checkout -- <file(s)>``` changes files back to how they were at the last commit

```git branch <branch_name>``` creates a branch to make a copy of the code so changes can be made and merged back in later

```git rm <'file(s)'>``` removes file from disk and stages the removal of the files

```git merge <branch_name>``` merges the changes from the branch into the master branch

```git branch -d <branch_name>``` deletes the specified branch
