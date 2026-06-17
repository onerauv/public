# The Full Command Line Of `Git`
## user.name and user.email
```
git config --global user.name ""
```
```
git config --global user.email ""
```

## git clone
```clone
git clone <link>
```
## git status
```status
git status
```

## add file
```
git add "file-name"
```
## commit
```
git commit -m 'update file'
```
## when make a new local repo

## git init
```init
git init
```
## connect remote to local 
```connect
git remote add origin <github-link>
```
## git remote set
```set
git remote rename origin <new-name>
```
## to check remote verfiy
```check
git remote -v
```
## branch check
```check
git branch
```
## branch rename
```modify
git branch -M main
```
```modify2
git branch -m old-name new-name
```
## new branch
```new
git checkout -b <new-branch>
```
```new2
git branch <new-branch>
```
```new3
git checkout -b my-branch
```
```new4
git switch -c my-branch
```
## branch change or navigate ( change branch)
```change
git checkout <branch-name>
```
## delete a branch
```del
git branch -d <branch-name>
```
## force delete a branch
```del
git branch -D <branch-name>
```
## delete branch for github
```del
git push origin --delete branch-name
```
## reset commit
```commit
git reset <commit>
```
```commit2
git reset --soft <commit>
```
```hard
git reset --hard <commit>
```