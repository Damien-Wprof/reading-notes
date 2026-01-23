# Git Basics – Key Questions and Answers

## What is Version Control?
Version Control is a system that records changes to files over time. It allows you to track edits, restore previous versions, see what changed and who changed it, and collaborate with others without losing work.

## What is cloning in Git?
Cloning is the process of creating a local copy of an existing Git repository. When you clone a repository, you download all project files and the complete version history to your computer.

Command used:
git clone <repository_url>

## What is the command to track and stage files?
To track and stage a file so it can be included in a commit, use:
git add <filename>

To track and stage all files:
git add *

## What is the command to take a snapshot of your changed files?
Taking a snapshot in Git is called committing. This saves the staged changes to the project history.

Command used:
git commit -m "commit message"

## What is the command to send your changed files to GitHub?
Sending your local commits to GitHub is called pushing.

Command used:
git push origin main
