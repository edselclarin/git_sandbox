# git_sandbox

Test bed for git operations.

Run the following commands with your favorite shell program. (cmd, powershell, bash, git bash, etc.)

### Create a Repository
1. Create a new repository on github.com.
2. Checkmark "Initialize this repository with a README".
3. Click "Create repository" button.

### Clone the Repository on your Local Drive
~~~~
    git clone <repository URL>
~~~~

Your local repo is now ready for your changes.

### Add Files to a Repository

1.  Create new branch for work.
~~~~
    git branch <new branch name>
~~~~
2. Confirm current branch.
~~~~
    git branch
~~~~
3. Switch to new branch.
~~~~
    git checkout <new branch name>
~~~~
4. Add files to the new branch.  Set <filename> to "." for resursive add.
~~~~
    git add <filename>
~~~~
5. Confirm which files have been added.
~~~~
    git status
~~~~
6. Commit changes.
~~~~
    git commit -m <commit message>
~~~~
7. Push new branch along with changes upstream.
~~~~
    git push --set-upstream origin <new branch name>
~~~~

### Update Local Repository
~~~~
    git pull
~~~~

### View Changes in the Current Branch
~~~~
    git diff
~~~~

### Commit and Push Changes Upstream
1. Switch to a new branch, and set it up to track the remote branch from origin.
~~~~
    git checkout --track origin/<new branch name>
~~~~
2. Add files to commit.
~~~~
    git add <file1> <file2> ...
~~~~
3. Commit changes.
~~~~
    git commit -m <commit message>
~~~~
4. Push upstream.
~~~~
    git push
~~~~
