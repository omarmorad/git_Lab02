# lab02


## 1. Remove a Branch Locally

To delete a branch locally, use:

``` git branch -d <branch_name> ```

## 2. Remove a Branch remotelly 

To delete a branch on the remote repo, use:

``` git push origin --delete <branch_name> ```

# Tags 
## how to list all tags 
```git tag```

## Annotated Tags vs Lightweighted Tags

* Annotated Tags: Full Git objects with metadata (message, author, date) and are usually used for marking releases or milestones.

* Lightweight Tags: pointers to a specific commit, with no additional metadata.

![Tags screenshot](/Images/Tags.png)

## How to delete tags

### locally 
``` git tag -d <tag_name> ```

### remote 
``` git push origin --delete <tag_name> ```

# Rebase

## 1 - switch to the branch you want to rebase 

``` git checkout <branch_name> ```

## 2 - rebase to the base branch

``` git rebase <base_branch_name> ```

## 3 - solve any conflicts
** you can abort using the command 
``` git rebase --abort ```


## 4 - resume the rebase process

``` git rebase --continue ```

# When to use rebase

## new feature

* if you're adding a new feature and you need to get the latest changes to the main branch you can use rebase instead of using unnesscary merges


![Image](image.jpg)
