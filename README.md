# gitcommands


Here's a list of important Git commands that cover a range of basic to advanced operations:

Basic Commands=>
git init - Initializes a new Git repository.
git clone <repository> - Clones a remote repository to your local machine.
git status - Shows the status of changes in the working directory and staging area.
git add <file> - Stages changes for the next commit.
git commit -m "<message>" - Commits staged changes with a message.
git log - Shows the commit history.
git diff - Displays changes in the working directory that are not staged.
git diff --staged - Shows changes between the staged files and the last commit.
git reset - Unstages changes but keeps them in the working directory.
git rm <file> - Removes files from the working directory and stages the removal for the next commit.


Branching and Merging=>

git branch - Lists all branches or creates a new branch.
git branch <branch-name> - Creates a new branch.
git checkout <branch-name> - Switches to the specified branch.
git checkout -b <branch-name> - Creates and switches to a new branch.
git merge <branch-name> - Merges the specified branch into the current branch.
git rebase <branch-name> - Re-applies commits on top of another base tip.


Remote Repositories=>

git remote -v - Lists the remote repositories and their URLs.
git remote add <name> <url> - Adds a new remote repository.
git fetch <remote> - Fetches changes from the remote repository but does not merge them.
git pull <remote> <branch> - Fetches and merges changes from the remote repository.
git push <remote> <branch> - Pushes commits to the specified branch of the remote repository.
git remote remove <name> - Removes a remote repository.


Reverting and Resetting=>

git revert <commit> - Creates a new commit that undoes the changes of the specified commit.
git reset <commit> - Resets the current branch to the specified commit, optionally altering the staging area and working directory.
git stash - Saves changes in a temporary stash to clean the working directory.
git stash pop - Applies the latest stash and removes it from the stash list.


Tagging=>

git tag <tag-name> - Creates a new tag pointing to the current commit.
git tag -a <tag-name> -m "<message>" - Creates an annotated tag with a message.
git push <remote> <tag-name> - Pushes the tag to the remote repository.


Configuration=>

git config --global user.name "<name>" - Sets the global user name.
git config --global user.email "<email>" - Sets the global user email.
git config --list - Lists all the configuration settings.
These commands provide a solid foundation for working with Git in various scenarios, from basic operations to more advanced tasks.