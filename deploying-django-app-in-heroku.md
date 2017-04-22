* Make sure heroku client is installed
```
sudo apt-get install software-properties-common # debian only
sudo add-apt-repository "deb https://cli-assets.heroku.com/branches/stable/apt ./"
curl -L https://cli-assets.heroku.com/apt/release.key | sudo apt-key add -
sudo apt-get update
sudo apt-get install heroku
```

* Install django 1.10
```
pip install django==1.10
```

* Create django project using heroku template
```
django-admin.py startproject --template=https://github.com/heroku/heroku-django-template/archive/master.zip --name=Procfile <project-name>
```

* Create apps
```
cd <project-name>
python manage.py startapp <app-name>
```

* Commit the code to github
```
git init
git add .
git commit -m 'app ready to be deployed in heroku'
```

* Create heroku app
```
heroku create
git push heroku master
```

* Upload the code
```
```

*TODO
```
Deploy database-backed app
Get CI-CD setup ready
```
