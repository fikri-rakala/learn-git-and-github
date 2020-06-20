# Introduction
* What is version control
* What is Git
* What is Github

# Set up Git
## 1. Installing Git

[Download and install the latest version of Git](https://git-scm.com/downloads)

## 2. Setting your username in Git

https://help.github.com/en/github/using-git/setting-your-username-in-git

## 3. Setting your commit email address

https://help.github.com/en/github/setting-up-and-managing-your-github-user-account/setting-your-commit-email-address

# Create a new repository
## 1. Create a repo in Github

https://help.github.com/en/github/getting-started-with-github/create-a-repo

## 2. Create a new repository on the command line

```
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/fikri-rakala/test.git
git push -u origin master
```

## 3. Cloning a repository

```
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```

# Working with Git
* git add
* git restore --stage filename
* git commit

## Viewing the commit history
* git log