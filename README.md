# Prediction-of-African-Economic-Crisis
The purpose of the project is predicting the economic crisis for the african countries using the machine learning techniques which are Decision Tree, Naive Bayes and K Nearest Neighbor.

The dataset is called [Africa Economic, Banking and Systemic Crisis Dataset](https://www.kaggle.com/chirin/africa-economic-banking-and-systemic-crisis-data), Kaggle 2019. The dataset consists of 5 numerical and 9 categorical attributes. Raw form of the dataset has 1059  instances. Target feature is “banking_crisis” and it has two separate values as “crisis” and “no crisis”. The explanation of the other features can be found from the Kaggle link.

## Data Preparation
Data cleaning is applied for obtaining results closer to reality in dataset and facilitating analysis. The following steps are applied for data cleaning.
	
	1.Remove Duplicates and Missing Values
	2.Normalization
	3.Undersampling Method

After the data preparation steps, K-Fold Cross Validation is applied to improve the accuracy of the predictions. The %75 of the dataset is used for training set and the %25 is used for test set.





