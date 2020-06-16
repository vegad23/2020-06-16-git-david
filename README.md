# 2020-06-16 Git

# Local 
- `git init`: create a git repository in the current directory
- `git status`: tells you what is going on
- `git add`: add to staging area
- `git commit`: commit to command
- `git add <FILENAME>`: adds <FILENAME> to the staging area (aka index)
- `git log`: shows the history of commit we have done
- `git log --oneline`: short version of git log
- `git diff`: shows the difference between last known git state
- `git checkout`: reverts the file from <HASG> back to current state
- `git diff HEAD~1 <FILE>`: compares current to last state
- `git checkout <HASH>: revert entire folder to current state
- `HEAD`: where you are looking at 

## Remotes

-`git push <where> <what>`: takes the master branch on local computer and pushes it to origin location
- `git remote add <name> <url>`: gives remote URL short name
- `git pull <where> <what>: takes the remote master branch and brings it to local master branch
