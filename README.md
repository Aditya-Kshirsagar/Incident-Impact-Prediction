# Incident-Impact-Prediction

## Table of Content
* General Information
* Explotory data analysis
* Data visualization
* Data balancing
* Feature Selection
* Model building



## General Information
The objective behind this to predict Incident impact. Incident is an event that could lead to loss of, or disruption to, an organization's operations, services or functions.
This is important to classify each incident priority level because based on priority level  we can decide what incident should take care first to minimize the impact on business.
Our goal is to create a machine learning model which will help us in predict incident priority level based on provided information by the end user.

## Data visualization
Data visualization done by using 
* Matplotlib
###### To install matplotlib in Jupyter Notebook use [!pip install matplotlib] version-3.4.2

* Seaborn
###### To install seaborn in Jupyter Notebook use [pip install seaborn] version-0.11.1


## Data balancing
For data balancing 
* iamlearn 
###### To install imblearn in Jupyter Notebook use [!pip install imblearn]

* imbalanced-learn
###### To install imbalanced-learn in Jupyter Notebook use [!pip install imbalanced-learn]
* SMOTEN

## Feature Selection
I useed Sklearn library.

* sklearn
###### To install imbalanced-learn in Jupyter Notebook use [!pip install sklearn]

* DecisionTreeClassifier
* SelectKBest
* chi2
* ExtraTreesClassifier
* mutual_info_classif

## Model building
* Logistic Regression Model (ONE VS REAST)
* Decision Tree
* Random forest
* KNN 
* AdaBoost
* Naïve Byes
* Artificial Neural Network 
* Hyper Parameter Tuning (Optuna)
