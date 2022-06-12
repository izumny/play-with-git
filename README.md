## Overview


# Play with git!

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

###### Clone the file from Github

```sh
$ git clone URL of the file in Github
```

###### Pulling all the data up to date

```sh
$ git pull
```

###### Create the new branch

```sh
$ git checkout -b <<branch name>>
```

###### Delete the existing branch

```sh
$ git branch -d <<branch name>>
```

 ###### Up to date again

```sh
$ git pull
```

###### sync with atom

```sh
$ atom .
```

#### Modify or fix the issues in Atom then make sure SAVE!

##### Add to the stage  

```sh
$ git status
$ git add .
$ git status
```

- [x] Commit to the Local repository for the first time

```sh
$ git commit
```
- [x] If its fixed once or more
```sh
$ git commit --fixed=HEAD
```

- [x] Push to the GitHub for first attempt with new branch
```sh
$ git push -u origin HEAD
```
- [x] Second time or more from the branch
```sh
$ git push  
```

#### Go to the Github

```sh
1. Pull Request

2. Make some comments

3. Chose Reviewers, Assignees and Labels
```
