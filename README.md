### How to remove the branches locally and remotely.


### 1- Remove Local Branch

1- Switch to a different branch:
  git checkout main

## Example
git branch -d "branch name"
## and for force delete we use:
git branch -D "branch name"



### 2- Remove Remote Branch

## Example
## To delete the remote branch
git push origin --delete "branch name"


### Attention >> Ensure that the branch is no longer needed before deleting it.



## ==============================================================================


### ● Annotated tags vs Lightweight Tags 

## Annotated Tag	
# Used for releases or important points.	
## To create an annotated tag
# git tag -a v2.0 -m “version 2.0”


## Lightweight Tag
# Used for quick references without documentation.
## To create a lightweight tag
# git tag v1.0



## ==============================================================================

### When to use Rebase
## 1- To Keep a Clean Commit History
## 2- When Working with Feature Branches
## 3- making small updates or bug fixes to avoid extra merge commits
## 4- Clean Up Commit History Before Pushing


## ==============================================================================


### How to list tags?

## To list tags use this command:-
# git tag

## If you want to list tags matching a specific pattern, use this command:-
# git tag -l "v1.7"


## If you want to see details of a specific tag, use this command:-
# git show "tag-name"


## ==============================================================================


### How to delete tag locally and remotely?

## 1. Delete a Tag Locally
# git tag -d "tag-name"

## 2. Delete a Tag Remotely
# git push origin --delete "tag-name"


## ==============================================================================



### Image
[Year Image](Year.jpg)
