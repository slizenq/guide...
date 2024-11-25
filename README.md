```
git init
git checkout -b main
git add .
git commit -m 'first commit' 
git remote add origin https://github.com/slizenq/guide.git
git push --force origin main

// Первый пулл прописывать если гит не видит удаленную ветку
git branch --set-upstream-to=origin/main main
git pull
```
