# Stroke Risk Prediction Using Machine Learning

## Project Overview

This project applies machine learning techniques to predict the likelihood of stroke occurrence using patient demographic, lifestyle, and medical information.

The project focuses on data preprocessing, exploratory data analysis, feature engineering, model training, evaluation, and comparison of multiple machine learning classification algorithms.

The aim is to support early risk identification and demonstrate how machine learning can assist healthcare-related decision-making.

---

## Dataset

The dataset contains health-related attributes such as:

- Gender
- Age
- Hypertension
- Heart Disease
- Marital Status
- Work Type
- Residence Type
- Average Glucose Level
- BMI
- Smoking Status

Target variable:

- `stroke`
  - `1` = Stroke
  - `0` = No Stroke

---

## Project Objectives

- Clean and preprocess healthcare data
- Handle missing values and categorical variables
- Perform exploratory data analysis (EDA)
- Visualise stroke-related patterns
- Train and compare classification models
- Evaluate models using healthcare-relevant metrics
- Investigate class imbalance effects

---

## Exploratory Data Analysis

The notebook includes:

- Class distribution analysis
- Correlation analysis
- Age distribution visualisation
- Stroke occurrence comparisons
- BMI and glucose level analysis
- Categorical feature analysis
- Heatmaps and count plots

---

## Machine Learning Models Used

The following models were trained and evaluated:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbours (KNN)
- XGBoost Classifier

---

## Evaluation Metrics

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC Score
- Confusion Matrix

---

## Why Recall Matters in Healthcare

In stroke prediction, recall is extremely important because missing a real stroke-risk patient can have severe consequences.

A false negative means the model predicts that a patient is safe when they are actually at risk of stroke. In healthcare applications, reducing false negatives is often more important than maximising overall accuracy.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

## How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/your-username/stroke-risk-prediction-ml.git
```

### 2. Open the project directory

```bash
cd stroke-risk-prediction-ml
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open and run the notebook

Run:

```text
stroke_risk_prediction.ipynb
```

from top to bottom.

---

## Repository Structure

```text
.
├── stroke_risk_prediction.ipynb
├── StrokePredictionDataset.csv
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Key Challenges

- The dataset is imbalanced because stroke cases are relatively rare.
- Missing BMI values required preprocessing.
- Some categorical variables required encoding before training.

---

## Future Improvements

- Apply SMOTE for imbalance handling
- Perform hyperparameter tuning
- Add feature importance analysis
- Use SHAP explainability
- Build a Streamlit web application
- Deploy the model online

  
---

## Author

Uvietobore Joshua Adjugah
MSc Data Science and Artificial Intelligence
