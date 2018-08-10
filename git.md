## git notes

### Rebase from master

If already on working branch, with commits pushed to origin  
`git fetch && git rebase origin/master`  
`git push branchname -f`


### Clone Repo with token (allows cronjobs etc. to push to remote)

Get token from github>settings>developer settings>personal access tokens.

`git clone https://ACCESS_TOKEN0@github.com/mikeyford/REPO_NAME.git`