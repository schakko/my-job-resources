> Doing that stuff for more than 20 years and still forgetting the easiest commands.

# Branches 
## Rename branch
```
# rename current branch
git branch -M ${NEW_NAME}

# rename other branch
git branch -M ${OLD_NAME} ${NEW_NAME}
```

# Tags
## Push all tags of a repository to remote

```
git push origin --tags
```

## Delete remote tag
```
git push --delete origin ${TAG}
```

## Delete a tag, if a branch with the same name also exists

```
error: dst refspec develop matches more than one.
error: failed to push some refs to 'git@github.com:orga/repo.git'
```

```
git push --delete origin refs/tags/${TAG}
```
