# 343HW_1
Assignment 1 for CIS 343

**************
*git cmd list*
**************

git init : Used to initialize a git repository

git status : Displays the current state of the project. Displays information such as what files 
              area and are not tracked, changes to be commited, ect.
              
git add file.txt : This will make the repository start tracking changes made to file.txt

git commit : Moves files from the staging area the to be stored into the repository.

git commit -m "What in Oblivion is that!?" : Adds the message in quotes along with the commit. The 
                                              message idealy explains the commit.

git add *.txt : Uses a wild card to move all the files that end in .txt from the staginng area 
                 to be stored into the repository.
                 
git log : This produces a "journal" of all the changes that have been commited to the repository

git remote add origin URL : This creates a remote repository with name origin and URL

git push -u origin master : Make pushes to the default local branch of the remote repository
                            origin. -u tells git to remember the parameters.
                            
git pull origin master : pulls down any changes made to the remote repository.

git diff HEAD : Tells you what is different in the repository from our last commit.

git diff --staged : Tells you what is different in the staging area from the last commit.

git reset files : This will unstage files. Meaning that it will remove files from the staging area.

git checkout -- file : this will change files back to there previous state. (Staged or unstaged)

git branch branch_name : this will create a new branch with the name branch_name

git checkout branch_name : Checkout can be used to swithc branches like this

git rm '*.txt' : removes all the text files

git marge branch_name : merge changes from a branch to the master branch. In other words you commit 
                          the changes made in one branch to another branch.
                          
git branch -d branch_name : deletes branch branch_name.

git push : moves everything form your remote repository to the local repository.

                          
                            

                                              
                                        


                                       



