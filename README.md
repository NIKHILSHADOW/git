# BASICS OF GIT AND GITHUB

### GIT

* Git is a distributed version control System
* It provides mechanisms to manage, track, organise different versions of source code 
* Here we can create multiple braches and work on each independently
* After finishing changes in different branches, we can merge them 
* It helps when we are working on a different use cases of application 

### GITHUB

* It is web based platform that manages git repositories
* It provide additional features like collaboration, code-review and project management
* It is remote repository, where multiple developers can work on it 
* It offers easy code sharing with others, and recieve multiple pull requests
  and continuous integration and deployment. 


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

### Diff between local branch and remote branch

```
git diff branch-name origin/branch-name
```