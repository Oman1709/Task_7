# task7
Titanic Survival Prediction - Logistic Regression

PROJECT OVERVIEW

This project implements a Logistic Regression model to predict the survival of passengers on the Titanic. Using the Titanic dataset, the goal is to perform binary classification to determine whether a passenger survived (1) or not (0) based on features like age, sex, and fare.

DATASET

The project uses the Kaggle Titanic Dataset (or Seaborn's built-in version). The features analyzed include:

Age: Handled missing values using median strategy.

Sex: Encoded using OneHotEncoding.

Fare: Scaled using StandardScaler for stable model training.

Embarked: Handled missing values using mode strategy.

STEPS FOLLOWED

Data Cleaning: Removed unnecessary columns like PassengerId and Name.

Preprocessing: Handled missing data and performed categorical encoding/feature scaling.

Model Training: Split the data into train-test sets and trained a Logistic Regression model.

Evaluation: Evaluated the model using Accuracy, Precision, Recall, and F1-score.

PERFORMANCE RESULTS

The model's performance was measured using the following deliverables:

Confusion Matrix: Visualizes the True Positives, True Negatives, False Positives, and False Negatives.

ROC Curve & AUC Score: Evaluates the model's ability to distinguish between classes.

TOOLS USED

Language: Python

Libraries: Pandas, Scikit-learn, Matplotlib, Seaborn
