# Datathon 2025 Session Value Prediction 

This repository contains solution for predicting session values in an e-commerce setting. 

## Dataset 

- Dataset is provided by the competition organizers.
- Each row represents a user action on a specific product and category with timestamps.

## Notebooks 
- EDA.ipynb : Exploratory Data Analysis
- Preprocess.ipynb : Feature engineering and data preparation
- hyperparameter_search.ipynb : hyperparamter search process
- train_final.ipynb : Model training and evaluation

## Models 
- LightGBM, XGBoost, CatBoost regressors
- Hyperparameters optimized by Optuna
- Evaluation Metric: MSE

## How to Run 
1. Install dependencies:  
pip install -r requirements.txt

2. Open notebooks in Jupiter and run in order:
- 1. EDA.ipynb
- 2. Preprocess.ipynb
- 3. hyperparameter_search.ipynb
- 4. train_final.ipynb 
