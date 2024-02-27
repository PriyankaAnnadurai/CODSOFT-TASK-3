# CODSOFT-TASK-3
# Customer Churn Prediction
## Import Libraries:

Libraries such as numpy, pandas, plotly.express, and matplotlib.pyplot are imported for data manipulation and visualization.
## Read Data:

The code reads a dataset named "Churn_Modelling.csv" using Pandas into a DataFrame (data_df).
## Data Overview Function:

Defines a function (dataoverview) to provide an overview of the dataset, including the number of rows, features, feature names, missing values, and unique values.
## Display Data Overview:

Calls the dataoverview function to display an overview of the dataset.
## Read Data Again:

Reads the dataset "Churn_Modelling.csv" into another DataFrame (data_df).
## Display Data Head and Info:

Displays the first few rows and information about the dataset, including data types and non-null counts.
## Check for Missing Values:

Checks and displays the count of missing values in each column of the dataset.
## Label Encoding:

Uses LabelEncoder from sklearn.preprocessing to encode categorical features in the dataset.
## Train-Test Split:

Splits the dataset into training and testing sets using train_test_split from sklearn.model_selection.
## Decision Tree Classifier:

Utilizes a Decision Tree Classifier from sklearn.tree to build a classification model.
## Make Predictions and Evaluate:

Makes predictions on the test set and evaluates the accuracy of the model using metrics from sklearn.
### Notes:
The code appears to be building a basic Decision Tree model for predicting the number of products based on certain features.
Some points for consideration are the sufficiency of selected features, the appropriateness of treating the problem as a classification task, and the need for comments to enhance code readability.
This is a high-level summary of the steps taken in the provided code for Customer Churn Prediction.
