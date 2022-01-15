`git clone <https://name-of-the-repository-link>`

# Branch

## Creating a new branch

`git branch <branch-name>`

## Pushing a local branch to a remote repository

`git push -u <remote> <branch-name>`

## Viewing branches

`git branch`

## Deleting a branch

`git branch -d <branch-name>`

# Git checkout

Git checkout is used to switch between branches.

`git checkout <branch-name>`

There are some steps you need to follow for successfully switching between branches:

- The changes in your current branch must be committed or stashed before you switch
- The branch you want to check out should exist in your local

## Create and switch to a new branch

`git checkout -b <name-of-your-branch>`

# Git push

`git push <remote> <branch-name>`

If branch is newly created. we need to set-upstream

`git push --set-upstream <remote> <name-of-your-branch>`

# Git revert

` git log -- oneline`

`git revert <commit-hash>`
