    Branches

this command for list all branches
    $git branch

this command shows branches with some details

    $git branch -v

if you want to delete branch 

    $git branch -d <branch-name>

this command will create branch but not checkout master

    $git branch <branch-name>

this command will create new branch and checkout from master to newly created branch

    $git checkout -b <branch-name>

if already created branch you just checkout on created branch by this command

    $git checkout <branch-name>

---------------------------------------------------------------

Merge

if you want to merge a branch you need to commit all changes into branch which
you want to merge then checkout to the master and type this command

from master head
    $git merge <branch-name>

show commit diffrence in two branches

    $ git log new-dev..master