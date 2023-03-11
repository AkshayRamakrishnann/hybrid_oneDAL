# Hybrid Random Forest and SVM for Iris Flower Classification
![download-_3_](https://user-images.githubusercontent.com/111365771/224471710-8b48dd90-a793-46be-a7e0-c88be181fdee.jpg)


## Introduction
The Iris flower dataset is a well-known multivariate dataset introduced by Sir Ronald Fisher in 1936. It consists of 50 samples from each of three species of Iris (Iris setosa, Iris virginica, and Iris versicolor), making a total of 150 samples. Each sample contains measurements of the sepal length, sepal width, petal length, and petal width of the flower. The goal of this project is to build a machine learning model that can classify the species of Iris based on these measurements.

In this project, we will use a hybrid model consisting of Random Forest and Support Vector Machine (SVM) classifiers. Random Forest will be used to identify the most important features of the dataset, and SVM will be used to classify the data based on these features.

## Dataset
The Iris flower dataset is built into scikit-learn and can be loaded using the load_iris function. This dataset contains 150 samples with 4 features each, and 3 possible target classes.

## Models Used
Two models will be used in this project: Random Forest and SVM.

### Random Forest
Random Forest is a decision tree-based ensemble learning algorithm. It works by constructing a multitude of decision trees at training time and outputting the class that is the mode of the classes (classification) or mean prediction (regression) of the individual trees.

In this project, we will use Random Forest to identify the most important features of the Iris dataset.

### SVM
SVM is a popular supervised learning algorithm that is often used for classification tasks. It works by finding the hyperplane that maximizes the margin between two classes.

In this project, we will use SVM to classify the Iris dataset based on the most important features identified by Random Forest.

## OneAPI
OneAPI is a set of industry standards that allow developers to write code that can run on a variety of hardware architectures. In this project, we will use OneAPI to leverage the parallel processing capabilities of our computer's CPU.

## Methods and Materials
We will use Python 3 with the following libraries:

-> scikit-learn for building the machine learning models

-> NumPy for numerical computing

-> Matplotlib for data visualization

## Results
After training and testing the hybrid Random Forest and SVM model, we achieved an accuracy of 96.67% on the Iris flower dataset. The decision boundary of the hybrid model is shown below:

![download (4)](https://user-images.githubusercontent.com/111365771/224471652-e759a6f1-9be7-422b-a656-3012674385a0.png)
Decision Boundary

## Conclusion
In this project, we demonstrated the use of a hybrid model consisting of Random Forest and SVM for classification tasks. We also used OneAPI to leverage the parallel processing capabilities of our computer's CPU. While our model achieved an accuracy of 60%, there is still room for improvement through hyperparameter tuning and feature engineering.
