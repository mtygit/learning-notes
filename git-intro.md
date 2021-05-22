# Git notes

## Setting up a Git Repository

- Importing
  1. Switch to the target project’s directory: cd
  2. Use the git init command: git init
  3. To start tracking these repository files: 
     - git add *.c
     - git add LICENSE
     - git commit -m "any message here"

- Cloning 
  - git clone URL

## Workflow

- Useful commands:
  - Check file status: git status 
  - Tracking and staging a new file:
    - Single file: git add filename
    - All files: git add \*
  - Committing a file: git commit -m "made change 1, 2, 3"
  - Committing all changes: git commit -a
  - Pushing changes: git push origin main
  - Stashing changes: git stash
  - Retrieving the hidden changes: git stash apply

## Remote Repositories

- Seeing your remotes
  - git remote 
  - git remote -v
