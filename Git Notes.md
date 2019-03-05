#### Git Notes #####
You will have a Repository on your machine, then you will "push" it to the Repository
Make a "commit" to update your code, can always revrt back when needed.
Putting into "staging" are before commiting.

#### Basic Commands ######
git init   //initalize a local Repository (go to your folder where you have your code with your terminal)
git add <file>  //Add files to index
git add . <file type> ex html  //this will add every html file in the folder to the Repository
git add . //This adds every file in the folder
git status  //check what is in the staging area
git rm --cached<file> //removes file from the staging area
git commit   //Takes everything in the staging area to the Repository
git push //takes local Repository and puts it on github
git push -u orgin master
git pull  //Pull latest version
git clone //copies Repository to machine
git branch <name of branch> //to create a branch
git checkout <name of branch>  //to switch to another branch
git merge <file>  //merge branch to master
git config --global user.name 'your name'
git config --global user.email 'your email'
.
#### How to use Git Ignore ######### (folder to not include in Repository)
-----Bash------
touch .gitignore
touch .log.txt (to not include)
----Atom--------
go into gitignore and type log.txt (all you have to do it type the file name)
you can also add entire directories
as you can see.

##### Git Bash #############
Right click on folder that contains your code. "Git Bash"
touch index.html  //This creates a html file
touch app.js  // This creates js
-------Open up Atom---------(add this folder as project)

NOW, you want to initalize this folder as a Git Repository
------------------------------------------------------------
git init   //This will create a .git folder in your project
git add index.html  //this adds to Repository
git status //check what is in the staging area
git commit  //this will open up vim editor
--------Vim Editor----------------
Click 'i' to go into inser mode and type. ex inital commit
to get out push esc button and pres :wq enter
--------------------------------------
BETTER WAY TO commit
git commit -m 'initial commit'
---------------------------------------------
############ Git Branch ##########################
git branch <name of branch> ex git branch login
git checkout login  //to switch to the branch you created
############## Git Merge #############################
git merge <file name>
-----vim editor-------
press I, then enter commit message
press esc :wq enter
