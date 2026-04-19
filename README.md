# Regression
Regression Assignment Report: California Housing Prediction
1. Preprocessing Explanation
Standardization: We applied StandardScaler to ensure all features have a mean of 0 and a standard deviation of 1. This is critical for SVR and Linear Regression, as these models are sensitive to the magnitude of input features.
Missing Values: The dataset was checked and found to have no missing values, so no imputation was required.
2. Algorithm Overview
Linear Regression: Models the relationship between features and target using a linear equation. Suitable for finding general trends.
Decision Tree: Uses a tree-like structure to make decisions based on feature thresholds. Handles non-linearities well.
Random Forest: An ensemble of many decision trees. It reduces variance and prevents overfitting by averaging results.
Gradient Boosting: Builds trees sequentially, where each new tree attempts to correct the errors of the previous ones.
SVR (Support Vector Regressor): Uses kernels to map data into higher dimensions to find a hyperplane that best fits the data within a specified margin.
