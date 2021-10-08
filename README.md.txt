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


