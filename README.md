# Delivery Time Prediction Using Ensemble Regression Models

## 🚀 Project Overview
This project focuses on predicting delivery time (in minutes) using ensemble-based regression models. Random Boosting and CatBoost regressors were implemented using Python and scikit-learn-compatible libraries. To ensure robust model evaluation and reduce overfitting, K-Fold cross-validation was applied during training.


## 🧠 Models Used
- **Random Boosting Regressor**
- **CatBoost Regressor**

Both models are ensemble-based methods that improve prediction accuracy by combining multiple weak learners.

## 🔁 Cross-Validation Strategy
Since the dataset was small,
- **K-Fold Cross-Validation** was used to split the dataset into multiple folds
- Each model was trained and evaluated across all folds
- Performance metrics were averaged to ensure stability and generalization

## 📊 Evaluation Metrics
The models were evaluated using standard regression metrics such as:
Mean Absolute Error (MAE)

## 🛠️ Technologies & Libraries
- Python
- scikit-learn
- CatBoost
- NumPy
- Pandas
- Matplotlib (for visualization, if applicable)

