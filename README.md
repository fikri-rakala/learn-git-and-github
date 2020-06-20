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

https://help.github.com/en/github/using-git/setting-your-username-in-git

### 3. Setting your commit email address

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
### Tracking files

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
git commit -am "message
```

### Viewing the commit history

```
git log
```