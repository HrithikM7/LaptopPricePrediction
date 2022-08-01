# LaptopPricePrediction

<img src="https://m.media-amazon.com/images/I/718ETwvLVOL._SY355_.jpg" >

## Quick Intro
Enclosed is a Jupyter Notebook which uses various Machine Learning Models to predict the price of a laptop.

## Dataset
* Download the dataset for custom training.
* https://www.kaggle.com/muhammetvarl/laptop-price 

## Problem Statement
Based on the various columns available (i.e Ram, Memory, Size of Display Screen, etc...), our task is predict the price of the given laptop.                                                                                                                                     
## Approach
I used several features (i.e Company, Screen Resolution, CPU, etc...) to predict our target variable (i.e Price) and split the data into training and testing datasets.
I tried to cover every step of the machine learning pipeline while making this project. I started out by performing basic EDA to get more insight about the data at hand. Following which, Feature encoding, Feature selection, Feature Transformation, and Feature scaling were performed before training the model. I implemented several machine learning algorithms such as Linear Regression, KNeighborsRegressor, Decision Tree, Random Forest,Gradient Boosting, and Ada Boosting to model and fit the data. GridSearchCV was used to perform hyperparameter tuning to get the best parameters for each algorithm used. To quantify the models, I used the metrics of mean_absolute_score.

## Result
In this notebook I implemented Linear Regression, KNeighborsRegressor, Decision Tree, Random Forest,Gradient Boost, and Ada Boost for a machine learning supervised regression task. The best result that was obtained was : Gradient Boosting w/ Mean Absolute Error : 0.1572

## Importance
The field of machine learning has seen a tremendous growth over the past few years, and is only going to grow further in the future. 
Predicting the price of a laptop has many use cases and will ultimately benefit both the buyers as well as the sellers who sell various laptops. This model can be used to even check whether a particular laptop in the store is over-priced or under-priced.

## Authors

Hrithik Maddirala  
[@hrithik_m245](https://www.linkedin.com/in/hrithik-maddirala/)


<img src="DSC_0037-01-01.jpeg" width="100">
