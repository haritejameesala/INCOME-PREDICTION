# Income Predictor using Random Forest Classifier

## Overview

This project is an end-to-end Machine Learning classification system that predicts whether a person's annual income exceeds \$50K based on demographic and employment-related attributes from the Adult Census Income dataset.

The project covers the complete ML workflow including:

- Data preprocessing
- Data Analysis
- Feature engineering
- Encoding categorical variables
- Model training
- Hyperparameter tuning using GridSearchCV
- Model evaluation and visualization

---

# Dataset

Dataset:
- Adult Census Income Dataset

Prediction Target:
- `<=50K`
- `>50K`

---

# Features Used

Some important features include:

- Age
- Education
- Occupation
- Marital Status
- Relationship
- Hours per Week
- Capital Gain
- Capital Loss
- Workclass

---

# Tools Used

- python
- pandas
- numPy
- matplotlib
- Scikit-learn
- seaborn
- pickle
- Jupyter Notebook

---

# Machine Learning Pipeline

## Data Preprocessing

- Removed unnecessary columns like `fnlwgt`
- Handled missing values
- Encoded categorical variables
- Split data into training and testing sets

---

## Model Used

### Random Forest Classifier

The Random Forest model was trained to classify income categories and improve prediction accuracy.

---

## Hyperparameter Tuning

Used:
- GridSearchCV

Parameters tuned:
- `n_estimators`
- `max_depth`
- `min_samples_split`

---

# Model Evaluation

The model was evaluated using:

- Accuracy Score
- Confusion Matrix
- ROC Curve
- Classification Report
- Feature Importance Plot

---

# Visualizations

## Feature Importance

Displays the contribution of each feature to the prediction process.

## Confusion Matrix

Shows correct and incorrect predictions for both income classes.

## ROC Curve

Measures the model’s classification capability across different thresholds.

---

# Author

Hariteja Meesala  
CSE, NIT Trichy
