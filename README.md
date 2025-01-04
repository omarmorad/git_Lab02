# lab02


## 1. Remove a Branch Locally

To delete a branch locally, use: ``` git branch -d <branch_name> ```



## 2. Remove a Branch remotelly 

To delete a branch on the remote repo, use:``` git push origin --delete <branch_name> ```



# Tags 
## how to list all tags  ```git tag```


## Annotated Tags vs Lightweighted Tags

* Annotated Tags: Full Git objects with metadata (message, author, date) and are usually used for marking releases or milestones.

* Lightweight Tags: pointers to a specific commit, with no additional metadata.



## How to delete tags

### locally 
``` git tag -d <tag_name> ```

### remote 
``` git push origin --delete <tag_name> ```

# Rebase


# When to use rebase

## new feature

New Feature Development:
Use rebase to incorporate the latest changes from the main branch without unnecessary merges.

![Image](image.jpg)
