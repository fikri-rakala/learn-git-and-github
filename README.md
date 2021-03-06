# Learn Git and Github

## Getting Started

### Introducing Git

Git is a version control system that records changes to a file or set of files over time so that you can recall specific versions later.

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

## Working with a Local Repository

### Creating/Initializing a Repository

You can take a local directory that is currently not under version control, and turn it into a Git repository.

```
git init
```

### Checking the Status of Your Files

```
git status
```

### Tracking New Files

```
git add <file>
```

### Staging Modified Files

```
git add <file>
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
git commit -am "message"
```

### Viewing the Commit History

```
git log
```

### Unstaging a Staged File

```
git restore --staged <file>
```

### Unmodifying a Modified File

```
git restore <file>
```

### Adding Remote Repository

```
git remote add origin https://github.com/fikri-rakala/testing.git
git push -u origin master
```

## Working with Remote Repository

### Cloning a Remote Repository

```
git clone <url>
```

### Pulling from Your Remotes

```
git pull
```

Running git pull generally fetches data from the server you originally cloned from and automatically tries to merge it into the code you’re currently working on.

### Pushing to Your Remotes

```
git push
```

## Branches

### Displaying Branches in a Repository and Currently On

```
git branch
```

### Creating a New Branch

```
git branch <branchname>
```

### Switching Branches

```
git checkout <branchname>
```

### Merging Branches

```
git merge <branchname>
```

### Delete Branches

```
git branch -d <branchname>
```

### Merge Conflicts

Fix conflicts and then commit the result.

## Remote Branches

### Pushing

```
git push -u origin <branchname>
```

### Pulling

```
git pull
```

### Adding Remote Branches into Local Repository

```
git branch <branchname> origin/<branchname>
```

or 

```
git checkout -b <branchname> origin/<branchname>
```

### Deleting Remote Branches

```
git push origin --delete <branchname>
```