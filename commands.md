# Git Commands:

## Directory Management
- `mkdir git-for-devops` - Create a directory named `git-for-devops`
- `cd git-for-devops` - Change to the `git-for-devops` directory

## Git Initialization
- `git init` - Initialize a new Git repository

## Viewing Files
- `ls -la` - List all files, including hidden files, in long format
- `ls` - List directory contents

## File Creation and Editing
- `vi Hello` - Create or edit a file named `Hello`
- `vi nibbi` - Create or edit a file named `nibbi`
- `vi nibba` - Create or edit a file named `nibba`
- `touch nibba nibbi` - Create empty files named `nibba` and `nibbi`
- `touch nibbu` - Create an empty file named `nibbu`

## Git Status
- `git status` - Show the working tree status

## File Removal
- `rm Hello` - Remove the file `Hello`
- `rm nibbi` - Remove the file `nibbi`

## Staging and Unstaging Files
- `git add nibbi` - Add `nibbi` to the staging area
- `git add nibba` - Add `nibba` to the staging area
- `git rm --cached nibba` - Unstage `nibba` from the index

## Committing Changes
- `git commit -m "adding nibba nibbi"` - Commit changes with the message "adding nibba nibbi"
- `git commit -m "added new changes to nibbi"` - Commit changes with the message "added new changes to nibbi"
- `git commit -m "added nibba changes"` - Commit changes with the message "added nibba changes"
- `git commit -m "added nibbu"` - Commit changes with the message "added nibbu"

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
- `git switch dev` - Switch to the `dev` branch

## Miscellaneous
- `git restore nibbi` - Restore the file `nibbi` to the previous state
