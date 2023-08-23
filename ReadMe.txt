╭━━━╮╭╮╱╭━━━╮╱╱╱╱╱╱╱╱╱╱╱╱╱╱╱`╱╱╭╮╱╱╱╭╮
┃╭━╮┣╯╰╮╰╮╭╮┃╱╱╱╱╱╱╱╱╱╱╱╱╱╱╱╱╭╯╰╮╱╭╯╰╮
┃┃╱╰╋╮╭╯╱┃┃┃┣━━┳━━┳╮╭┳╮╭┳━━┳━╋╮╭╋━┻╮╭╋┳━━┳━╮
┃┃╭━╋┫┃╱╱┃┃┃┃╭╮┃╭━┫┃┃┃╰╯┃┃━┫╭╮┫┃┃╭╮┃┃┣┫╭╮┃╭╮╮
┃╰┻━┃┃╰╮╭╯╰╯┃╰╯┃╰━┫╰╯┃┃┃┃┃━┫┃┃┃╰┫╭╮┃╰┫┃╰╯┃┃┃┃
╰━━━┻┻━╯╰━━━┻━━┻━━┻━━┻┻┻┻━━┻╯╰┻━┻╯╰┻━┻┻━━┻╯╰╯

╱╱╱╱╱╱╱╱╱╱╱╱╱╱╱╱╱╱╱╱╱╱╱╱╱╱╱

This is how to use git by Ian bezerra

-----// Main //-------------

-> Git is a version managing and colaboration tool 
it is very usefull and your codes can be posted on github!!!




-----// Git Basics //-------------

$ git init
   - Init the git repo 

$ git add [Name_Of_FILE] 
   - Adds file to be comiited

$ git add .
  - To add all files

$ git status 
  - Shows files that are pending to be commited 

$ git commit -m "name of the commit"
  - Commits changes to the main branch

-----// Git Branches //-------------

-> Now Imagine that just like in a tree a branch can go off the main 
one, we can use branches to test and develop features or more.

        ___ Master-------(Colapses)------ Master(But with changes!!)
master <___ BranchB-----^

+ This are the main branch commands

$ git checkout -b name_of_the_branch
  Create new Branch

$ git merge name_of_the_branch_to_pull 
  - Pulls into the branches (current branch)



-----// Setting up users in github //-------------

$ git config --global user.name "[User_Name]"
  Set up user name

$ git config --global credential.helper store 
  - Remembers password

$ git clone <url> - clones repo of specified URL 

-----// Pushing to github //-------------

$ git remote add origin https://github.com/IdhcbIan/tets.git
 - Get remote origin 

$ git [Branch] -a     
  - lists branches remote and local

$ git push -u origin [Branch] 
  - pushes branch
  



