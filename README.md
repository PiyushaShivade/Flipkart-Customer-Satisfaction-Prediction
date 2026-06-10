# Customer Satisfaction Prediction using Flipkart Customer Support Data

This project explores customer support data from Flipkart and builds machine learning models to predict customer satisfaction scores (CSAT).

The work includes:

* Data cleaning and preprocessing
* Exploratory data analysis (EDA)
* Feature engineering
* Model training and evaluation
* Comparison of multiple classification models

## Models

* Random Forest
* XGBoost
* LightGBM
* Stacking Classifier

## Results

| Model               | Accuracy |
| ------------------- | -------- |
| Random Forest       | 69.21%   |
| XGBoost             | 69.33%   |
| LightGBM            | 69.49%   |
| Stacking Classifier | 69.64%   |

The Stacking Classifier achieved the best performance and was selected as the final model.

## Files

* `Flipkart_Customer_Support.ipynb` - Complete analysis and model development
* `Customer_support_data.csv` - Dataset used for training and evaluation

## Tools

Python, Pandas, NumPy, Scikit-Learn, XGBoost, LightGBM, Matplotlib, Seaborn
