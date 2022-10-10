# assignement-1-git-task2-github-pages
You can find the complete code <a href='https://github.com/ni3choudhary/DataScience-Industry-Ready-Projects'>here</a>.

## Rainfall-Prediction-In-Australia-Deployment

[![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-blue.svg)](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package) ![Python 3.6](https://img.shields.io/badge/Python-3.6-brightgreen.svg)

• This repository consists of files required for end to end implementation of Rain Prediction in Australia ___Machine Learning Web App___ created with ___Flask___ on ___Heroku___ platform.

### Problem statement:
A ML project with EDA and model that helps in predicting next-day rain by training classification models on the target variable RainTomorrow.

### Dataset
You can find the dataset [here.](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package)

### Dependencies:
* Python 
* Pandas
* Numpy
* Matplotlib
* Seaborn
* Scikit-Learn
* Catboost
* Tensorflow
* Flask 

## setup
To create a project from scratch use following steps - -

- Clone the repository : https://github.com/ni3choudhary/Rainfall-Prediction-In-Australia-Deployment.git
- Inside the project root directory, Create Python Virtual Environment using below command.
```console
$ python3 -m venv venv
``` 

Activate Virtual Environment
```console
$ .venv/bin/activate 
          OR
$ .\venv\Scripts\activate
```
Install Libraries using below command
```console
$ pip install -r requirements.txt
```
- Run jupyter notebook to get the pickle file inside **Model** directory.

- Now run **app.py** on terminal to start local server.
```console
$ python app.py
```

• If you want to view the deployed model, click on the following link: Deployed at: https://rainfall-prediction-australia.herokuapp.com/
