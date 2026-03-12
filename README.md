# :books:Git-GitHub

Throughout this Git and GitHub course, I have learned the fundamental concepts and workflows that are essential for modern software development. This document outlines what I've learned about Git, its core concepts, and the three-stage workflow that forms the backbone of version control.

### What is Git?

Git is a **distributed version control system** that allows developers to track changes in their code over time. Unlike centralized version control systems, Git enables every developer to have a complete copy of the project history on their local machine. This makes Git powerful for collaboration, branching, and maintaining a complete audit trail of all changes made to a project.

### Git vs GitHub
- Git is an application you install and run locally.
- Git is a local application for version control.
- You can use Git without GitHub.
- GitHub is just one of many hosting options.

## Git Areas Overview

I've learned that Git has three main areas, and each one serves a specific purpose in the version control workflow

The Three Areas:
- **``Working Directory``** - Where you create and edit your files locally
- **``Staged Area``** - Where you prepare changes before committing them
- **``Commit (Repository)``** - Where your changes are permanently saved in project h

## :computer: 1 Working Directory

**What it is:** The folder on your computer where you actually work and edit files.

**In this diagram:** Shows `file.txt` (highlighted in blue with a dashed border), indicating it's a file that exists in your local workspace but hasn't been tracked by Git yet.

**Purpose:** This is where you create, modify, and delete files before telling Git about the changes.

## :rocket: 2 Staged Area (Index)

**What it is:** A temporary holding area that prepares your changes for the next commit.

**In this diagram:** The middle section is empty, but when you run `git add file.txt`, the file moves here.

**Purpose:** Allows you to selectively choose which changes to include in your next commit. You can have multiple changes in your working directory but only stage some of them.

## :gear: 3 Commit (Repository)

**What it is:** The permanent history of your project stored in the `.git` folder.

**In this diagram:** The leftmost section is empty, but when you run `git commit -m "message"`, staged changes move here and become part of the official history.

**Purpose:** Creates a snapshot of your project at a specific point in time with a descriptive message.


# Git Commands

Throughout this Git and GitHub course, I have learned a lot of important commands that are essential for version control and collaboration. These commands form the foundation of working with Git efficiently.

### git init
```Git
git init
```
The `git init` command is the **first command** you use when starting a new Git project. It initializes a new Git repository in your current directory.

### What does it do?

- Creates a new `.git` directory in your project folder
- Sets up all the necessary files and metadata for Git to track your project
- Prepares your project for version control
- Initializes your local repository

### git status

```git
git status
```
Shows the current state of your working directory and staging area, displaying which files have changes.

## git add

```git
git add filename
```
Moves changes from your working directory to the staging area, preparing them for commit.

## git commit

```git
git commit -m "message"
```

Saves your staged changes to the Git repository with a descriptive message about what changed.

## git log

```git
git log
```

Displays the commit history of your repository, showing all previous commits with messages and timestamps.

## git log --oneline 
```git
git log --oneline
```
Displays the commit history in a compact, single-line format showing commit hash and message.

## git log --oneline --graph
```git
git log --oneline --graph
```
Displays the commit history in a compact format with a visual graph showing the branch structure and merge history

## commands showing details

## git diff

```git
git diff
```
Shows the differences between your working directory and the staging area, displaying what has changed in your files.

## git show

```git
git show 
```
Displays the details of a specific commit, including the changes made, author, and timestamp

# Commands for Managing Branches

# git branch

```git
git branch <name>
```
Creates a new branch with the specified name in your repository.

## git checkout

```git
git checkout <branch-name>
```
Switches to a different branch, moving your working directory to that branch's code.

## git branch -d

```git
git branch -d <name>
```
Deletes a branch with the specified name from your repository.
