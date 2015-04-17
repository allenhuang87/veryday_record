 #how to push local repo to github
 #follow the below command
git init
vim README.md
git add .
git commit -m "add readme.md"
git remote add origin https://github.com/allenhuang87/everyday_record.git
git branch -a
git push -u origin master
 #the system will ask you to input the username and password on github
 #and will remind you that there is no git repo on github for we write the wrong git repo

 #try to add a correct git repo
git remote add origin https://github.com/allenhuang87/veryday_record.git
git push -u origin master
git remote add origin https://github.com/allenhuang87/veryday_record.git
 #we must delete the wrong repo
git remote rm origin
 #try to add it again
git remote add origin https://github.com/allenhuang87/veryday_record.git
git push -u origin master
git branch -a
 #successful

