# Cotton-Disease-Predictor

![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-blue.svg) ![Python 3.6](https://img.shields.io/badge/Python-3.6-brightgreen.svg) ![Scikit-Learn](https://img.shields.io/badge/Library-ScikitLearn-orange.svg)![Keras](https://img.shields.io/badge/Keras-yellow.svg)![Tensorflow](https://img.shields.io/badge/Tensorflow-cyan.svg)

This repository consists of files required for end to end implementation and deployment of Deep Learning Cotton Disease Classification web application created with flask and deployed on the Heroku platform.

## Table of Contents
  * [App Link](#app-link)
  * [About the App](#about-the-app)
  * [Deployement on Heroku](#deployement-on-heroku)
  * [Technologies Used](#technologies-used)


## App Link
If you want to view the deployed model, click on the following link:<br />
[https://cottondiseasepredict.herokuapp.com/](https://cottondiseasepredict.herokuapp.com/)

A glimpse of the web app:

![GIF](readme_resources/diseased_cotton.gif)

• If you encounter this webapp as shown in the picture given below, it is occuring just because **free dynos for this particular month provided by the Heroku platform have been completely used.** You can access the webpage on 1st of the next month.

• Sorry for the inconvenience.

![Heroku-Error](readme_resources/application-error-heroku.png)

## About the App
The Cotton Disease Predictor is a flask web application which classifies a cotton plant/leaf image into four categories viz. diseased cotton leaf, diseased cotton plant, fresh cotton leaf, and fresh cotton plant. The code is written in Python 3.6.10 and makes use of Keras and Tensorflow libraries in developing an InceptionV3 based image classification web application. 

If you don't have Python installed, you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```

## Deployement on Heroku
Login or signup in order to create virtual app. You can either connect your github profile or download ctl to manually to deploy this project.

[![](https://i.imgur.com/dKmlpqX.png)](https://heroku.com)

The next step would be to follow the instruction given in the [Heroku Documentation](https://devcenter.heroku.com/articles/getting-started-with-python) to deploy a web app.

## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://number1.co.za/wp-content/uploads/2017/10/gunicorn_logo-300x85.png" width=280>](https://gunicorn.org) [<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=200>](https://scikit-learn.org/stable/) 

## Please do ⭐ the repository, if it helped you in anyway.
