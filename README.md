# 📌 Git

**Git** is a version control system that allows you to track changes in a project, manage history, work with multiple versions of code, and facilitates collaboration within a team.

It is especially useful in testing: a QA engineer can use Git to maintain documentation, write bug reports, store test cases, and manage test data.

🔍 This repository contains essential Git commands that are regularly used by QA engineers in their daily work.


## Navigation

- [Creating and cloning](#Creating-and-cloning)
- [Adding remote and pushing](#Adding-remote-and-pushing)
- [Committing changes](#Committing-changes)
- [Working with branches](#Working-with-branches)
- [Status and logs](#Status-and-logs)
- [Undoing changes](#Undoing-changes)

## Creating and cloning
```git
git init project-name                               # Initialize a new Git repository
git clone <URL>                                     # Clone an existing GitHub repository
```

## Adding remote and pushing
```git
git remote add origin <URL>                         # Link local repository with remote
git push -u origin main                             # Push to main branch
git fetch                                           # Download changes from remote without merging
git push                                            # Push new changes
git pull                                            # Pull changes from remote repository
```
## Committing changes
```git
git add .                                           # Stage all changes
git add file.txt                                    # Stage specific file
git commit -m "Added file.txt"                      # Commit with message
git commit --amend -m "New commit message"          # Rename last commit
```

## Working with branches
```git
git branch                                          # List all branches
git branch second-branch                            # Create a new branch named second-branch
git checkout second-branch                          # Switch to the second-branch
git checkout -b second-branch                       # Create and switch to second-branch in one command
git merge second-branch                             # Merge second-branch into the current branch
```

## Status and logs
```git
git status                                          # View current status
git log                                             # View commit history
git diff                                            # View changes not staged
```

## Undoing changes
```git
git restore file.txt                                # Discard changes in file
git reset HEAD file.txt                             # Unstage file
git reset --hard                                    # Reset everything to last commit
```
👀 Psst… Just so you know, there are awesome [Git Cheat Sheets](https://education.github.com/git-cheat-sheet-education.pdf) available
