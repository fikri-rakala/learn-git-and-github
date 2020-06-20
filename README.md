# Learn Git and Github

## Getting Started

### What is Git?

Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later.

Git has three main states that your files can reside in: modified, staged, and committed.

### Installing Git

[Download and install the latest version of Git](https://git-scm.com/downloads)

### First-Time Git Setup

Setting your Git username and email for every repository on your computer:

```
git config --global user.name "username"
git config --global user.email "email@example.com"
```

https://help.github.com/en/github/getting-started-with-github/set-up-git

### Checking Your Settings

```
git config --list
```

## Creating a Git Repository

### Initializing a Repository in an Existing Directory

You can take a local directory that is currently not under version control, and turn it into a Git repository.

```
git init
```

### Cloning an Existing Repository

```
git clone url
```

## Git Basics

### Checking the Status of Your Files

```
git status
```

### Tracking New Files

```
git add files
```

### Staging Modified Files

```
git add files
```

### Committing Your Changes

```
git commit
```

```
git commit -m "message"
```

### Skipping the Staging Area

Adding the -a option to the git commit command makes Git automatically stage every file that is already tracked before doing the commit, letting you skip the git add part.

```
git commit -a
```

### Viewing the Commit History

```
git log
```


### 2. Create a new repository on the command line

```
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/fikri-rakala/test.git
git push -u origin master
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

### Delete Branch Locally

```
git branch --delete branchname
```

### Delete Branch Remotely

```
git push origin --delete branchname
```