# Titanic Logistic Regression Classifier 🚢

This project implements a machine-learning solution for the *Training data* in the famous *Titanic dataset*(https://www.kaggle.com/c/titanic/data?select=train.csv) from the *Kaggle competition*. The goal is to predict whether a passenger survived or not based on various features, using Logistic Regression. Below is a breakdown of the step-by-step process:

# Step-by-Step Process:

## 1. Importing Libraries:
The project begins by importing necessary libraries like Pandas, NumPy, and Scikit-learn for data manipulation, exploration, and modeling.

## 2. Loading the Dataset:
The Titanic dataset is loaded using Pandas. 
The data consists of features like passenger class (Pclass), age, fare, and other demographic information.

## 3. Data Cleaning:
The dataset is cleaned by handling missing values. In particular:
Missing values in the Age column are filled with the median age.
The Embarked column's missing values are filled with the mode.

## 4. Feature Engineering:
Categorical variables like Sex and Embarked are converted into numeric formats using dummy variables.
Unnecessary columns such as Name, Ticket, and Cabin are dropped, as they don't contribute to the model's performance.

## 5. Train-Test Split:
The dataset is split into training and testing sets using an 80-20 ratio to validate the model's performance later.

## 6. Model Building - Logistic Regression:
A Logistic Regression model is used to fit the training data and make predictions on the testing set.

## 7. Model Evaluation:
1. *Accuracy:* The accuracy of the model is evaluated, and the Logistic Regression classifier performs well on the test set.
2. *Classification Report:* Precision, recall, and F1-scores are calculated to assess the model's performance on both survived and non-survived classes.
3. *Confusion Matrix:* A confusion matrix is created to visualize true positive, true negative, false positive, and false negative predictions.

## 8. Conclusion:
The model achieves an accuracy of 83%, with reasonable precision and recall for both survived and non-survived passengers.

## Key Skills Demonstrated:
1. Data cleaning and preprocessing
2. Feature engineering with dummy variables
3. Implementing and evaluating machine learning models
4. Interpreting classification reports and confusion matrices

*This repository is a hands-on demonstration of applying Logistic Regression to a real-world dataset, illustrating the steps taken in a typical data science workflow.*
