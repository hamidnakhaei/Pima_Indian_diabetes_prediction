# Pima Indian Diabetes Prediction
The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. \
1. Importing and cleaning the data set
2. Correlated Feature Check
3. Check pairplot
4. Check class distribution
  - Number of True cases:  268 (34.90%)
  - Number of False cases: 500 (65.10%)
6. Spliting the data
  - 70% for training, 30% for testing
7. Training Initial Algorithm - Naive Bayes
  - Performance on Testing Data: Accuracy: 0.7403 / Precision = 0.62 / Recall = 0.64
8. Training Random Forest
  - Performance on Testing Data: Accuracy: 0.7403 / Precision = 0.62 / Recall = 0.62
9. Training Logistic Regression
  - Performance on Testing Data: Accuracy: 0.7446 / Precision = 0.66 / Recall = 0.55
10. Training Logisitic regression with class_weight='balanced'
  - Performance on Testing Data: Accuracy: 0.6970 / Precision = 0.55 / Recall = 0.74
11. Training LogisticRegressionCV
  - Performance on Testing Data: Accuracy: 0.6926 / Precision = 0.55 / Recall = 0.65
