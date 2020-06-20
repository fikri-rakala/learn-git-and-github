# Learn Git and Github

## Introduction

### What is version control

Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later.

### What is Git

Git has three main states that your files can reside in: modified, staged, and committed.

* Modified means that you have changed the file but have not committed it to your database yet.

* Staged means that you have marked a modified file in its current version to go into your next commit snapshot.

* Committed means that the data is safely stored in your local database.

### What is Github

GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Set up Git
### 1. Installing Git

[Download and install the latest version of Git](https://git-scm.com/downloads)

### 2. Setting your username in Git

Setting your Git username for every repository on your computer:

```
git config --global user.name "name"
```

Setting your Git username for a single repository:

```
git config user.name "Mona Lisa"
```

https://help.github.com/en/github/using-git/setting-your-username-in-git

### 3. Setting your commit email address

Setting your email address for every repository on your computer:

```
git config --global user.email "email@example.com"
```

Setting your email address for a single repository:

```
git config user.email "email@example.com"
```

https://help.github.com/en/github/setting-up-and-managing-your-github-user-account/setting-your-commit-email-address

## Create a new repository
### 1. Create a repo in Github

https://help.github.com/en/github/getting-started-with-github/create-a-repo

### 2. Create a new repository on the command line

```
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/fikri-rakala/test.git
git push -u origin master
```

### 3. Cloning a repository

```
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```

## Working with Git

### Viewing Your Staged and Unstaged Changes

```
git status
```

### Tracking/Staging files

```
git add filename
```

### Unstaged files

```
git restore --stage filename
```

### Commits changes

```
git commit -m "message"
```

```
git commit -am "message"
```

### Viewing the commit history

```
git log
```

### Reset or Go back to the previous commit

```
git reset --hard commithash
```

Reset branch to master:

```
git reset --hard origin/master
```

## Working with Remotes

### Pushing to Your Remotes

```
git push
```

### Pulling from Your Remotes

```
git pull
```

## Branching

### Shows current branch

```
git branch
```

### Creating a new branch

```
git branch branchname
```

### Switching Branches

```
git checkout branchname
```

### Merging Branches

```
git merge branchname
```