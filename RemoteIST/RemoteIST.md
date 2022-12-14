# 🌟 Remote:

- Init GitHub bare repository:

```shell
git init --bare
```

- List all remote:

```shell
git remote -a
```

- View remote info:

```shell
git remote -v
```

- Add remote to local repository:

```shell
git remote add remoteName remoteURL
```

```shell
git remote add origin https://github.com/internSeXuanHoa/github-crash-course.git
```

- Delete a remote in local repository:

```shell
git remote rm remoteName
```

```shell
git remote rm origin
```

- Delete a branch in remote repository:

```shell
git push --delete branchName

```

```shell
git push --delete dev

```

- Push:

```shell
git push -u remoteName branchName
```

```shell
git push -u origin --all
git push -u origin master
```

- Clone:

```shell
git clone remoteURL
```

```shell
git clone https://github.com/internSeXuanHoa/github-crash-course.git
```

- Fetch:

```shell
git fetch
```

- Pull:

```shell
git pull remoteName branchName
```

```shell
git pull origin --all
git pull origin master
```

- List all tags:

```shell
git tag
```

- Create a tag:

```shell
git tag -a tagName -m messene commitId
```

```shell
git tag -a "1.0.0" -m "V 1.0.0" 89ff6e3
```

- Show tag info:

```shell
git show tagName
```

```shell
git show "1.0.0"
```

- Delete tag:

```shell
git tag -d tagName
git push --delete remoteName tagName
```

```shell
git tag -d "1.0.0"
git push --delete origin "1.0.0"
```

- Push tag to remote:

```shell
git push --tag
```
