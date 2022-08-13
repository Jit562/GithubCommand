Git setting user name and email id:

Step 1 :- 

git config --global user.name "Your Name"

git config --global user.email "youremail@yourdomain.com"

step 2:-

git config --list

step 3 :-  (create ssh key )

ssh-keygen or ( ssh-keygen -t rsa -b 4096 -C "email" )

ls -a

cd .ssh

ls

cat id_rsa_pub

step 4:-

git init

got project path 

step 5 :- 

git config core.useBuiltinFSMonitor true

  enter

git config core.fsmonitor true



step 6 :- 

git init 

git add . , or git add -A , git add one file name

or

git add <File_Name>  {{For Single File}}

git add .            {{For all the files in current Directory}}





first time move project 

git remote add origin git@github.com:"Username_on_github"/"Repository_Name"

example: - git remote add origin git@github.com:XYZ/project.git

check remote

git remote -v


Remove origin

git remote rm origin


git status

git commit -m “first commit”

git status


step 7:- (first time project push in gitlab or github )
   

git remote add origin “go to gitlab project and copy ssh clone path paste here “


step 8:- 

finaly move the code: 

git pull --rebase origin master 

git push origin master 


git push -u origin master or git push -f origin master

step 9 :-

git log

git log –online

git log stat

git log –stat

git log patch

git log s

git pull

git push origin master

step 10 :-

create new branch from master branch

git checkout -b (branch name)

or git branch brnchname

git checkout branchname

delete branch

git branch -d Branch_name

Update and Merge.

git pull

git merge <branch>

git add <filename>

git diff <source-branch> <target-branch>

replace local change

git checkout --filename 

git fetch origin

git reset --hard origin/master




step 11 :- ( how to clone )


copy master branch or any branch clone ssh file path and paste your terminal gitbash.



step 12:- (Create file and remove file)

touch filename

rm filename

example:-

touch README.md

rm README.md









