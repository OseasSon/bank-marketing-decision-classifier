This project involves building a logistic regression model to classify the outcome of a bank marketing campaign. The workflow includes loading necessary libraries, reading the data from a file, preprocessing the data to handle missing values and encode categorical variables, and then splitting the data into training and testing sets. The logistic regression model is trained on the training set, and its performance is evaluated using the test set. Additionally, the model is used to make predictions on a separate queries dataset, and the results are saved to a file. The code also includes a post-prediction analysis to understand the impact of certain features on the predictions.

These are the two relvant files:

1. trainingset.txt: this file contains the training instances. It contains the descriptive
features and the target feature level for each instance.

2. queries.txt: this file contains the query instances. It contains the descriptive
features for each instance. The target feature level has been overwritten
with ‘?’
