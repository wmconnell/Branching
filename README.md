## Git and Git Branching Cheat Sheet

### Basic commands
* `git init` - initialize current directory with repository
* `git add .` - add all new or changed files in current directory to git index, staging them for commit
* `git commit -m "some message"` - commit staged changes to local repository

### Info commands
* `git status` - show status of current working directory
* `git log` - list commit history
* `git log --oneline` list commit history (compact)

### Branch commands
* `git branch` - list local branches, highlight current branches
* `git branch branchName` - create branch `branchName`
* `git checkout branchName` - switch to branch `branchName`
* `git checkout -b otherBranch` - switch to branch `otherBranch`, creating it if it doesn't exist
