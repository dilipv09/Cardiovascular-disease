# Cardiovascular Disease Analysis

# Problem Statement
The objective is to develop a classifier to identify the presence of cardiovascular disease.

# Dataset description
The cardiovascular disease [dataset](https://www.kaggle.com/sulianova/cardiovascular-disease-dataset) is an open-source dataset found on Kaggle. The data consists of 70,000 patient records and contains 11 features (4 Factual information, 4 examination, and 3 patient social information) and a target. Dataset is almost balanced with 34,979 having cardiovascular disease and 35,021 not having cardiovascular disease.

* Age (Factual information)
* Height (Factual information)
* Weight (Factual information)
* Gender (Factual information)
* Systolic blood pressure (Examination)
* Diastolic blood pressure (Examination)
* Cholesterol (Examination)
* Glucose (Examination)
* Smoking (Social information)
* Alcohol intake (Social information)
* Physical activity (Social information)

# Overview
In this study, I explore several machine learning approaches to detect the presence of cardiovascular disease. I leverage traditional machine learning techniques including a Logistic Regression, a KNN classifier, a support vector machine (SVM) with a Gaussian RBF kernel, a Random forest classifier, a Naive Bayes classifier, and a XGBoost classifier. Furthermore, I utilize grid search for extracting best hyper parameters which could help in selecting the best parmeters to choose to yield the good results. 

To detect cardiovascular disease with above methods, I also investigate which data features (factual, examination and social information) are most expressive of disease and useful for predicting the disease. 

# Results
Below are the results of implemented machine learning methods used and observed that XGBoost is giving the best accuracy out of all.   
* Logistic Regression - 72.0
* KNN classifier - 69.15 
* Support vector machine - 72.92 
* Random forest classifier - 73.63
* Naive Bayes classifier - 59.48
* XGBoost classifier - 73.79
