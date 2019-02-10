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
* Initialize Local Git Repository
```bash
$ git init
```

* Add Files to Index
```bash
$ git add <file>
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

## Rebase Setup
when you see git command error below, it will help fix the error
> git error: failed to push some refs to 'master'
```bash
git pull --rebase origin master
git push origin master
```

```bash
git status
```

```bash
git push
```

```bash
git pull
```

```bash
git reset

git reset --hard <commit>
git reset --hard origin/master
```

