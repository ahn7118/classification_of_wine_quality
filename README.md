# classification_of_wine_quality

# (1) Introduction

In this project, main purpose is to find factors that are most important to wine quality and to predict such quality. The original data is from following reference (Kaggle URL https://www.kaggle.com/uciml/red-wine-quality-cortez-et-al-2009). Dataset is composed of quality of wine and other variables such as fixed acidity. Based on this particular dataset, 6 machine learning models are used in order to predict wine quality. Six machine learning models are Naive Bayes, Decision Tree, Random Forest, KNN, Logistic Regression and SVM. 

--------------------------------------------

# (2) Steps of the Project

## 1) Step 0 - Preparing Data set

In many cases, raw data is not so suitable or clean for analysis that I want to conduct. It is essential to adjust those messy data into clean data form. There are two things that should be transformed in this project. First of all, dependent variable, wine quality, should be changed into binary scale instead of sacle from 0 to 10. Second, each variable scale should be normalized beforehand in order prevent statistical errors. 


## 2) Step 1 - Simple Analysis with Machine Learning Model

In first analysis, all six models is going to be run without setting specific model parameters, leaving those as default conditions. Then, I would like to visualize those results first. The reason of presenting this simple version is to show improvenment which is going to be made in next step. 



## 3) Step 2 - Searching for Optimal Parameter with Grid Search

With grid search package, each model's parameter condition would be compared and tested. Among a number of cases, only one best result and its parameter condition would be selected and show the improvements compared to former step. As a result, it is possible to show which machine learning model is the most suitable model for this red wine dataset. 
