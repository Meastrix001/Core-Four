# ChocoLoco

## 

npm i git-flow

### 1. go to develop branch
- git chechout develop

### 2. nieuwe feature starten
- git flow feature start `name` (no backticks)

work on feature, after finished:
### 3. prepare to merge

- git add .
- git commit -m "message"

### 4. merging
- git flow finish feature `name` (no backticks)

### 4. this deletes the current feature branch, en redirects you to the develop branch"
- git push
- 
### 5. merge develop with main 
- git checkout main
- git merge development
