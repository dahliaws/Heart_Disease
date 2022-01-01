# Heart_Disease
 Classifier for predicting heart disease using a kaggle dataset.

This dataset was used for predicting heart disease. 
EDA:
It has 12 attributes, 912 records and no missing values.
Roughly half of the values in the cholesterol feature were 0. 
This seemed faulty so the feature was removed from the predictive analysis.

Data cleaning:
Removed cholesterol feature.
Using get.dummies, categorical features were changed to numerical features.

Model prediction class.
Heart disease binary target required classification algorithm.
Decision tree and Random Forest algorithms as well as others were tested. 
Random Forest had the best accuracy, percision, recall and F1-score.

Results of train and test sets are presented. 
