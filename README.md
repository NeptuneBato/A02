# Git tutorial

The first step to using Git is to download and install from the official website.   
You can create a repository using the command "git init"
From there you can start adding and coding files like normal. Once you are finished, you need to add them to git.  
Git status shows you which files have been changed.  
Git add \[file] will add the files you want to be committed.  
Git commit -m "A commit message" will be what saves those changes.  
Git push origin "branch-name" will copy your commits made on local to your remote repository.  
Git pull origin "branch-name" will copy your commits made on remote to your local repository. 


# Github Tutorial
Github is a website to externally host your repositories.  
To connect your local repository to your Github, you can use the command "git remote add origin (your project's github url)"  
When you view your project on github, you can see all the files and directories there. Clicking on one allows you to see its history. There is also a button that lets you switch which branch you're viewing.  
Github allows you to merge branches through the "Pull Requests" tab.



# Definitions

**Branch** - A branch is a unique version of the project's codebase. A branch can have files added, removed, or modified without affecting another branch.  

**Clone** -A copy of a repository into a new directory

**Commit** - Records changes made to a repository  

**Fetch** - Git Fetch retrieves all the new commits from the remote branch and brings them to local WITHOUT merging them

**GIT**  - Git is a version control system that allows you to track changes to your code and see historical versions of it.

**Github**  - Github is a website where you can externally store your git repositories.

**Merge** - Merge takes changes committed into one branch and adds those changes to the selected branch

**Merge Conflict** - When you make an edit in one branch, a different edit to the same file in a different branch, and try to merge them together, there is a conflict where you must choose which edit to save.

**Push** - Git Push is when you send the changes you made on your local directory to the remote directory.

**Pull** Git Pull retrieves all the new commits from the remote branch and brings them to local WITH a merge

**Remote** - Remote is an external place to host your directory, such as Github.

**Repository** - A repository is where all the files and branches of your project are.  


# References
[https://www.geeksforgeeks.org/git/what-is-git/](url)
