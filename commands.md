# Git Commands:

## Directory Management
- `mkdir git-for-devops` - Create a directory named `git-for-devops`
- `cd git-for-devops` - Change to the `git-for-devops` directory
- `cd ..` - Move up one directory level
- `mkdir github` - Create a directory named `github`
- `cd github` - Change to the `github` directory

## Git Initialization and Cloning
- `git init` - Initialize a new Git repository
- `git clone <github url>` - Clone a remote repository

## Viewing Files
- `ls -la` - List all files, including hidden files, in long format
- `ls` - List directory contents

## File Creation and Editing
- `vi Hello` - Create or edit a file named `Hello`
- `vi nibbi` - Create or edit a file named `nibbi`
- `vi nibba` - Create or edit a file named `nibba`
- `vi README.md` - Create or edit the README file
- `touch nibba nibbi` - Create empty files named `nibba` and `nibbi`
- `touch nibbu` - Create an empty file named `nibbu`
- `vi branching` - Create or edit a file named `branching`

## Git Status
- `git status` - Show the working tree status (repeated at multiple steps to verify changes)

## File Removal
- `rm Hello` - Remove the file `Hello`
- `rm nibbi` - Remove the file `nibbi`

## Staging and Unstaging Files
- `git add nibbi` - Add `nibbi` to the staging area
- `git add nibba` - Add `nibba` to the staging area
- `git add README.md` - Add `README.md` to the staging area
- `git add branching` - Add `branching` to the staging area
- `git rm --cached nibba` - Unstage `nibba` from the index

## Committing Changes
- `git commit -m "adding nibba nibbi"` - Commit changes with the message "adding nibba nibbi"
- `git commit -m "added new changes to nibbi"` - Commit changes with the message "added new changes to nibbi"
- `git commit -m "added nibba changes"` - Commit changes with the message "added nibba changes"
- `git commit -m "added nibbu"` - Commit changes with the message "added nibbu"
- `git commit -m "added readme"` - Commit changes with the message "added readme"
- `git commit -m "added some changes"` - Commit changes with the message "added some changes"
- `git commit -m "some changes in branching"` - Commit changes with the message "some changes in branching"

## Configuring Git
- `git config --global user.name "suraj5sky"` - Set the global username
- `git config --global user.email "surajec12@gmail.com"` - Set the global email address

## Viewing Logs
- `git log` - View commit history
- `git log --oneline` - View a concise commit history

## Branch Management
- `git branch` - List all branches
- `git checkout -b dev` - Create and switch to a new branch named `dev`
- `git checkout master` - Switch to the `master` branch
- `git checkout dev` - Switch to the `dev` branch
- `git checkout -b from-dev` - Create and switch to a new branch from `dev`
- `git checkout -b from-master` - Create and switch to a new branch from `master`
- `git checkout -b staging` - Create and switch to a new branch named `staging`
- `git switch dev` - Switch to the `dev` branch

## Remote Repository Management
- `git remote -v` - Verify the remote URL configuration
- `git remote set-url origin http://token@github.com/username/foldername.git` - Update the remote URL to use HTTP with a token
- `git remote set-url origin git@github.com:username/foldername.git` - Update the remote URL to use SSH

## Pushing and Pulling Changes
- `git push` - Push committed changes to the remote repository
- `git pull origin main` - Pull changes from the `main` branch on the remote repository

## SSH Key Configuration
- `cd .ssh` - Navigate to the SSH directory
- `ssh-keygen` - Generate an SSH key pair
- `cat .pub` - Display the public SSH key
- Copy the public key to GitHub

## Merging Branches
- `git merge dev` - Merge the `dev` branch into the current branch
- `git push origin staging` - Push the `staging` branch to the remote repository

## Miscellaneous
- `git restore nibbi` - Restore the file `nibbi` to the previous state
- Changes made on GitHub to `README.md`:
  - `cat README.md` - Display the content of `README.md`
  - `git pull origin main` - Pull the changes from the remote repository
