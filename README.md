# Titanic Survival Prediction

This repository contains a machine learning project that uses logistic regression to predict passenger survival on the Titanic based on various features. The project evaluates the model's performance and identifies areas for improvement.

## Dataset

The dataset used in this project contains the following features:

- **PassengerId**: Unique identifier for each passenger
- **Survived**: Survival status (0 = No, 1 = Yes)
- **Pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **Name**: Passenger's name
- **Sex**: Passenger's gender
- **Age**: Passenger's age
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Ticket**: Ticket number
- **Fare**: Ticket fare
- **Cabin**: Cabin number
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

**Missing Values:**

- **Age**: 177 missing values
- **Cabin**: 687 missing values
- **Embarked**: 2 missing values

## Model Performance

The logistic regression model was used to classify passengers as either "Survived" or "Not Survived." Here is the performance summary:

- **Correctly Identified as Not Survived:** 94 samples
- **Correctly Identified as Survived:** 45 samples
- **False Positives (Survived but should be Not Survived):** 16 samples
- **False Negatives (Not Survived but should be Survived):** 24 samples

**Overall Accuracy:** The model correctly classified 139 out of 179 samples, resulting in an accuracy of about 77.65%. 

## Performance Review

While the model achieved a reasonable accuracy, there is a notable number of false positives (16) and false negatives (24), suggesting room for improvement. Future enhancements could focus on feature engineering, addressing missing data, and exploring other machine learning algorithms to improve classification accuracy.
