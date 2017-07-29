# GitHub Guide
(because Emily is forever clueless)

## Getting a copy of a repository on GitHub
```
git clone (url)
```

## Push changes
```
git add (filename)
git commit -m "This is a message detailing the changes I made"
git push origin branch
```

## Add all files from a directory
```
git add * OR git add .
```

## Force remove local files & checkout to another branch
```
git checkout -f another-branch-name
```

## Undo local changes
```
git checkout -- bad-code-filename
```
*overwrites local changes, restoring to old code*

## Retrieve latest commits in branch
```
git pull
```
*always do this before committing changes*

## See what files have been changed locally
```
git status
```

## When you can't merge, just stash!
```
git stash
```

## And FINALLY, what the heck is origin?!
```
git checkout origin/branch_name = working in local repository
git checkout branch_name = on actual branch in git
```