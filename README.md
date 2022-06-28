# Telecom-Customer-Churn-Prediction
This is a supervised machine learning project using telecom customer data to predict customers that would churn based on customer Age Group, Relationship Status, Subscribed Services, Charges, and Finantial Responsibilities, .
## Project Guide
In this project i made use of Pandas, Numpy, train_test_split, RandomForestClassifier, SVM, LogisticRegression, cross_val_score, and StandardScaler

This project was carried out using the following steps:
* Importing the necessary libraries 
* Reading CSV into a dataframe
* Cleaning data by
  * Dropping irrelevant columns
  * Dropping rows with empty columns
  * Applying appropriate column format (astype(float))
  * Checking for outliers using Z-score
* Creating dummy columns for machine learning
* Grouping dependent and independent variables and scaling the independent variables appropriately
* Use Cross Validation Score to determine the best performing model
* Train the best performing model to make predictions 
* Make predictions
