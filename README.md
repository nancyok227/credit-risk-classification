Background

In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

1. Purpose of the Analysis:

This analysis aims to create and evaluate the precision of a data model that forecasts the creditworthiness of potential borrowers from peer-to-peer lending services.

2. Results:
Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.
* Precision Score: 92% --> This means 92% of predicted positives were correct.
* Recall Score: 95% --> this indicates that, out of all created positive predictions, the model was 95% accurate in assessing true positive values.
* Balanced Accuracy Score: 95.20% --> Score for Balanced Accuracy: 95.20% - this indicates that the model's balanced prediction accuracy was 95.20% after accounting for the model's sensitivity (recall and/or true positive rate) and specificity (true negative rate).

3. Summary:
This model has over 95% accuracy in forecasting how the initial loan will be repaid, so I would suggest using it to assess a borrower's creditworthiness. For the lenders to continue operating and turning a profit, it would be simple to incorporate that accuracy range into a business risk profile.


Before You Begin

* Create a new repository for this project called credit-risk-classification. Do not add this homework to an existing repository.
* Clone the new repository to your computer.
* Inside your credit-risk-classification repository, create a folder titled "Credit_Risk."
* Inside the "Credit_Risk" folder, add the credit_risk_classification.ipynb and lending_data.csv files found in the "Starter_Code.zip" file.
* Push your changes to GitHub.

Files

Click on link below https://bootcampspot.instructure.com/courses/3337/assignments/54015?module_item_id=961978
 to visit site for link to download needed files. Whiles on the site, click on click Module 20 Challenge files to download required files needed for project.



Instructions

The instructions for this Challenge are divided into the following subsections:
* Split the Data into Training and Testing Sets
* *Create a Logistic Regression Model with the Original Data
* Write a Credit Risk Analysis Report

Split the Data into Training and Testing Sets

Open the starter code notebook and use it to complete the following steps:
1. Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
2. Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.

NOTE
A value of 0 in the “loan_status” column means that the loan is healthy. A value of 1 means that the loan has a high risk of defaulting.

3. Split the data into training and testing datasets by using train_test_split.

Create a Logistic Regression Model with the Original Data

Use your knowledge of logistic regression to complete the following steps:

1. Fit a logistic regression model by using the training data (X_train and y_train).
2. Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.
3. Evaluate the model’s performance by doing the following:
    * Generate a confusion matrix.
    * Print the classification report.

4. Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

Write a Credit Risk Analysis Report

Write a brief report that includes a summary and analysis of the performance of the machine learning models that you used in this homework. You should write this report as the README.md file included in your GitHub repository.

Structure your report by using the report template that Starter_Code.zip includes, ensuring that it contains the following:

1. An overview of the analysis: Explain the purpose of this analysis.
2. The results: Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.
3. A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.


