undo local changes

if you want to discard chenges only a particluar file 

    $git checkout HEAD <file-name>

if you want to discard all changes from staging area

    $git reset --hard HEAD


----------------------------------------------------------

undo committed changes

if you want to delete commited changes you can do 

    $git revert <commit-hash>

this will reset you at required commit it move you head on require commit and discard all commit from history .......

    $git reset --hard <commit-hash>

if you want to reset --hard but keep changes available 

    $git reset --keep <commit-hash>

(when you have made commits and push , after that you relize you want to take back your head on previous commit with reset --hard, after that you want to push on remote repos you face error which says your remote repos ahead of you commit it can be many commits if you pull all previous commit will be added and obsiously you dont need because you want to remove this commits so in this case you used force push you commit  )
when pushing you find eroor you can force push by

    $git push -f origin master

