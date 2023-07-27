# credit-risk-classification

### Data Preparation:

Ensure you have the Lending Data in CSV format with the "loan_status" column as the target variable.
Load the data into Python using Pandas.

### Data Splitting:

Split the data into features (X) and the target variable (y).
Use the train_test_split function from scikit-learn to create training and testing sets.

### Model Training:

Import the LogisticRegression module from scikit-learn.
Instantiate the Logistic Regression model with desired parameters.
Fit the model on the training data using the fit method.

### Model Prediction:

Make predictions on the testing data using the trained model and the predict method.

### Model Evaluation:

Assess the model's performance using the confusion matrix and classification report.
Use the confusion_matrix and classification_report functions from scikit-learn.

### Interpretation and Conclusion:

Analyze the results to understand how well the model predicts loan default status (0 or 1).
Draw insights and conclusions about the model's performance.
