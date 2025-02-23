Table of Contents
---

- [Git CheatSheet for Developers](#git-cheatsheet-for-developers)
  - [Git Configuration](#git-configuration)
  - [Getting & Creating Projects](#getting--creating-projects)
  - [Basic Commands](#basic-commands)
  - [Branching & Merging](#branching--merging)
  - [Sharing & Updating Projects](#sharing--updating-projects)
  - [Inspection & Comparison](#inspection--comparison)
  - [Setting up Alias](#setting-up-alias)
  - [Deletion](#deletion)
  - [Temporary Commits](#Temporary-commits)

# Git CheatSheet for Developers

## Git Configuration

| Command | Description |
| ------- | ----------- |
| `git config` | Check all configuration options |
| `git config --list` | Check all configuration options with name and email |
| `git clone [https://url]` | Clone source code from a remote repository |

**[🔼Back to Top](#table-of-contents)**

## Getting & Creating Projects

| Command | Description |
| ------- | ----------- |
| `git init` | Initialize a local Git repository |

**[🔼Back to Top](#table-of-contents)**

## Basic Commands

| Command | Description |
| ------- | ----------- |
| `git status` | Check status |
| `git diff` | Compare and show updated codes |
| `git add [file name]` | Add file changes in next commit |
| `git add .` | Add all unstaged changes in next commit |
| `git reset [file name]` | Used to unstage the staged files |
| `git clean -f` | To delete or remove unstaged files forcefully |
| `git commit -m "message about updates"` | Commit changes to current branch |
| `git rm [file]` | Deletes the file from your working directory and stages the deletion |
| `git pull` | Fetches and merges changes on the remote server to your working directory |
| `git fetch` | Gathers remote commits but does not merge them unlike `pull` |
| `git remote add origin [url]` | Adding a remote repository | 
| `git show` | Shows information about any git object |
| `gitk` | Shows graphical interface for a local repository |


**[🔼Back to Top](#table-of-contents)**

## Branching & Merging

| Command | Description |
| ------- | ----------- |
| `git branch` | List branches |
| `git branch [branch-name]` | Create a local branch |
| `git branch -d [branch-name]` | Delete a branch |
| `git checkout [branch-name]` | Switch to another branch |
| `git merge [branch-name]` | Merge branchs |
| `git checkout -b "branch name"` | Create a new branch and switch to that branch |

**[🔼Back to Top](#table-of-contents)**

## Sharing & Updating Projects

| Command | Description |
| ------- | ----------- |
| `git push origin [branch name]` | Push a branch to your remote repository |
| `git pull origin [branch name]` | Pull a branch from your remote repository |
| `git remote origin [branch name]` | Connect repository to local server |

**[🔼Back to Top](#table-of-contents)**

## Inspection & Comparison

| Command | Description |
| ------- | ----------- |
| `git log` | View changes |

**[🔼Back to Top](#table-of-contents)**

## Setting up Alias

| Command | Description |
| ------- | ----------- |
| `git config --global alias.[short name for command]  [actual command]` | Alias make the commands short and handy | (## ex:- git config --global alias.st status)

**[🔼Back to Top](#table-of-contents)**

## Deletion
| Command | Description |
| ------- | ----------- |
| `git gc` | Cleans unnecessary files and optimizes the local repository |
| `git prune` | Deletes objects that don’t have any incoming pointers |

**[🔼Back to Top](#table-of-contents)**

## Temporary Commits
| command | Description |
| ------- | ----------- |
| `git stash`| Save modified and staged changes|
|`git stash list`| list stack-order of stashed file changes|
|`git stash pop`| write working from top of stash stack|
|`git stash drop` | discard the changes from top of stash stack|


**[🔼Back to Top](#table-of-contents)**
