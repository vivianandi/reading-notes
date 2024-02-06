# Git Tutorial: A Comprehensive Guide

## Version Control
- **Local Version Control:** Single database on your hard disk
- **Centralized Version Control:** Single server for collaboration
- **Distributed Version Control:** Prevents single point of failure, allows mirrored repositories

## What is Git?
Git is a Distributed Version Control System that:
- Stores data in snapshots
- Relies on local operations for efficiency
- Tracks every change to files
- Minimizes the risk of irreversible damage
- Files in git can either be
    - Committed: data is securely stored in a local database
    - Modified: File has been changed but not committed to the database
    - Staged: Flagged a file’s changed version to be committed in the next snapshot

## Setting up a Git Repository
### Importing
To import an existing project or directory into Git
1. Switch to the target project’s directory
2. Use the git init command
   `git init`
3. To start tracking these repository files, perform an initial commit by typing the following:
    `git add *.c`
    `git add LICENSE`
    `git commit -m “any message here”`

### Cloning
Create a copy of an existing Git repository using `git clone` and the repository's URL
- Example with a name change - `git clone https://github.com/test mydirectory`

## Workflow
### Local Repository Structure
The local Git repository has three components:
1. Working Directory: The actual files reside here
2. Index: The area used for staging
3. Head: Points to the most recent commit

### Saving Changes
**Tracked files** can be modified, unmodified, or staged; they were part of the most recent file snapshot
**Untracked files** were not in the last snapshot and do not currently reside in the staging area

### Life Cycle of File Status
1. After you edit a file, Git flags it as modified because of changes made after the previous commit
2. You stage the modified file
3. Then, you commit staged changes

### Check File Status
`git status`

### Tracking and Staging a New File
Single File
Track one file only by using the following format:
`git add filename`

All Files
Track all files in a repository by using the following command:
`git add *`

### Committing a file
After staging one or multiple files
`git commit -m “made change x,y,z”`

### Committing all changes
`git commit -a`

### Pushing Changes
Push changes to a remote repository
`git push origin master`
- This command pushes changes from the local “master” branch to the remote repository named “origin”

# Q&A
1. What is Version Control?
Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes. Through version control, one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes.

2. What is cloning in Git?
To copy all versions of all files for a project.

3. What is the command to track and stage files?
To track and stage files in Git:
`git add <filename>`
To stage all changes:
`git add .`

5. What is the command to take a snapshot of your changed files?
`git commit -m "commit message"`

6. What is the command to send your changed files to Github?
`git push origin main`
