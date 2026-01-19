# git lab exam
git lab exam conducted on 19/01/2026

commands used

git init
git global --config user.name
git global --config user.email

git clone<repo link>
cd<repo>
# to move inside the file  

touch <file name> (to create the file )
nano <file name> ( to edit the file )

git status
git add .
# these commands to add the files 

git commit -m " file commited"
git push -u origin main 
# to push the filr to the repo

git checkout -b master
git checkout branch -m main
git checkout feature-branch
# these are used to change the branches

git stash

git merge the feature-branch
# to merge the branch feature-branch with other main branch

git tag v1.0
git tag 
git push tag v1.0
# used to name the tag ( insteed of committing full name useage of tags is done ) and also to push the tag

git log --oneline
# to track the history in git bash
git revert<commit id>
git push origin main
