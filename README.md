# Git Command

## First Setup
```bash
git init
git add file.md
git commit -m "some comment"
git remote add origin https://github.repository.address
git push -u origin master
```

## Instructions
* Versio Check
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

## Github에 잘못 올린 파일을 지우는 방법
```bash
$ git rm --cached first_project/lib/home.dart
$ git commit -m "Fixed untracked files"
$ git push -u origin master
```

