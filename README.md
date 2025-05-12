# Logistic_Regression_Model
# Predicting Student Exam Outcome using Logistic Regression
 
This mini-project uses **Logistic Regression**, a machine learning classification algorithm, to predict whether a student will pass or fail an exam based on the number of hours they studied.
 
## Overview
 
Logistic Regression is ideal for **binary classification problems** (e.g., pass/fail, yes/no). In this project, we simulate a small dataset of students and use logistic regression to predict outcomes and visualize the probability curve.
 
---
 
## Project Steps
 
### 1. Import Libraries
 
We use:
- **pandas** for data handling
- **numpy** for numerical operations
- **matplotlib** for plotting
- **scikit-learn**'s `LogisticRegression` for the model
 
### 2. Create the Dataset
 
A simple dataset is created with:
- `Hours_Studied`: Number of hours a student studied
- `Passed`: 0 (failed) or 1 (passed)
 
### 3. Visualize the Data
 
A scatter plot is used to show the relationship between study time and exam outcome.
 
### 4. Train the Logistic Regression Model
 
The dataset is split into:
- Feature `X`: Hours studied
- Label `y`: Passed or not
 
We then train the model using `model.fit(X, y)`.
 
### 5. Make Predictions
 
We use the trained model to predict whether a student studying, for example, 4.5 hours will pass.
 
### 6. Plot the Logistic Curve
 
We generate a smooth curve using `predict_proba` to visualize how the probability of passing increases with study hours.
 
---
 
## Outcome
 
- Understand the difference between `predict()` and `predict_proba()`
- Learn how coefficients and intercept are calculated by the model during training
- See how Logistic Regression fits a **sigmoid curve** to binary data
 
---
 
## Technologies Used
 
- Python
- Pandas
- Numpy
- Matplotlib
- Scikit-learn
 
---
 
## Author
 
Pranathi — sharing and learning ML through simple projects.
 
