    Branches

this command for list all branches
    $git branch

this command shows branches with some details

    $git branch -v

if you want to delete branch 

    $git branch -d <branch-name>

this command will create branch but not checkout master

    $git branch <branch-name>

if you want to delete any remote branch you can do 

    $ git branch -dr <branch-name>
    its not working incase of remote it only delete it from you local 
this command will delete remote branch from you local machine
    $ git push --delete dev
    

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

when you merge branches there will be two senerio one it fast-forward merge
Fast-forward-merge
------------------
when we created dev branch from master and keeep working on dev. at this time master branch is stoped and didnt do any work on master so there will be no more commits, when we completed work on dev we want to merge it into master, simple checkout on master and call git merge dev so this is a
fast-forward merge

another senerio is where we working on dev and make many commit, same time someone is working os master and make some addtional commits so when we mege dev into master github will create another commit called merge commit ...


----------------------------------------------------------

git stash
--------

git stashes are used to save all changes temporly mean pause your work for 
some time if you are working on a branch and urgently you need to move on another branch without commit changes so for that you have stash you changes
move to you requried branch and after that when work completed you come back and start working on your branch with stash

commands

git stash

git stash save my-stash

git stash list

git stash pop

in this stash@{1} you get from git stash list

git stash apply stash@{1}

if you want to clear your stashes

git stash clear

-----------------------------------------------


