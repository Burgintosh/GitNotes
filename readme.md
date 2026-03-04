# Commands

git init : Turns the working directory into a git repository
git add <filename> : Add a specific file to the commit list
git commit -m '<msg>' : Commit all added files with a message
git -A : Add all files not on the gitignore list

git status
git log : Shows the log of recent commits
git checkout -b <branchname> : Creates a new branch
git checkout <branchname> : Switches branches

git merge <branchname> : Merges the specified branch into current branch

git remote add origin <url> : Sets up the remote repository as the default on the remote
git remote -v : Shows the available branches on remote
git push origin <branchname> : Pushes localname branch to the remotename repo