# GIT For Professionals

# Perfect Commit

1.  Include file related to same topic in a single commit.

    > `git add index.html`

2.  If a single file contains multiple changes, we can pick the related changed at patch level. For each changes in the file, choose whether to add in staging area or not.
    > `git add -p index.html`
3.  provide great commit message.
    - Subject => concise summary of the changes.
    - Body

# Branching Strategies

    - Mainline Development
    - State, Release, and Feature branches

1. Long-running and short-lived branches
   1. Commit from short-lived branch to long-running branch should be done via merge or rebase.
   2. short-lived branch will be deleted after integration.

Two Example brnaching stratergies.

1. Github flow
2. GitFlow

# Pull Request

1. A Pull Requeat invites reviewers to provide feedback before merging the code.
2. Contributing Code to other projects.
   > Fork is a personal copy of a repository.

## Merge Conflicts

### How and When Conflicts Occur

When integratin commits from Different Souces.

```
git merge
git rebase
git pull
git cherry-pick
git stash apply
```

### How to undo a conflict and start over

you can always undo and start fresh

```
git merge --abort
git rebase --abort
```

# Merge vs Rebase

1. A Fast-Forward Merge
   1. Contains commits from both branches.
2. Merge Commits:
   1. These are automatically created by git while merging two branches.

## Rebase

- Step1: Git removes all comits from branch A after the common commit.
- Step2: Git adds all commits from branch B after this both brances looks same.
- Step3: adds commits from branch A after this, "Rebased"
  Commit histroy is changed.

```
git rebase -i <branch>
```
