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


### creating a superuser and displaying its user information on the main page
python manage.py createsuperuser

username: hasan9519

email: <shehab10111995@gmail.com>

Password: dragonball95

### Create initial migrations and generate the database schema
python manage.py makemigrations

python manage.py migrate

### Start the development server, shift+< to inclose them in <>
python manage.py runserver