This is a simple flask ToDo app deployed on Heroku.



Useful commands for Heroku deployment:

python3 -m pip freeze > requirements.txt
git init
git add .gitignore app.py requirements.txt
git commit -m "Initialize Git repository"

heroku login

git add .
git commit -m "Add Heroku deployment files"
git push heroku master
