## Overview


# Git practice!

## About it
> This page is for Izumi chan to practice git with me. This should give you some basic idea of how engineers perform the most common actions in Git. Ganbare!


#### What is Git

Git is a distributed version control system

#### Install Git

There are a few different ways to install git (from source or for Linux) but the purpose of this page is to focus on git commands and procedures, so I am going to skip the installation part of git on a Mac (Plus, I already installed git from your macbook already)


##### Setting up git

```sh
$ git config --global user.name "User Name"

$ git config --global user.name "email address"
```

##### Create LOCAL repository

```sh
$ git init
```

#### Clone the file from Github to work on

```sh
$ git clone URL of the file in Github

$ git pull           ----> up to date

$ git checkout -b [branch name]   -----> create branch
   <--> $ git branch -d [branch name]  ----> delete branch

$ git pill

$ atom .
```

### Modify or fix the issues in Atom then make sure SAVE!

#### Add to the stage, commit to the Local repo, then push to the GitHub

```sh
$ git status

$ git add .

$ git status

$ git commit
    OR
$ git commit --fixed=HEAD   <---- when you fixed

$ git push -u origin HEAD  <---- only when it's first attempt
    OR
$ git push   <---- later than first attempt
```

#### Go to the Github

```sh
1. Pull Request

2. Make some comments

3. Chose Reviewers, Assignees and Labels
```
