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

Move file from untracked to tracked
```
git add filename.txt
```

### File status in GIT

![image-1](/temp/image1.png)





Move all changes(untracked and modified) to staged

```
git add .
or
git add --all
or 
git add -a
```

Move each change one by one
Works only for tracked files
```
git add -p
or
git add --patch
```
### Commit
Commit changes which are staged
```
git commit -m "type-message-here"
```

### Move files to remote directory

Set remote first
```
git remote add origin git@github.com:user-name/repo-name.git
```

Push changes
```
git push origin master
```


### Check local branches
Asterik sign one is current branch
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

View remote branches

```
git branch -r
```

View local and remote branches

```
git branch -a
```

View branch with commit

```
git branch -vv
```

View branch with commit of local and remote

```
git branch -vva
```
