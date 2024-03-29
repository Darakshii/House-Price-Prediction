# House Price Prediction Project

## Problem Statement
### Goal
It is your job to predict the sales price for each house. For each Id in the test set, you must predict the value of the SalePrice variable. 
### Metric : 
Submissions are evaluated on Mean-Squared-Error,Root-Mean-Squared-Error, Mean Absolute Error, R2 (MSE, RMSE, MAE, R2).
Submission File Format

## Overview
This project focuses on predicting house prices using machine learning techniques. It involves data preprocessing, feature selection, model training, and evaluation to achieve accurate predictions.

## Skills Utilized
- Python, Pandas, NumPy for data manipulation
- Matplotlib, Seaborn for data visualization
- Scikit-Learn for machine learning tasks such as feature selection, model training, and evaluation
- GridSearchCV for hyperparameter tuning

## Project Steps
1. **Data Handling and Preparation:**
   - Loaded training and testing datasets.
   - Conducted initial data exploration to understand the dataset's structure.
   
2. **Data Preprocessing:**
   - Handled missing values and performed feature scaling.
   
3. **Feature Selection:**
   - Used Lasso regression for feature selection.
   - Identified relevant features for model training.
   
4. **Model Training and Evaluation:**
   - Trained Ridge and Lasso regression models using GridSearchCV.
   - Evaluated model performance using MSE and MAE metrics.
   
5. **Test Data Prediction:**
   - Applied the trained models to the test dataset for predictions.
   - Saved results in a CSV file for analysis.

## Conclusion
- Successfully developed a machine learning pipeline for house price prediction.
- Achieved accurate predictions through data preprocessing, feature selection, and model training.
- Demonstrated proficiency in data analysis and machine learning techniques.

## How to Run
1. Clone the repository: `git clone https://github.com/your_username/house-price-prediction.git`
2. Install required libraries: `pip install -r requirements.txt`
3. Run the main script: `python house_price_prediction.py`
4. View the results in the generated CSV file.

