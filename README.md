# ICP_5
# NN_ASSIGN_ICP_5
Neural Network Assignment ICP_5 Programs

1. Implement Naïve Bayes method using scikit-learn library
Use dataset available with name glass
Use train_test_split to create training and testing part
Evaluate the model on test part using score and
classification_report(y_true, y_pred)

2. Implement linear SVM method using scikit library
Use the same dataset above
Use train_test_split to create training and testing part
Evaluate the model on test part using score and
classification_report(y_true, y_pred)


Which algorithm you got better accuracy? Can you justify why?

* In summary, SVM is demonstrating better accuracy and performance across multiple evaluation metrics, suggesting that it is a more suitable model for this dataset, possibly due to its ability to capture complex relationships and handle class imbalances than Naïve Bayes.

Above Justification is based on the below evaluations:

* Precision, Recall, and F1-Score: SVM generally exhibits higher precision, recall, and F1-scores across multiple classes compared to Naïve Bayes. 
  * Naïve Bayes shows lower performance, especially regarding recall for some classes.

* Class Imbalance: The dataset might have class imbalances, affecting Naïve Bayes, which assumes independence among features.
  * SVM, being less sensitive to feature independence, may perform better in such cases.
* Model Complexity: SVM, with a linear kernel, might have captured the underlying relationships in the data more effectively, especially if the decision boundary is not strictly linear.
* Handling of Class 3: Naïve Bayes predicts class 3 with a precision, recall, and F1-score of 0.40, 0.67, and 0.50, respectively. SVM, however, struggles with class 3, showing precision, recall, and F1-score of 0.00, 0.00, and 0.00. This discrepancy could significantly impact overall performance.
