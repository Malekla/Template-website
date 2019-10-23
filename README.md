# Essential Git Commands
Git is a distributed version-control system for tracking changes in source code during software.
Github is a web service that gives you the possibility to use git services(interface).
In this project we will dicover essential git comands.

# Getting Started
## Commits 
What did I just commit?
    git show
How to edit a commit(has not yet been pushed) message?
    git commit --amend --only -m 'xxxNewCommitMessagexxxx'

How to add staged changes to the previous commit?
    git commit --amend
    git commit --amend -C HEAD

How to move unstaged edits to a new branch?
    git checkout -b my-branch
How to move unstaged edits to a different, existing branch?
    git stash
    git checkout my-branch
    git stash pop (pop/apply) 
Stash the changes in a dirty working directory away.



