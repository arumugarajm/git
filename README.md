# creating this readme file for git 
### Basics: <br>
- Git is a version control system (VCS) <br>
- Git helps you keep track of code changes.
- Git is used to collaborate on code.
### Types of VCS:
- Local VCS
- Centralized VCS
- Distributed VCS

### VCS Tools:
- Git
- SVN
- TFS
- Bazaar, etc.
### Features 
- Works on a distibuted system
- compatible with all OS
- Allow for non-linear development
- Branching
- Fast and flash
- Reliable

### Git workflow
![](arumugarajm/Images/git.jpg)
[<src = "arumugarajm/Images/git.jpg">]


git --version -> check the version. <br>
mkdir **file name** ->makes a new directory. <br>
cd **directory** ->changes the current working directory. <br>
git clone **url_of_github** -> clone remote repo to our local system. <br>
git init **file_name** -> initialize the file for version control system (VCS). <br>

git status -> displays the state of the working directory and the staging area. <br>
git add **file_name** -> To stage the file/ the file is ready to track changes. <br>
git add --all or git add . or git add -A -> To add all the files to track. <br>
git rm --cached **file_name** -> To make the normal file, i.e, not staging the file. <br>
git commit -m "write here what changes you made" -> after init, add store the file in local repo. here m stands for message. <br>

git log ->To view the history of commits for a repository. <br>
git log --oneline -> To only see the changes. <br>

git command -help ->See all the available options for the specific command. <br>
git help --all ->See all possible commands. <br>

git branch -> To check the number of branches. <br>
git checkout **branch_name** ->  To set branch. <br>
git checkout -b **branch_name** -> To create and swith to that new created bracnch. <br>
git switch **branch_name** ->To swithch the branch. <br>

git merge **branch_name** -> To merge branche. <br>

git remote add origin **url_of_github_repository(remote)** ->manually add the remote repo. <br>
git remote -v -> To check the reomote repos. <br>
git fetch origin ->Tracked history to our local repo. <br>
git pull origin<br>
git push origin **branch_name** ->Push a Branch to GitHub. <br>

git push origin -> Push the changed file to github/remote repo .<br>

