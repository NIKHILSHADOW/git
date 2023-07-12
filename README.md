# BASIC GIT COMMANDS

### Intialise the git repository
```
git init
```


### ADD external directory
```
git config --global --add safe.directory D:/link1/link11/link111
```

### ADD Command

move file from untracked to tracked
```
git add filename.txt
```



move all changes(untracked and modified) to staged

```
git add .
or
git add --all
or 
git add -a
```

move each change one by one
works only for tracked files
```
git add -p
or
git add --patch
```
### Commit
commit changes which are staged
```
git commit -m "type-message-here"
```

### Move files to remote directory

set remote first
```
git remote add origin git@github.com:user-name/repo-name.git
```

push changes
```
git push origin master
```


### Check local branches
asterik sign one is current branch
```
git branch
```

### Switching between one branch to other

```
git checkout branch-name
```

### Create a new branch
```
git checkout -b branch-name
```

