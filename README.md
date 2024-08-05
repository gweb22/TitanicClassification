# Titanic Classification Project

## Overview

This project aims to develop a machine learning model to predict the survival of passengers aboard the Titanic. The model utilizes various features, such as age, gender, and passenger class, to make predictions. The project also explores historical insights and contemporary safety discussions.

## Dataset

The dataset used in this project is the Titanic dataset, available on [Kaggle](https://www.kaggle.com/c/titanic). It includes information on passengers, such as:

- **PassengerId**: A unique identifier for each passenger
- **Pclass**: The ticket class (1st, 2nd, or 3rd)
- **Name**: Passenger's name
- **Sex**: Gender of the passenger
- **Age**: Age of the passenger
- **SibSp**: Number of siblings or spouses aboard
- **Parch**: Number of parents or children aboard
- **Ticket**: Ticket number
- **Fare**: Ticket fare
- **Cabin**: Cabin number
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Features Engineering and Analysis

Key aspects of the feature engineering process include:

1. **Handling Missing Values**: Imputed missing values in the `Age` and `Embarked` columns.
2. **Encoding Categorical Variables**: Converted categorical variables, such as `Sex` and `Embarked`, into numerical formats.
3. **Creating New Features**: Created new features like `FamilySize`, `IsAlone`, and `Title` from existing data.

## Model Development

Several machine learning models were explored, including:

- **Logistic Regression**
- **Random Forest**
- **Support Vector Machines (SVM)**
- **K-Nearest Neighbors (KNN)**

The final model was selected based on accuracy, precision, recall, and F1 score metrics.

## Results

The model achieved an accuracy of **83.22%** on the test dataset. Detailed results, including the coefficient table and feature importances, can be found in the project notebook.

## Conclusion

This project provided valuable insights into the factors that influenced passenger survival on the Titanic. The findings highlighted the importance of age, gender, and passenger class in survival outcomes. The project also offered historical perspectives and contributed to ongoing discussions about safety measures.

## Repository Structure

- `Titanic(7).html`: The main project report containing all analysis, visualizations, and results.
- `README.md`: This README file.
- `train.csv`: Training data provided by kaggle
- `test.csv`: Testing data provided by kaggle
