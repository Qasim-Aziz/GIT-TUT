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