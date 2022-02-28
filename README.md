#Welcome to Git

##Git commands:

##To add files to staging area:
git add "filename"
git add .   -> for all files

##To get status of files:
git status

##To create log:
git log    -> prints all details
git log --oneline     -> print one line log
git log commitid1...commitid2    -> gives log between particular range
git log --follow -- filename    -> gives log of particular file 

##To get difference between local and remote branch:
git diff main origin/main

##To reset
git reset --hard HEAD~1   -> previous commit

##To create a branch:
git branch br_name
