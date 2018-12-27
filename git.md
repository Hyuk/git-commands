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
```bash
git pull --rebase origin master
git push origin master
```