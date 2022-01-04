# git-basic-commands

- git version ( git --version ) 
- git help ( git --help )

### Basic git commands
- Initialize a directory as git directory ( git init . )
- Status of working directory ( git status )
- Add/stage files to local git ( git add FILE_NAME )
- Remove/unstage files which was added to local git ( git rm --cached FILE_NAME )
- Add/stage all files to local git from current folder( git add . )
- Remove/unstage all files which was added to local git ( git rm -r --cached . )
- Add all directories to local git ( git add -A )
- Commit files to local git( git commit -m "MESSAGE_TO_COMMIT" )
- Get commit history's ( git log )
- get more info about particular commit ( git show "COMMIT_ID" )
- get changed differences ( git diff )
- Ammend commit/rename last commit ( git commit --amend -m "MESSAGE_TO_COMMIT")
- 

### git configure
- Config username ( git config --global user.name "REPLACE_YOUR_GIT_USERNAME" )
- Config emailid ( git config --global user.email "REPLACE_YOUR_GIT_EMAIL_ID" )
- Config coloring for terminal ( git config --global color.ui auto )
- List all configurations ( git config -l )
