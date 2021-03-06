## Tutorial

Github Commands:

git - check if we have github <br>
git -version - check version of our github <br>
git config -global user.name "Your Username" <br>
git pull --help - show description and arguments of the command "pull" <br>
local repository - located on your machine <br>
git COMMAND --help - get help with COMMAND <br>

1.  first commit our codes to our local repository
2.  then push it to the remote repository
3.  git add . - to index the changes
4.  git commit -m "the first commit"
5.  git status - branch should be updated
6.  git push origin master - push change to remote repo
7.  master - the branch
8.  git clone

**Steps for committing a new change:**

1.  make changes to file
2.  type in command line:
3.  **git status**

1.  to find the differences
4.  **git add .**
5.  **git commit -m "commit title"**
6.  **git status**

1.  should say "nothing to commit"
7.  **git remote add origin "url of newRepo"**

1.  add change to a new repo
8.  **git pull origin master** -  download remote content and immediately attempt to change the local state to match that content

**Repositories**

repo - can clone existing remote repo or init creating repo<br>
git clone - gets existing repo from remote<br>
git init - create own repo in local<br>

### How to clone repo

1.  copy url
2.  right click in directory
3.  click git bash
4.  type in command line: git clone "url"

**How to check if we have .git format:**

1.  cd "Project Name"
2.  ls --all
3.  list every file - used to check if we have .git&nbsp;
<br><br>
### How to create new branch and merge it
1.  git checkout -b "branch name"&nbsp;
a.  create a new branch named branch name&nbsp;
2.  git checkout master - switched to branch 'master'&nbsp;
3.  git checkout "branch name" - switch to a branch&nbsp;
4.  git add .
5.  git commit -m "commit for new branch"&nbsp;
6.  git push origin "branch name"&nbsp;
7.  git add *.txt - add everything with the txt format&nbsp;
8.  git push origin "branch name" 
a.  create new file called "3.txt"&nbsp; <br>
9.  git add bob.txt 
10.  git commit -m "3 txt"&nbsp;
11.  git push origin "branch name"&nbsp;
12.  git checkout master
13.   git merge "branch name"

commit identifying numbers - indicates that the in this commit, the remote repo has changed

### Github website:

Trace commits
