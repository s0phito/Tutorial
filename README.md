# Tutorial
<p>
Github Commands:<br>
git - check if we have github<br>
git -version - check version of our github<br>
git config -global user.name "Your Username"<br>
local repository - located on your machine<br>
  first commit our codes to our local repository<br><br>
  then push it to the remote repository<br>
  git add . - to index the changes<br>
  git commit -m "the first commit"<br>
  git status - branch should be updated<br>
  git push origin master - push change to remote repo<br>
    master - the branch<br>
git clone<br>
steps for committing a new change:<br>
  make changes to file<br>
  type in command line:<br>
    git status<br>
      to find the differences<br>
    git add .<br>
    git commit -m "commit title"<br>
    git status<br>
      should say "nothing to commit"<br>
    git remote add origin "url of newRepo"<br>
      add change to a new repo<br>
    git pull origin master - remote repository<br>
repo:<br>
  can clone existing remote repo or init creating repo<br>
 git clone - gets existing repo from remote<br>
 git init - create own repo in local<br>
  copy url<br>
  right click in directory<br>
  click git bash<br>
  type in command line: git clone "url"<br>
 how to check if we have .git format:<br>
   cd "Project Name"<br>
   ls --all<br>
    list every file - used to check if we have .git<br>
 git checkout -b "branch name" - create a new branch named branch name
 git checkout master - switched to branch 'master'
  git checkout "branch name" - switch to a branch
 git add .
  git commit -m "commit for new branch"
  git push origin "branch name"
  git add *.txt - add everything with the txt format
  git commit -m "txt format"
  git push origin "branch name"
  create new file called "3.txt"
  git add 3.txt
  git commit -m "3 txt"
  gt push orgin "branch name"
  
  Github website:<br>
    Trace commits<br>
 </p>
