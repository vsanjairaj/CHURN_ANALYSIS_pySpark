# Churn Analysis on IBM telecom dataset

### ·	Using IBM telecom dataset, carried out Churn Analysis and developed a ML pipeline for predicting Churn of a customer.

### ·	The dataset was split into two categories: Categorical and Non Categorical columns. NA values were filled using Imputer and Categorical variables were encoded using OneHotEncoder and QuantileDiscretizer for continuous values. 

### ·	Logistic Regression and Random Forest models were developed and a CrossValidator to tune the model with best parameters.

### ·	All the steps were added in stages to a pyspark ML pipeline and train and test dataframes were created.

## Dataset link: https://www.kaggle.com/zagarsuren/telecom-churn-dataset-ibm-watson-analytics


### References 
- https://spark.apache.org/docs/latest/api/python/index.html
- https://www.youtube.com/results?search_query=ai+engineering