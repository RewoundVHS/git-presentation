<br>
<p align="center">
  <img src="https://user-images.githubusercontent.com/23706925/48293363-add70f00-e44c-11e8-922b-0c77af21bd72.png" alt="EUPCS Club Logo" width="200" height="200">
</p>
<br>

# Git

## What is Git?

Git is a distributed version control system. Git is an industry standard when it
comes to VCS. GitHub is a wrapper for Git where developers can easily
communicate and create software together and end users can submit bug reports
and feature requests.

## The Three States

Files have three states in a Git directory.
* Committed
* Modified
* Staged

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

## Rolling Back Changes

If you are unsatisfied with the changes made in a commit you can revert to a
previous commit with `git reset --hard HEAD`

## GitHub Features

### Issues

Issues are used to submit bug reports and feature requests and are written in
Markdown.

### Forking

You can copy all of the contents of a user's repository to your own you can 
`fork` it. This allows you to modify and improve another user's code without
being a contributor.

### Pull Requests

If you believe the modifications and improvements you have made would benefit
the project upstream you can submit a `pull request`. This allows the upstream
developers and maintainers to review your changes and accept (or deny) them.
The documentation for a pull request is written in Markdown.

## Best Practices

To build a good GitHub profile you should start by choosing a good username,
especially if you want to show potential employers. (Which I would highly
reccommend.) 

Host a few projects that are representative of your ability as a developer.

You should write proper documentation, starting with a nice Readme.md.

Find projects that you are interested in and get involved.
