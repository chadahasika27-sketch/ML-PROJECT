# 11 Machine Learning Projects — Complete Starter Package

Each project is a standalone Python script. Run them from the project root.

## Install
pip install -r requirements.txt

## Run
python projects/01_titanic_eda_lifecycle.py
python projects/02_titanic_preprocessing.py
...
python projects/11_wine_quality_tree_rf.py

The scripts download the required public datasets automatically when needed.
Generated/cleaned CSV files are written to the `datasets/` folder.

## Projects
1. Titanic Survival — EDA and ML Lifecycle Mapping
2. Titanic Survival — Preprocessing Pipeline and Cleaned Dataset
3. Adult Income — Feature Engineering and EDA
4. California Housing — Linear Regression and Regularisation
5. Titanic Survival — Full Logistic Regression Pipeline
6. Diabetes Severity — Multinomial Logistic Regression
7. Auto MPG — Linear Regression, Scaling and Encoding
8. Heart Disease — Decision Tree Classification
9. Heart Disease — Random Forest Ensemble
10. Heart Disease — XGBoost, LightGBM and SHAP
11. Wine Quality — Decision Tree and Random Forest Classification

## Note
Project 6 creates three severity classes from the continuous target of sklearn's diabetes dataset using its 33rd and 66th percentiles. This is an educational target-engineering exercise, not a clinical severity definition.
