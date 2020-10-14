
at first you need to configure your git user, password, and email

git config --global user.name="qasim683"
git config --global user.password="********"
git config --global user.email="youremail@example.com"


basic operations 

initialize
add
commit
pull
push

advance operation

branching 
merging
rebasing
--------------------------------------------
this command use to add files to staging area
    $git add .

if you want to unstage files which you have stage with previous command

    $git reset      (this command only reset files unstage area not revert changes which you have acctully made in files)
if you want to reset all changes which you have added into files

    $git reset --hard
    
git add <file-name>   

this command use to commit changes to local repo

git commit -m "my commit"
