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
