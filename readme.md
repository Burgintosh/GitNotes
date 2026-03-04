# Commands
```bash
git init                                    # Turns the working directory into a git repository
git add <fileName>                          # Add a specific file to the stage
git add -A                                  # Add all files not on the gitignore list
git commit -m '<msg>'                       # Commit all stages files with a message


git status                                  # Hints what to do next / where you are at
git log                                     # Shows the log of recent commits (q quits out of that view)
git checkout -b <branchName>                # Creates a new branch
git checkout <branchName>                   # Switches branches

git merge <branchName>                      # Merges the specified branch into current branch

git remote add origin <url>                 # Sets up the remote repository as the default on the remote (Use HTTPS not SSH)
git remote -v                               # Shows the available branches on remote
git push origin <branchName>                # Pushes localname branch to the remotename repo

git tag -a '<versionNumber>' -m '<msg>'     # Adds a tag to the current commit
git push origin --tags                      # pushes tags to remote
git pull origin <branchName>                # Fetches and merges remote branch to active branch
git fetch origin <branchName>               # Gets the meta data about a branch to your local
```