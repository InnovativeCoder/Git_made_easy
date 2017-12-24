# Git_made_easy 
 
 <img align="center" src="http://valuebound.com/sites/default/files/2015-12/Beginners_guide_setting_up-git.jpg">
  
_1._ Initializing the repository
``` 
$ git init .
```
_2._ To show the status of your repository
``` 
$ git status
```
_3._ To add files for staging before commiting
```
$ git add <filename>
```  
_4._ To commit the changes made 
```
$ git commit -m"<type the message explaining what you have done>"
```
_5._ It will show all the commits and history of the repo
```
$ git log 
```
_6._ It will show all the commit 
``` 
$ git log --oneline ()
```
7. will make a branch of the git repo os that you can work on your own and then merge later on
```
$ git checkout -b <branch name> 
```
8. argument is the branch name you want to merge in your current branch
```
$ git merge <arguement> 
```
9. for getting a graphical visualisation of the git tree
```
$ git log --oneline --color --graph --decorate
```
10. add all local repo to your GitHub repo
```
$ git remote add origin <url of the repo> 
```
11. all the branches get pushed into GitHub repository
``` 
$ git push -all 
```
12. will tell all the tech and pull history of the repository
```
$ git remote -v
```
