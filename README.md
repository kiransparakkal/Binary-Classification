# Binary-Classification
Project Goal

This project aims to compare the performance of various supervised learning methods on a binary classification problem, which will help you understand each classification algorithm's advantages and disadvantages.

Project Introduction

Write python code to compare the performance of three different classification methods. You can choose any three classification methods based on the following list:

Decision Tree
Random Forest
SVM/kernel SVM
KNN
Naïve Bayes
Logistic Regression
You can refer to any python libraries (pandas, numpy, matplotlib, seaborn, scikit-learn, …) to implement the classification methods. However, your code must include the following steps:

Indicate the imported packages/libraries
Load the dataset and print the data information
Understand the dataset
Print out the number of samples for each class in the dataset
Plot some figures to visualize the dataset (e.g., histogram, etc.)
For each class, print out the statistical description of features (e.g., the input variable x), such as mean, std, max and min values, etc.
Split data into a training dataset and a testing dataset (i.e., 80% v.s. 20%)
For each classification algorithm you chose, please complete the below steps in Python:
Train the model using the training dataset.
If there are hyperparameters in the algorithm, please use K-Fold Cross Validation (e.g., you could choose k = 5 for K-Fold Cross Validation) to tune the hyperparameters of the algorithm (e.g., explore the best value for hyperparameter “k” for KNN, or the best kernel for kernel SVM, etc.).
Please use different evaluation metrics, including precision, recall, accuracy, and F1-Score, to pick up a model that gives you the best result on the validation dataset (e.g., via the Cross Validation, for kNN model, which k value gives the best precision, recall, accuracy, and F1-Score respectively)
Test the model (the best one you obtained from the above stage) on the testing dataset
Plot the confusion matrix
Please use different evaluation metrics, including precision, recall, accuracy, and F1-Score, to report the performance of the algorithm, you can use tables or plot figures to summarize the results
