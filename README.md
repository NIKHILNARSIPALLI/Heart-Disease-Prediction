# Heart-Disease-Prediction
This repository is part of the internship project at pnfsninterns. This project is based on accurately predicting heart disease in patients.



# Transformations of the data

The whole data set is first cleaned and fixed of missing values.

Then the categorical columns are one-hot encoded.


NO Exploratory Data Analysis was done, and Outliers were not treated.


# Predictions 

The predictions were done on various models with cross-validation set to 5 and the accuracies were compared to select the best model.


The model with the best test_accuracy turned out to be Logistic Regression with an accuracy of 62%


# Conclusion

The model can be vastly improved with the following:
1. Vastly bigger dataset.
2. Management of outliers (although not too much as real-world data also contains few errors while testing)
3. Trial and error with model parameters 
