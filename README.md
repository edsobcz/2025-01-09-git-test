# 2025-01-09-git-test
- `git clone`: does a one-time download from github to your local computer
  - make sure the directory you are cloning is not already a git repository (nesting is annoying)
- `git status`: tells you everything you need to know about your github repo (including whether you're in a github repo)
- `git add <FILE>`: adds the file to the staging area and readies it for committing
- `git commit -m "MESSAGE"`: commits the added files with the commit message in quotes
- `git push <WHERE> <WHAT>`: pushes changes from local machine to remote (WHERE) using the branch (WHAT), will often be origin main
- `git pull <WHERE> <WHAT>`: brings chnages from remote to local machine
