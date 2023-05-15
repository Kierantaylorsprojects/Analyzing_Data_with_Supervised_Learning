# Analyzing_Data_with_Supervised_Learning
In this project, I used various techniques to train and evaluate a model based on loan risk. I used a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

## Split the Data into Training and Testing Sets

Open the starter code notebook and use it to complete the following steps:

Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.

Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.

Split the data into training and testing datasets by using train_test_split.

## Create a Logistic Regression Model with the Original Data

Use your knowledge of logistic regression to complete the following steps:

Fit a logistic regression model by using the training data (X_train and y_train).

Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.

Evaluate the model’s performance by doing the following:

Calculate the accuracy score of the model.

Generate a confusion matrix.

Print the classification report.

Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

## Write a Credit Risk Analysis Report

The original dataset model, which had an accuracy of 99%, precision of 87%, and recall of 89%, provided satisfactory results. It can be considered reliable for use. 

On the other hand, the resampled dataset achieved even better outcomes. It obtained 100% accuracy, 87% precision, and 100% recall. This model surpassed the original in terms of recall and accuracy. Notably, the precision remained the same for both models. 

Based on these findings, I recommend utilizing the resampled model, although both models can be used to assess borrower creditworthiness. To evaluate performance, it is important to consider both false positives and false negatives. Both factors carry significance, and neither should be overlooked.
