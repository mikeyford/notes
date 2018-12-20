## git notes

### Rebase from master

If already on working branch, with commits pushed to origin  
`git fetch && git rebase origin/master`  
`git push branchname -f`

or the nice, easy way in magit:
`y` show refs, (see if you're behind master and how far)
'r' rebase onto:
`e` elsewhere, choose origin/master
force push branch with lease


### Clone Repo with token (allows cronjobs etc. to push to remote)

Get token from github>settings>developer settings>personal access tokens.

`git clone https://ACCESS_TOKEN0@github.com/mikeyford/REPO_NAME.git`


### Tidy up branchs that have been merged

Delete all local branches that have been merged
`git branch --merged | egrep -v "(^\*|master|dev)" | xargs git branch -d`

Get rid of old remote tracking branches
`git remote prune origin`


### Squash commits

e.g for last three commits

`git reset --soft HEAD~3 &&`
`git commit`

then force push with `git push origin branchname -f`
