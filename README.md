# lab02

## How to Remove Branches
Locally: Use  to delete a branch locally.
Remotely: Use  to delete a branch remotely.

## How to Remove Branches

Locally:  `git branch -d branch-name` to delete a branch locally.
Remotely: `git push origin --delete branch-name` to delete a branch remotely.

Annotated tags: Store metadata (message, author, date) and are used for  releases or milestones (`git tag -a v1.7 -m "Version 1.7 - Lab 2 completed"`).  
Lightweight tags: Simple commit pointers with no metadata  (`git tag v1.7`).

when to use rebase
Clean Commit History: To create a linear and organized history by combining changes from the main branch (git rebase main)
Feature Branch Updates: When you need to update your feature branch with the latest changes from the main branch before merging
Avoid Merge Commits: To integrate changes without creating additional merge commits, making the history easier to read.


TO DELETE TAG LOCALLY AND REMOTELY

Delete Tags Locally:  `git tag -d tag-name`.
Delete Tags Remotely:  `git push origin --delete tag-name`

tol ist all tags => git tags

![Image](image.jpg)
