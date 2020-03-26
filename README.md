## Git Branching

### Basic Commands

* 'git init' - Initialize local git repo
* 'git add' - Stage local working directory for commit
* 'git commit' - Commit staged files to local repo
* 'git log' - Show commit history
* 'git status' - Show status of repo
* 'git rm --cached fileName' - Remove fileName from commit index
* 'git log --oneline' - Show commit history (Compact)


### Branching Commands

* 'git branch' - List local branches, highlight checked-out branch
* 'git branch branchName' - Create branch 'branchName'
* 'git checkout branchName' - Move to branch 'branchName'


### Remote Repository commands

* 'git remote add origin remoteRepoUrl' - Link local repo to 'remoteRepoUrl'
* 'git pull origin master' - Pull 'master' branch content from remote origin into current local branch
* 'git push origin master' - Push current local branch to 'master' branch of remote origin
* 'git push origin branchName' - Push local branch 'branchName' to origin
