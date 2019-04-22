
# Git snippets

## Setting your branch to match the remote branch:
```
git fetch origin
git reset --hard origin/master
```

## Alias for git upstream
sup = !git branch --set-upstream-to=origin/`git symbolic-ref --short HEAD`
