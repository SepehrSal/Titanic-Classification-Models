# Titanic-Classification-Models
for this project we will be working with the [Titanic Data Set from Kaggle](https://www.kaggle.com/c/titanic).   We'll be trying to predict a classification- survival or deceased.

##steps:
*Exploratory Data Analysis
*Data Cleaning
*Converting Categorical Features 
*Building  Regression models

##Exploratory Data Analysis
We can use seaborn to create a simple heatmap to see where we are missing data:

![image](https://user-images.githubusercontent.com/121250443/218646309-48eb03c1-b044-46b6-b7e5-fcf1c5f633cd.png)

ticket class:

![image](https://user-images.githubusercontent.com/121250443/218646419-86f4fbda-347d-4ae0-bcb0-2d52a6b007a8.png)

##Data Cleaning

 *used average age values to impute based on Pclass for Age.
 *StandardScaler
 
 ## Converting Categorical Features 
 
convert categorical features to dummy variables using pandas

# Building  Regression models
*LogisticRegression
*KNeighborsClassifier
*RandomForestClassifier
* calculating classification_report, f1_score, confusion_matrix to select best fit.
