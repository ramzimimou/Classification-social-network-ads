# Classification using Naive Bayes, Decision Tree, and KNN algorithms on Social Network Ads dataset

This repository contains code for implementing classification algorithms on the Social Network Ads dataset. The goal of this implementation is to predict whether a user will purchase a product based on their age and estimated salary.

## Dataset
The dataset used was downloaded from Kaggle.com, and it consists of 400 observations with the following columns:

**1-User ID**

**2-Gender (Male=1/Female=0)**

**3-Age (in years)**

**4-Estimated Salary (in dollars)**

**5-Purchased (0=No, 1=Yes)**

We will use the Age and Estimated Salary columns to predict whether a user will purchase a product.

## Classification Algorithms
The following classification algorithms have been implemented:

**1- Naive Bayes Classifier: A probabilistic algorithm that makes predictions based on the Bayes theorem.**

**2- Decision Tree Classifier: A tree-based algorithm that builds a decision tree to make predictions.**

**3- K-Nearest Neighbors Classifier: A distance-based algorithm that makes predictions based on the closest data points.**

## Rnning the Code

To run the code, follow the steps below:

**1-Download the dataset from the repository above(Social Network Ads.csv).**

**2-Open Google drive and upload the dataset in DATA file, (Make sure that the path in the code corresponds to the dataset placement).**

**3-Open Google Colab and create a new Python 3 notebook and run the code after pasting it (the three codes were implemented separately).**

## Results
The performance of each algorithm is evaluated based on accuracy, confusion matrix, and classification report. The Naive Bayes Classifier achieved an accuracy of 90.0%, the Decision Tree Classifier achieved an accuracy of 94.0%, and the K-Nearest Neighbors Classifier achieved an accuracy of only 77.0% on the testing data.

## Conclusion
In this project, we used three classification algorithms to predict whether a user will purchase a product based on their age and estimated salary, using the Social Network Ads dataset. These algorithms can be further optimized to achieve better results on this dataset or other similar datasets.

## Credits
This code was created by ramzimimou.
