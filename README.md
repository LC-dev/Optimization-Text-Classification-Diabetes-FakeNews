# Optimization & Text Classsification on 'Diabetes' and 'Fake News' Datasets

## Project Status 🕒

Completed 🙌

## Table of Contents 📜

* [Project Objectives](#objectives)
* [Methods](#methods)
* [Technologies](#tech)
* [Results](#results)
* [Setup](#setup)
* [Credits](#cred)

<a name="objectives"></a>
<a name="methods"></a>
<a name="tech"></a>
<a name="results"></a>
<a name="setup"></a>
<a name="cred"></a>

## Project Objectives ✅ 

* Gain insight into the optimization process of gradient based methods by implementing variations of gradient descent and analyzing their impact on convergence speed, using Logisitc Regression.
* Explore text-specific pre-processing techniques and use Logistic Regression for binary classification 

## Methods ✍️

* Gradient descent (classic, mini-batch SGD, momentum gradient descent)
* Data visualization
* Data preprocessing
* Logistic Regression
* Hyperparameter tuning 


## Technologies 💻

* Python 3.7.12
* sklearn
* numpy
* pandas
* plotly
* matplotlib
* contractions
* re

## Results 📈

* Gradient descent:
  * Slow convergence on non-normalized data
  * Significantly faster convergence using mini-batch SGD (B=8, epochs=25) than GD (epochs=1350), normalized data: 75% accuracy
  * Negligeable effect of momenteum GD on normalized data

* Text classification:
  * 76.5% accuracy

## Setup 👩‍💻

* Install dependencies 
* Clone repo
* Run notebook

## Variables ⌨️
### Part 1: Optimization
```
data_train = pd.read_csv('insert path of diabetes_train.csv')
data_val = pd.read_csv('diabetes_val.csv')
```
### Part 2: Text Classification
```
df_train= pd.read_csv('insert path of fake_news_train.csv')
df_val = pd.read_csv('insert path of fake_news_val.csv')
df_test = pd.read_csv('insert path of fake_news_test.csv')
```

## Credits 🏅

Thank you to my awesome team for working on this project! 
