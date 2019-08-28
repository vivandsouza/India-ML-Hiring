# India-ML-Hiring

## Approach:
•	Tried different classification algorithms like Logistic Regression, SVM, KNN, Naïve Bayes, Random Forest, Decision Tree and XGBoost and found that Logistic Regression, Random Forest and XGBoost were giving the better results compared to the other models.
•	Finally selected the 8 important features from Random Forest top attributes.
•	Observed that the class was imbalance, so up-sampled the minority class.
•	Stacked the three models (Logistic Regression, Random Forest and XGBoost) with the cross validation of 4 folds.
•	Output of these stacked models were given to the Logistic Model for the final prediction.

## Pre-processing/Feature engineering
•	Ran the Random forest and selected the top 8 attributes
•	Up-sampled the minority class

## Final Model
•	Logistic Regression + Random Forest + XGBoost > Logistic Regression (with 4-fold cross validation)
