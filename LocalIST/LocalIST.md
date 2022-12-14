# 🌟 Local:

- Init a GitHub repository:

```shell
git init
```

- Check repository status:

```shell
git status
```

- Add file to staged:

```shell
git add fileName
```

```shell
git add .
git add ./src
git add index.html
```

- Delete file from staged:

```shell
git restore --staged filePath
```

```shell
git restore --staged .
git restore --staged /src
git restore --staged index.html
```

- Commit a state:

```shell
git commit -m [option] messene
```

```shell
git commit -m "Update Repository"
git commit --amend -m "Update Repository"
```

- Delete a commit:

```shell
git reset [option] HEAD~1
```

```shell
git reset --soft HEAD~1
git reset --head HEAD~1
```

- List all log:

```shell
git log [option]
```

```shell
git log
git log --oneline
git log --oneline --graph
```

- Restore a file to previous state:

```shell
git restore filePath
```

```shell
git stash
git restore .
git restore /src
git restore index.html
```

- Checkout to any previous state:

```shell
git checkout commitId -- filePath
```

```shell
git checkout d2dd0fa -- .
git checkout d2dd0fa -- /src
git checkout d2dd0fa -- index.html
```

- List all branch:

```shell
git branch
```

- Create a new branch:

```shell
git branch branchName
```

```shell
git branch dev
```

- Switch to other branch:

```shell
git checkout branchName
git switch branchName

```

```shell
git checkout dev
git switch dev

```

- Merge branch:

```shell
git merge branchName
git rebase branchName
```

```shell
git merge dev
git rebase dev
```

- Delete a branch:

```shell
git branch -d branchName
```

```shell
git branch -d dev
```
