# Git Command

## First Setup
```bash
git init
git add .
git commit -m "some comment"
git branch -M main
git remote add origin https://github.repository.address.git
git push -u origin main
```

## Instructions
* Version Check
```bash
$ git --version
```

* Initialize Local Git Repository
```bash
$ git init
```

* Add Files to Index
```bash
$ git add <file>
```

* Remove FIles to Index
```bash
$ git rm --cached <file>
```

* Check Status Of Working Tree
```bash
$ git status
```

* Commit Changes In Index
```bash
$ git commit
```

* Push to Remote Repository
```bash
$ git push
```

* Pull Latest From Remote Repository
```bash
$ git pull
```

* Clone Repository Into A New Directory
```bash
$ git clone
```

* list out git settings
```base
$ git config --list
```

* User Name setup
```bash
$ git config --global user.name 'Hyuk'
```

* User Email Setup
```bash
$ git config --global user.email 'hyukho83@gmail.com'
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

