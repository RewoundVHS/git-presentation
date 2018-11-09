# Git

## What is Git?

Git is a distributed version control system. Git is an industry standard when it
comes to VCS. GitHub is a wrapper for Git where developers can easily
communicate and create software together and end users can submit bug reports
and feature requests.

## Creating a Repository

To create a new repository you could either create a repository on GitHub and
pull it to the local machine or use `git init` within the directory.

## Committing Changes

To add files to a git repository you simply use `git add filename`. 

If you have files you wish not to commit you can create a `.gitignore`
file and add regex expressions for such files.

## Checking Changes

If you wanted to check the changes made to a file since the last commit you
could use `git log -u -1 filename`