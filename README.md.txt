git init (projectName)
git status                         |workd directory,staging area, repo
ls                                 |list files
ls -al                             |list all files even hidden ones
git add (name) or git add.         |staging area
git commit -m "first commit"       |repo
git log                            |all commits
git show                           |last commit and a diff with all the changes
git ls-file                        |tracking files
rm (name)                          |remove file
git commit -a                      |add modified files to the stage area
git commit -am ""                  |add modified files to the stage area and a message
git reset HEAD (name)              |go back from staged area to work directory
git checkout -- (name)             |remove all changes from a commited file
git log --graph --decorate --all   |show all commits graph representation
git config alias.hist "a command"  |git hist will show the same as the command
git alias (name)                   |will show only the given file
git mv (oldName) (newName)         |rename a file **commit to save the change
git commit -m "renaming example"   |file is renamed
git rm (name)                      |remove a file **commit to complete the deletion
git add -u                         |add changes to stage area
git add -A                         |show the action made (edition/deletions) ** commit to save changes
.gitignore			   |create .gitignore file with all the log files, add and then commit the changes
git diff (name) (name)             |show differences between two files
git branch                         |show local branches
git branch -a                      |show local and remote branches 
git checkout -b (name)             |create a new branch and switch to the new branch
git checkout master                |go back to master
git merge (branch)                 |apply commits from branch to master
git branch -d (name) 		   |delete branch
git mergetool                      |to fix merge troubles 
git tag -a (name) -m "message"     |to create a tag
git tag --list                     |to list tags
git show (tagName)                 |to show tag info
git stash save "message"           |to save last changes but not commit them
git stash list                     |to list the shash
git stash show stash@}\{0\}        |show more info about the stash 0
git stash apply                    |to modify the stash
git stash drop                     |to drop stash
git stash pop                      |to modify and drop the stash
git reset --soft (idCommit)        |to delete the commit and keep it in the stage area
git reset --hard (idCommit)        |to delete the commit from the stage area at once
git revert --no-commit HEAD        |revert the last commit and put it in the stage area
git revert --no-commit HEAD~1      |revert the previous commit of the last one and put it in the stage area
git revert HEAD                    |revert the last commit and commit the change at once
