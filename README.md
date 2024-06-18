# Credit-Risk-Classification

## Overview ##
The main purpose of this analysis is to predict credit risk for loan applicants based on certain financial information based on variables like income, debt-to-income ratio, credit score, etc. The prediction target is good or bad credit risk and to see the distribution of the good and bad credit risk applicants. Machine learning was used during this process to split the data into training and testing sets for model training to evaluate accuracy, precision, recall, and F1 score, and potentially model tuning to improve performance. The model used was logistic regression in order to generate a confusion matrix and evaluate results.

## Results ##
- **Precision**: The ratio of correctly predicted positive observations to the total predicted positive observations.
  - For Class 0: Precision is 1.00, indicating the model is 100% accurate when predicting a sample as Class 0 (healthy loans).
  - For Class 1: Precision is 0.85, meaning the model is 85% accurate when predicting a sample as Class 1 (high-risk loans).

- **Recall**: The ratio of correctly predicted positive observations to all actual positive observations.
  - For Class 0: Recall is 0.99, meaning the model correctly identifies 99% of the actual Class 0 samples.
  - For Class 1: Recall is 0.91, indicating the model captures 91% of the actual Class 1 samples.

- **F1-score**: The F1-score is the harmonic mean of precision and recall (the balance of the two metrics).
  - For Class 0: The F1-score is 1.00, showing a perfect balance between precision and recall for Class 0.
  - For Class 1: The F1-score is 0.88, indicating a slightly lower balance between precision and recall for Class 1.

- **Support**: The number of actual occurrences of each class in the dataset.
  - For Class 0: There are 18,765 instances of Class 0.
  - For Class 1: There are 619 instances of Class 1.

- **Accuracy**: The overall correctness of the model, calculated as the ratio of correctly predicted samples to the total number of samples. The overall accuracy of the model is 0.99, indicating the model is 99% accurate.

- **Macro Avg**: The unweighted average of the metrics for each class, not considering class imbalance. The macro average precision, recall, and F1-score are 0.92, 0.95, and 0.94, respectively.

- **Weighted Avg**: The average of the metrics for each class, weighted by the number of true instances for each class. The weighted average precision, recall, and F1-score are all 0.99.

## Summary ##
