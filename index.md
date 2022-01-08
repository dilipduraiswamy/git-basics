## Git Commands

### Check git is installed
``` git version ```
### Help
``` git --help ```

### Git configure

#### Config username 
``` git config --global user.name "REPLACE_YOUR_GIT_USERNAME" ```
#### Config emailid 
``` git config --global user.email "REPLACE_YOUR_GIT_EMAIL_ID" ```
#### Config coloring for terminal 
``` git config --global color.ui auto ```
#### List all configurations 
``` git config -l ```


### Initialize a directory as git directory
``` git init . ```
### Status of working directory 
``` git status ```
### Add/stage files to local git 
``` git add FILE_NAME ```
### Remove/unstage files which was added to local git 
``` git rm --cached FILE_NAME ```
### Add/stage all files to local git from current folder
``` git add . ```
### Remove/unstage all files which was added to local git 
``` git rm -r --cached . ```
### Add all directories to local git 
``` git add -A ```
### Commit files to local git
``` git commit -m "MESSAGE_TO_COMMIT" ```
### Get commit history's 
``` git log ```
### Get log with limited data 
``` git log --oneline ```
### Get more info about particular commit 
``` git show "COMMIT_ID" ```
### Get changed differences 
``` git diff ```
### Ammend commit/rename last commit 
``` git commit --amend -m "MESSAGE_TO_COMMIT"```
### Push with branch 
``` git push -u origin BRANCH_NAME ```
### Push 
``` git push ```
### Check current branch 
``` git branch ```
### Check remote branch 
``` git branch -r ```
### Show all branch's 
``` git branch -a ```
### Create branch 
``` git branch BRANCH_NAME ```
### Switch branch 
``` git checkout BRANCH_NAME ```
### Switch to previous branch 
``` git checkout - ```
### Create branch and switch 
``` git checkout -b BRANCH_NAME ```
### Delete branch 
``` git branch -d BRANCH_NAME ```
### Merge changes between branches i.e it will be merged to current working branch 
``` git merge BRANCH_NAME```
### Rebase branch 
``` git pull -r origin REBASE_BRANCH_NAME ``` i.e. main
### Rebase after conflict resolve 
``` git rebase --continue ```
### Force push after conflict and rebase done 
``` git push -f ```


