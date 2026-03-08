# Wine Quality Classification using Tree-Based Models

## Project Overview

This project predicts wine quality using physicochemical properties of wine samples. The dataset contains various chemical attributes of wine and a quality score.

The objective is to classify wines into quality categories using machine learning models and compare the performance of different tree-based algorithms.

---

## Dataset Features

Key features include:

- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Free Sulfur Dioxide
- Total Sulfur Dioxide
- Density
- pH
- Sulphates
- Alcohol

Target Variable:

- Wine Quality Score

---

## Exploratory Data Analysis (EDA)

EDA steps performed:

- Data quality checks
- Distribution analysis
- Feature correlation analysis
- Feature importance exploration
- Outlier detection

Insights discovered:

- Alcohol content strongly correlates with wine quality
- Volatile acidity negatively impacts quality
- Several features exhibit nonlinear relationships

---

## Machine Learning Techniques Used

This project compares **multiple tree-based classification models**.

### 1. Decision Tree Classifier

Characteristics:

- Simple and interpretable
- Captures nonlinear patterns
- Prone to overfitting if not controlled

Advantages:

- Easy to interpret
- Works well with small datasets

Limitations:

- High variance
- Sensitive to training data changes

---

### 2. Random Forest Classifier

Characteristics:

- Ensemble of multiple decision trees
- Reduces overfitting
- Improves prediction stability

Advantages:

- High accuracy
- Robust to noise
- Handles nonlinear relationships

Limitations:

- Less interpretable than single decision trees

---

## Model Comparison

| Model | Strength | Weakness |
|-----|-----|-----|
| Decision Tree | Interpretable | Overfitting risk |
| Random Forest | Higher accuracy & robustness | Less interpretability |

In most cases, **Random Forest performs better due to ensemble learning**.

---

## Model Evaluation Metrics

Models are evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

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

## Potential Improvements

- Hyperparameter tuning
- Gradient Boosting models
- XGBoost or LightGBM comparison
- Feature engineering

---

## Author

**Neha Verma**  
Data Science | Machine Learning | Generative AI

LinkedIn: https://www.linkedin.com/in/nehavermadataanalytics
