# 🏠 House Price Prediction Using Machine Learning

## Project Overview

This project predicts house prices based on property features such as area, number of bedrooms, bathrooms, stories, parking, location, and house age.

The project follows a complete machine learning workflow, starting from data exploration and preprocessing to model training, evaluation, and hyperparameter tuning.

## Objective

The objective is to develop a regression model that can predict house prices from property-related features.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib
* Google Colab

## Machine Learning Models

The following regression models were trained and compared:

1. Linear Regression
2. Decision Tree Regression
3. Random Forest Regression

## Project Workflow

```text
Dataset
   ↓
Exploratory Data Analysis
   ↓
Data Cleaning
   ↓
Categorical Feature Encoding
   ↓
Feature Selection
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Model Comparison
   ↓
Hyperparameter Tuning
   ↓
Final Model Evaluation
   ↓
Feature Importance
   ↓
Save Final Model
```

## Data Preprocessing

The dataset was checked for missing values and duplicate records.

The categorical `Location` feature was converted into numerical features using one-hot encoding.

The dataset was divided into:

* 80% training data
* 20% testing data

## Model Evaluation

The models were evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

Lower MAE and RMSE indicate smaller prediction errors, while a higher R² score indicates better explanatory performance.

## Hyperparameter Tuning

GridSearchCV with 5-fold cross-validation was used to search for suitable Random Forest hyperparameters.

## Final Model

The best-performing model based on the evaluation results was selected as the final model and saved using Joblib.

## Files

* `House_Price_Prediction.ipynb` — Complete project notebook
* `house_price_dataset.csv` — Dataset used for training and evaluation
* `house_price_model.pkl` — Saved trained machine learning model

## Future Improvements

* Use a larger real-world housing dataset
* Experiment with additional regression algorithms
* Perform more extensive feature engineering
* Deploy the model as a web application
