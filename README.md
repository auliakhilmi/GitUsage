# GIT Usage
**Tutorial for myself and others if you want**

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

## Caching your GitHub password in Git

#### 1. In Terminal, enter the following:
```
$ git config --global credential.helper cache
# Set git to use the credential memory cache
```

#### 2. To change the default password cache timeout, enter the following:
```
$ git config --global credential.helper 'cache --timeout=3600'
# Set the cache to timeout after 1 hour (setting is in seconds)
```

**Source:**

[![GitHub Help](https://help.github.com/assets/images/site/logo.png)](https://help.github.com)
