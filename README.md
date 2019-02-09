# GIT Usage
**Tutorial for myself and other if you want**

For **linux** user with terminal

## Initialization
#### 1. Initialize the local directory as a Git repository.
```sh
$ git init
```
#### 2. Add the files in your new local repository. This stages them for the first commit.
```sh
$ git add .
# Adds the files in the local repository and stages them for commit. To unstage a file, use 'git reset HEAD YOUR-FILE'.
```
#### 3. Commit the files that you've staged in your local repository.
```sh
$ git commit -m "First commit"
# Commits the tracked changes and prepares them to be pushed to a remote repository. To remove this commit and modify the file, use 'git reset --soft HEAD~1' and commit and add the file again.
```

#### 4. In Terminal, add the URL for the remote repository where your local repository will be pushed.
```sh
$ git remote add origin [remote repository URL]
# Sets the new remote
$ git remote -v
# Verifies the new remote URL
```
#### 5. Push the changes in your local repository to GitHub.
```sh
$ git push origin master
# Pushes the changes in your local repository up to the remote repository you specified as the origin
```

**Source:**

[![GitHub Help](https://help.github.com/assets/images/site/logo.png)](https://help.github.com)   [![StackOverflow](<img src="https://cdn.sstatic.net/Sites/stackoverflow/company/img/logos/so/so-logo.svg?v=a010291124bf" width="100"/>)](https://stackoverflow.com)

Rewrite by **@auliakhilmi**
