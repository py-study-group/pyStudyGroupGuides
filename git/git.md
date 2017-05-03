# Git

Git is a great version control system. For example it can be used together with GitHub.

## Introduction

### Setup

First of all, you have you set up your configuration. Execute those both commands in the terminal and replace it with your name and your email address.

```
git config --global user.name "YOUR NAME"
git config --global user.email "YOUR EMAIL ADDRESS"
```


### Create Repository

You can either create a new git repository.

```
git init project-name
```

If you already have a repository you can clone it from GitHub too.

```
git clone https://github.com/username/repository
```

### Make changes

Now you can write your code in the folder with the repository name.

With the status command you will see which files were changed.

```
git status
```

Next you will have to add all your files

```
git add *
```

or just one specific file

```
git add filename
```

Now you can make a new commit to your repository.
A commit message should begin with: Add, Update or Fix.

```
git commit -m "Add app.py"
```

Next you can upload your code to GitHub.

```
git push
```

# Work with git

If you want to see your commit history, type the following command.

```
git log
```

If you work with several persons on a project you should always pull the changes before you start with editing any files.

```
git pull
```

If you make any new changes on your code, just add all the files, make a commit and push the commit.
