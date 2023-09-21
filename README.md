# Git Cheat Sheet and Branching Practice

## Overview

Common command reference, and practicing with commits and branches.

## Basic Commands

* 'git init' - initialize local Git repo
* 'get add fileName' - stage changed file 'fileName' for commit
* 'git commit -m "meggage"' - commit staged changes, with commit message "message"

## Info Commands

* 'git status' - shows status of working directory
* 'git log' - lists local commit history
* 'git log --oneline' lists local commit history in compact format

## Branch Commands

* 'git branch' - list local branches
* 'git branch -m "newName"' - rename current branch to "newName"
* 'git branch "branchName"' - create local branch "branchName"
* 'git checkout "branchName' - switch to local branch "branchName"
* 'git checkout -b "brancName"' - create and switch to "branchName"


## VI Commands

* ':wq' - w = write q = quit 

## Remote Commands

* 'git remote add origin url' - configure "url" as a remote repo with alias "origin"
* 'git push origin "branchName"' - push local commits to remote repo "origin" on branch "branchName"

