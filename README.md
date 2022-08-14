# Store Sales Prediction

Nowadays, shopping malls and Big Marts keep track of individual item sales data in
order to forecast future client demand and adjust inventory management. In a data
warehouse, these data stores hold a significant amount of consumer information and
particular item details. By mining the data store from the data warehouse, more
anomalies and common patterns can be discovered.

# Objective

We have to build a solution that should able to predict the sales of the
different stores of Big Mart according to the provided dataset.

# Project Demo


# Application link

https://storesaleprediction.herokuapp.com/

## Create a file "Dockerfile" with below content

```
FROM python:3.7
COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
ENTRYPOINT [ "python" ]
CMD [ "main.py" ]
```

## Create a "Procfile" with following content
```
web: gunicorn main:app
```


## to create requirements.txt

```buildoutcfg
pip freeze>requirements.txt
```

## initialize git repo

```
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin <github_url>
git push -u origin main
```

## create a account at circle ci

<a href="https://circleci.com/login/">Circle CI</a>


## Select project setting in CircleCI and below environment variable

```
DOCKERHUB_USER
DOCKER_HUB_PASSWORD_USER
HEROKU_API_KEY
HEROKU_APP_NAME
HEROKU_EMAIL_ADDRESS
DOCKER_IMAGE_NAME=wafercircle3270303
```


## to update the modification

```
git add .
git commit -m "proper message"
git push 
```


## :hammer_and_wrench: Requirements
- python 3.x
- Flask
- pandas
- pymongo
- kneed
- scikit-learn
- xgboost

# Contributor
- Saransh
