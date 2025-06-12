### linking project with my github
### first create github repo without readme file

git init
git config --global user.email "shehab10111995@gmail.com"
git config --global user.name "HASAN9519"
git add --a
git commit -m "initial commit"
git branch -M main

### linking project with created github repo 
git remote add origin https://github.com/HASAN9519/IBM_FullStackAppDevCapstoneProject.git
git push -u origin main