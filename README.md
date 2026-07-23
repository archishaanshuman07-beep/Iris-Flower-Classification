# Iris Flower Classification

A machine-learning notebook that classifies iris flowers into their three
species — *setosa*, *versicolor*, and *virginica* — from four measurements:
sepal length, sepal width, petal length, and petal width.

## What it does

- Explores the distributions in the Iris flower dataset from sklearn
- Cleans, rescales, and reduces dimensions of data (using PSA) to use in model training/testing
- cross-validate Logistic Regression, Random Forest, and SVC on the training data
- score the final SVC on a test set, with a classification report and confusion matrix

The final SVC reaches about **97% accuracy** on the test set.
