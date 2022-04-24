## Overview


# Git practice!

## About it
> This page is for Izumi chan to practice git with me. This should give you some basic idea of how engineers perform the most common actions in Git. Kanbare!


#### What is Git

Git is a distributed version control system

#### Install Git

There are a few different ways to install git (from source or for Linux) but the purpose of this page is to focus on git commands and procedures, so I am going to skip the installation part of git on a Mac (Plus, I already installed git from your macbook already)


##### Setting up git

```sh
$ git config --global user.name "User Name"

$ git config --global user.email "email address info"
```

##### Applying color to git

```sh
$ git config --global color.ui true
```

##### Initializing a repository in an existing directory

If you’re starting to track an existing project in Git, you need to go to the project’s directory and type:

```sh
$ git init
```
This creates a new subdirectory named .git that contains all of your necessary repository files — a Git repository skeleton. At this point, nothing in your project is tracked yet.
