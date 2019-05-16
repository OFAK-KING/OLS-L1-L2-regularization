# OLS-L1-L2-regularization
The Project is analyzing using the latest techniques learned using Python to build regularized linear models to predict the game attendance based on the month, day_of_week, temp, skies, and bobblehead input attributes.
 The following data preprocessing operations were performed: 
Encode the categorical variables using the one-hot encoding.
Made both training and testing datasets have the same data columns (input attributes).
• Standardize the new features by removing the mean and scaling to unit variance.
• Using the training dataset, train 100 L2-regularized linear models corresponding to 100 regularization coefficients evenly spaced between 0.1 and 1000. Use the leave-one-out cross-validation. 
• performed the same operation but now using L1-regularization.
• Trained also a linear model without regularization. 
