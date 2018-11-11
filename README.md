# git commands
## git init
### git init is used to initialised  folder
## git remote add origin https://github.com/vineeta-chauhan/testing-.git
### it specify the origin url
## git add file name
###  it only add the file which we were give a file name
##  git add --all
###  it  add all the file
## git commit
### it commited the file
## git status 
###  this command define that how many file are tracked or untracked.
## git log
###  it defines the log of repo
##  git commit -m "commit to change in branch"
###  it is used to commit a current code with the specific message
## git branch
### it shows how many branch u are nd which  branch presently u are
## git checkout -b branch-name
#### to create a new branch
## git push -u origin branch-name
### to push code when local branch is not available on remote repository(to create that local branch on remote repo)
## git push origin branch-name
### to push code when local branch is available
## git branch -d branch_name (-d option stands for --delete)
### To delete the local GIT branch 
## git branch -D branch_name (-D option stands for --delete --force)
### deletes the branch regardless of its push and merge status
### 
##  git push origin --delete test
### used to delete branch from remote repo as well as from local, if you are not in that branch which you want to delete( in this case it delete branch from local as well as from remote repo) but if you are in same branch which you want to delete then it only delete frome remote not from local
## git branch -m new-name
### If you are on the branch you want to rename
## git branch -m old-name new-name
### If you are on a different branch:
## Rename local as well as remote branch by terminal
```git
git branch -m old_branch new_branch       # Rename branch locally    
git push origin --delete old_branch       # Delete the old branch    
git push --set-upstream origin new_branch   # Push the new branch, set local branch to track the new remote
```
## You can use git-credential-store to store your passwords unencrypted on the disk, protected only by the permissions of the file system.

## Example
```git
$ git config credential.helper store
$ git push http://example.com/repo.git
Username: <type your username>
Password: <type your password>

[several days later]
$ git push http://example.com/repo.git
[your credentials are used automatically]
```
=======
## command to initialised git git init
### to configure repo to remote
