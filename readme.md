#Working Directry
-Area where all of our files and directries and changes are living all the time

#Staging Area
-Files and directries that we expicitly add to the staging area
-It stays after git add . command

#Git Repository
-where all are snapshots are stored
-Like github

#Basic commands
*git init
*git status
*git add
*git commit

#Git checkout
*git log
*git checkout

 Head
 0->0->0->0       *that means when we checkout for a location copy of
          Master   master named  Head is is indicate the particular location 
                   but this is only read only operation actual execution is 
                   remained at master itself
          
          
*git revert --no-commit 123452ddd..HEAD


NOTE: 
-->removing files :git reset filename
-->Ignoring files :touch .gitignore, then save files into it which we want to hide

#Make new bracches and then merge them together into master branch:
    
     @---@---@---@ -->new branch
    /           /
@---@---@---@---@  -->master branch

*commands:
-->make new branch: git checkout -b newBranch

-->switch to master: git checkout master

-->see branches: git branch

-->merge two branch:git merge <current-barnch> <mergable-branch> 
                   ,like(master) git merge newBranch

-->delete branch:git branch -d branchName  

#COMMANDS FOR GITHUB

-->For add git to github: git remote add origin URL
--> than check the remote origin: git remote -v
-->for push the master into github: git push -u origin master
-->for delete an existing origin:git remote rm origin

note:Run ssh-keygen -lf ~/.ssh/id_rsa.pub,and make sure the output matches 
     the Fingerprint of the Cloud9 key on GitHub 9.


 

          