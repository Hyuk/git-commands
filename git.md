# Git Command

## First Setup
```bash
git init
git add file.md
git commit -m "some comment"
git remote add origin https://github.repository.address
git push -u origin master
```

## Restart Setup
when you see git command error below, it will help fix the error \
git error: failed to push some refs to 'master'
```bash
git pull --rebase origin master
git push origin master
```