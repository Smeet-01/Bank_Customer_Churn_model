## Bank_Customer_Churn_model
Link to Dataset: https://www.kaggle.com/datasets/adammaus/predicting-churn-for-bank-customers?datasetId=66163&sortBy=voteCount

Details about the dataset:
It consists of 10000 observations and 14 variables. Independent variables contain information about customers. Dependent variable refers to customer abandonment status.


### Report: -
The procedure followed in analyzing this dataset-

1. Imported the dataset obtained from kaggle and checked the variable datatypes.
2. The dataset was engineered to suit our needs by dropping unnecessary columns and encoding the required ones.
3.The dataset was split into training, validation and test sets in the ratio of 14:3:3 respectively.
4. The model selected in this instance was RandomForestClassifier.
5. Using RandomSearchCV, optimal hyperparameters were obtained and the model thus created was applied to the test set.
6. The metrics obtained from the above are: - Acc: 86.40%, 
                                              Precision: 0.75,
                                              Recall: 0.45,
                                              f1: 0.57
