# Git recipes

## Add and commit

### Only add tracked files

`git add -u`

### Amend commit with new files

```
git add .
git commit --amend --no-edit
git push --force
```

## Rebase

```
git checkout master
git pull
git checkout [my-branch]
git rebase master
```

## Log

### One Line Release Notes

`git log --oneline -no-merges [commit]..`

