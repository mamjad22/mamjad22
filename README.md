# mamjad22
step1: created a repo on github account
step2: created a same name folder in local in your pc.
step3: create any file in that folder for versioning.
eg: echo "# git-demo-again" >> README.md
step4: initialize git in your local folder
eg: git init
step5: to check the status (untracked - red/track file - green) of your github repo eg: git status
step6: to move file from untrack fiiles to track files
eg: git add . OR git add -A (add all file into tracking)
eg: git add <file-name> (add only specific file to tracking)
eg: git add *.csv (add only specific files)
let suppose you want to move file from tracking to untracking again (tick wapis krdo)
git rm --cached <file>
step7: to make file ready to to push we do commit (send to airport)
eg: git commit -m "any meaningful comment"
step8: to rename the branch from master to main
eg: git branch -M main
step9: to set the origin for your local repo for githubn repo (travelling destination setting)
eg: git remote add origin https://github.com/aiwithqasim/git-demo-again.git
step10: to push file from local to github repo (in lfight from khi to isl)
eg: git push -u origin main
second time
git add .
git commit -m "any message"
git push

second time
git add .
git commit -m "any message"
git push

second time
git add .
git commit -m "any message"
git push


