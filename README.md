# Git Commands

## First Setup

```bash
git init
git add .
git commit -m "some comment"
git branch -M main
git remote add origin https://github.repository.address.git
git push -u origin main
```

## Version Check

```bash
$ git --version
```

## Initialize Local Git Repository

```bash
$ git init
```

## User Name setup

```bash
$ git config --global user.name 'Hyuk'
```

## User Email Setup

```bash
$ git config --global user.email 'hyukho83@gmail.com'
```

## Check Status Of Working Tree

```bash
$ git status
```

## Add Files to Index

```bash
$ git add <file>
```

## Remove file from staged area #1

```bash
$ git restore --stage <file>
```

## Remove file from staged area #2

```bash
$ git rm --cached <file>

```

## Commit Changes In Index

```bash
$ git commit
```

## Change name of the master branch to main

```bash
$ git branch -M main
```

## Push to Remote Repository

```bash
$ git push
```

## Pull Latest From Remote Repository

```bash
$ git pull
```

## Clone Repository Into A New Directory

```bash
$ git clone repository-url
```

## list out git settings

```base
$ git config --list
```

## check git remote url

```bash
$ git remote -v
```

## Change git remote

```bash
$ git remote set-url origin https://github.com/user/new-git-repository.git
```

## Rebase Setup

when you see git command error below, it will help fix the error

> git error: failed to push some refs to 'master'

```bash
git pull --rebase origin master
git push origin master
```

```bash
git reset

git reset --hard <commit>
git reset --hard origin/master
```

## remove uploaded files on github.

```bash
$ git rm --cached first_project/lib/home.dart
$ git commit -m "Fixed untracked files"
$ git push -u origin main
```

## Check who and when made changes

```bash
$ git blame <file>
```

## Check who and when made changes from line 1 to 10

```bash
$ git blame -L 1,10 <file>
```

## Check who and when made changes from line 1 to 10 with long format

```bash
$ git blame -l <file>
```

## Check commit history

```bash
$ git log
```
