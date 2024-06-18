# Wholesale-Customers-Data-Science
Goal of this project is to best describe the variation in the different types of customers that a wholesale distributor interacts with.

## Requirements

To run the notebook, you will need the following Python packages:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `jupyter`

The input features are separated from the target variable, and the XGBoost model is defined with the evaluation metric 'mlogloss'.

The StratifiedKFold method is used to define the 5-fold cross-validation method.

Cross-validation is performed using the XGBoost model, input features, and target variable. Accuracy, precision, recall, and F1 score are calculated using their respective scoring methods.

The mean scores are calculated for each performance metric and printed to the console.

The mean accuracy score is 0.9045, mean precision score is 0.9381, mean recall score is 0.9194, and mean F1 score is 0.9286.
