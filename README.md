In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
  The purpose of the analysis is to create supervised machine learning model that will predict if a loan will be health (represented by a 0), or risky, (represented by a 1).
* Explain what financial information the data was on, and what you needed to predict.
  Financial information included Loan Size, Interest Rate, Borrower Income, Debt to Income, Number of Accounts, Derogatory Marks, and Total Debt.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
  The model will predict the loan status as healthy (0) or risky (1).
* Describe the stages of the machine learning process you went through as part of this analysis.
  I split data into labels and features.  The Y variable represented the label "loan status", and the X variable represented the remaining features (Loan Size, Interest Rate, Borrower Income, Debt to Income, Number of Accounts, Derogatory Marks, and Total Debt).  Data was then split using train, test, split method and then fit into a logistic regression model.  Test data was then predicted and then printed into a confusion matrix and classification report.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).
  Logistic regression was used.  Model's performance was evaluted using accuracy, precision and recall scores.

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.
* Accuracy Score was 99%
* Precision Score for healthy loan (0) was 100% and risky loan (1) was 87%.
* Recall Scores for healthy loan (0) was 100% and risky loan (1) was 89%.



## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
