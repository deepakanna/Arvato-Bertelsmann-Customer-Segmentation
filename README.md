# Arvato-Bertelsmann-Customer-Segmentation
To segment the individuals based on the demographic information and to predict whether an individual will become a customer for the Arvato Financial solutions.
## Introduction:
The aim of this project is to predict the individuals who are likely to become customers of a mail order sales company, Arvato Financial solutions. We are provided with the demographic data of customers of a mail-order company in Germany and demographic data of general population of Germany.  Using this data, we are required to identify new customers for the company.

## Unsupervised Model:
 - In the first section, Preprocessing of the data was performed removing attributes with more than 80% missing values, using simple imputer to fill the missing values, removing redundant features using pearson's correlation and converting categorical attributes. 

 - In the second section, the data was normalized using minmax normalization and PCA was used to reduce the dimensions of the data.
 - In the third section, data was divided into segments using KMeans clustering where the number of clusters was decided using Elbow method. 

## Supervised Model:
 - The mailout-train data was cleaned seven classifiers were used and the best model was identified using GridSearch. The best score obtained for 'roc-auc' is recorded. 
 - The mailout-test data was cleaned and the best model selected in the previous step is used to predict the response in the test data.
 
 
