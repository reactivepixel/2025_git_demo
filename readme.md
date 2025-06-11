# Workflow

## Initial workflow
1. [x] git init
1. [x] stage gitignore
2. [x] commit gitignore
3. [x] push to remote\
4. [x] create dev branch
5. [x] push dev branch to remote

## Workflow for Feature Branches
1. [x] Ensure Dev branch is up to date
2. [x] Create and checkout a new branch from dev
3. [x] Make changes and commit them

# Commands

```
git init
git add .gitignore
git status
git commit -m "Initial commit"
git add -A
git remote add origin <remote-url>
git push origin <branch-name>
git branch
git checkout -b <new-branch-name>
```