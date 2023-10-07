Credit Risk Classification
Instructions
The instructions for this Challenge are divided into the following subsections:

Split the Data into Training and Testing Sets

Create a Logistic Regression Model with the Original Data

Write a Credit Risk Analysis Report

Split the Data into Training and Testing Sets
Open the starter code notebook and use it to complete the following steps:

Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
Split the data into training and testing datasets by using train_test_split.
Create a Logistic Regression Model with the Original Data
Use your knowledge of logistic regression to complete the following steps:

Fit a logistic regression model by using the training data (X_train and y_train).
Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.
Evaluate the model’s performance by doing the following: a. Generate a confusion matrix. b. Print the classification report.
Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?
Credit Risk Analysis Report
Overview of analysis: The goal of this analysis is to create a model that predicts the risk on whether to lend loans to reliable/unreliable borrowers.
Balanced Accuracy Score: 0.995
Precision Score: 1.00
Recall Score: 1.00
F1-Score: 1.00
Summary: The logistic regression model has a perfect F1-score, meaning the logistic model has perfect preision and recall. With this specific data, the model will be perfect for evaluating credit risk; however, I would be cautious when running this model on unseen data. A high F1 score could be a result of overfitting. I would do a confusion matrix to see if this is what causing my F1 score to be high, or if the model is perfect.