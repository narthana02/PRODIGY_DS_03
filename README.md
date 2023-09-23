# PRODIGY_DS_03
# Task-03
Build a decision tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. Use a dataset such as the Bank Marketing dataset from the UCI Machine Learning Repository.

Dataset :- https://www.kaggle.com/datasets/janiobachmann/bank-marketing-dataset
# Explanation and Inference:

Data Cleaning and Preprocessing:

Check for missing values and remove rows with 'unknown' values in the 'poutcome' column.
Encode categorical variables using label encoding.

EDA (Exploratory Data Analysis):

Visualize the distribution of the target variable 'deposit' to understand class balance.
Visualize the correlation matrix to identify relationships between features.
Split the data into training and testing sets (80% train, 20% test).

Build a Decision Tree Classifier:

Initialize and train a DecisionTreeClassifier with the training data.

Evaluate the model:

Calculate accuracy, confusion matrix, and classification report to assess the model's performance.

Visualize the Decision Tree:

Plot the decision tree to understand the rules and decisions made by the model.
