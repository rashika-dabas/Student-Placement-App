## IDE: PyCharm
## Steps:
* Create a new project in PyCharm with python 3.10 and a new virtual environment (.idea and venv folder will be automatically created)
* Install just once in terminal with venv:
1. pip install flask
2. pip install numpy
3. pip install sklearn
* To run the app in terminal with venv, use the command python app.py or play button at top
* Test API responses via Postman software
* For errors, stop & rerun the app and then repeat the command
* Install Heroku Client and then check installation using heroku --version via cmd as administrator
* In terminal with venv,
1. heroku login
2. git init
3. heroku git:remote -a rashika-app
4. git add .
5. git commit -am "deploying student placement app"
6. git push heroku main
