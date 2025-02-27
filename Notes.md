git init ------------used for once when you start working with git on new folder
git status-----------this is used to check thr status of the folder that all the files are part of git or not.


if you are going to add any new file in the folder then check with got status and it will  show you untrack file. To /make this part of git you need to perform git add and git commit


git add--------------when you are adding the file for the first time as part of git repository
git add .
git add *

git commit -m "initial commit"


git commit -a -m "message"--------------this will only be used for those files who are already a part of your git




commands for github repo to push data. perform the given commands for the first time only
git branch -M main
git remote add origin https://github.com/ravikumar1602/gitpractice.git
git push -u origin main


after this to upload or push the data in the github respository always use this command
git push