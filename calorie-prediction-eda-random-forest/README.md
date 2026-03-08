# Calorie Expenditure Prediction

## Project Overview
This project predicts the number of calories burned during physical activity using physiological and activity-related features. The analysis includes exploratory data analysis (EDA), feature understanding, and machine learning model development to estimate calorie expenditure.

The goal is to understand which variables most strongly influence calorie burn and build a reliable regression model.

---

## Dataset
The dataset includes features such as:

- Age
- Gender
- Height
- Weight
- Duration of activity
- Heart rate
- Body temperature

Target Variable:
- Calories Burned

---

## Exploratory Data Analysis (EDA)

Key steps performed:

- Data cleaning and preprocessing
- Distribution analysis of numerical variables
- Correlation analysis between features
- Identification of important predictors
- Outlier detection
- Feature relationship visualization

Key insights discovered:

- Heart rate and activity duration show strong correlation with calories burned
- Body metrics such as weight and height influence energy expenditure
- Some features required scaling and transformation

---

## Machine Learning Model

### Random Forest Regressor

The primary model used is **Random Forest Regression**.

Why Random Forest?

- Handles nonlinear relationships effectively
- Robust to outliers
- Performs well with mixed feature types
- Reduces overfitting through ensemble learning

---

## Model Training Steps

1. Feature selection
2. Train-test split
3. Model training using Random Forest
4. Model evaluation using regression metrics

Evaluation metrics include:

- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

---

## Key Findings

- Duration and heart rate are the most influential predictors
- Random Forest captures nonlinear patterns effectively
- Ensemble learning improves prediction stability

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Possible Improvements

- Hyperparameter tuning
- Comparison with Gradient Boosting models
- Feature engineering
- Deployment as an API or ML application

---
## Author

**Neha Verma**  
Data Science | Machine Learning | Generative AI

LinkedIn: https://www.linkedin.com/in/nehavermadataanalytics