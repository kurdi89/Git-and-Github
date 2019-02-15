### init
# to initilize the git :
git init
# to add to the staged changes
git add <file>
git add . 

# to commit changes
git commit

### remote repos : 
git push 
/ push to a remote repo (github, bitbucket), you have to add credi or SSH keys 
git pull 
/ pulls lateset version from remote
git clone
/ will copy the repo into the current dirctory

### add username and name 
git config --global user.name 'Abdul kurdi'
git config --global user.email 'kurdi.89@hotmail.com'

## to add a file : 
git add filename.ext
git add index.html
git add *.html
git add .

## to know the status : 
git status // will be used a lot 

## to remove from the staging area : 
git rm --cached filename.ext
git rm --cached index.html


## to enter staging mood : 
git add . 
// commit : 
git commit -> i -> :wq 
or 
git commit - 'my comments are : changed app.js'

### to git ignore : 
# creates a file thats ignores what files to be commited or include (example : logs files )
# create a .gitignore file using touch .gitignore and inside it add files or /directory name to be ignored 

# after adding all files you can commit with new -m 'comment'
git  commit -m 'your comments'



### branching
# adding a branch : 
git branch <name of barnch>
git branch login

# switching to a branch: 
git checkout <name of the branch>

# switching back to the master branch ():
git checkout master

# merging a branch to the master 
git merge login