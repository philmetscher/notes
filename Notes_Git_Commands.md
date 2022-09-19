### Cloning a remote repository

```
git clone <url>
```

### check git status (untracked, tracked, staged)

```
git status
```

### Add a file to the stage

```
git add <filename>
```

### Create a commit including all staged files

```
git commit -m "Commit message"
```

### Connecting your local repository to a new remote repository

```
git remote add origin git@github.com:GitHubUsername/repository-name.git
git branch -M main
git push -u origin main
```

### Upload content to the remote repository

```
git push
```

### Download content from the remote repository

```
git pull
```

### Create new branch

```
git branch BRANCHNAME
```

### Delete branch

```
git branch -d BRANCHNAME
```

### Show the commit history

```
git log --oneline
```

### You can always return to the last committed state of the entire project

```
git restore .
```

### You can always return to the last committed state of the entire project

```
git restore <file name>
```
