# Logistic-Regression---Breast-Cancer

It is a code that uses logistic regression technique to predict depending of the breast test whether is benign or malignant.

I used Breast Cancer Wisconsin data set (Original and Diagnostic), dividing them into 3 sub data set: 70% training set, 15% cross validation set and 15 test set.

Original Dataset has 10 columns, which 1-9 are features and 10 denotes whether the cell is benign(0) or malignant(1).

Diagnostic Dataset is divided as: 
first column --> ID patients (it is not important to us)
Second column --> Diagnosis (1's malignant and 0's to benign)
Third to thirty second --> features

The accuracies achieved are as follows:

# Original Dataset:
Training Set Accuracy: 96.242171 - Training set F1 score: 0.953846

Test Set Accuracy: 100.000000 - Test set F1 score: 1.000000

# DIagnistic Dataset
Training Set Accuracy: 98.496241 - Training set F1 score: 0.982456

Test Set Accuracy: 97.647059 - Test set F1 score: 0.976744

