# gitNotes 

```
git init											# converts current folder to a git repo
git add <filename>									# stages one file
git add -A											# stages all non-ignored files
git commit -m '<message>'							# commits with message
git checkout -b <branchName>						# creates new branch and places user in that branch
git checkout <branchName>							# places user in that branch
git status											# informs user of current branch and uncommited changes or issues
git merge <branchName>								# merges commits from inputed branch
git log												# shows commit history
git reflog											# shows last 15 git actions
git blame											# shows history of commits with users
git diff
git reset --hard <optionalID>						# reverts to pervious version
git tag												# add tag to current commit
git tag -a '<semversion>' -m '<message>'			# list all tags
git remote add <origin> <url>						# one time connect to gitHub
git push origin <branch>							# sync local repo to remote repo
git pull origin <branch>							# sync remote repo to local repo (merge)
```

