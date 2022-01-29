This is a simple flask ToDo app that later deployed on Heroku.



Useful commands for Heroku deployment:

python3 -m pip freeze > requirements.txt

git init

git add .gitignore app.py requirements.txt

git commit -m "Initialize Git repository"


heroku login

git add .

git commit -m "Add Heroku deployment files"

git push heroku master

![image](https://user-images.githubusercontent.com/32337899/151654243-120ae357-efaa-4f6a-8b61-5f8e95ff5d53.png)
