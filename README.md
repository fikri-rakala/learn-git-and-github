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
git commit -am "message"
```

### Viewing the Commit History

```
git log
```

### Unstaging a Staged File

```
git restore --staged file
```

### Unmodifying a Modified File

```
git restore file
```
