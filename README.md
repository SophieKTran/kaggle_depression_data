# Predicting Mental Health: Analysis and Modeling

This repository contains Jupyter notebooks for exploring and modeling a dataset related to predicting mental health outcomes. The work is divided into two main parts: exploratory data analysis and predictive modeling.

---

## **Contents**

### 1. `q1_analysis.ipynb`
This notebook focuses on **Exploratory Data Analysis (EDA)**, providing insights into the dataset. Key activities include:
- **Data Cleaning:** Handling missing values and data inconsistencies.
- **Statistical Summary:** Descriptive statistics for each variable.
- **Visualizations:**
  - Correlation heatmaps to identify relationships between features.
  - Distribution plots to examine data distributions.
  - Box plots and scatter plots for feature analysis.
- **Insights:** Observations and hypotheses derived from the EDA.

---

### 2. `q2_model.ipynb`
This notebook develops and evaluates models to predict mental health outcomes. Key highlights:
- **Models Implemented:**
  1. **K-Nearest Neighbors (KNN):** A simple, non-linear model for classification.
  2. **Logistic Regression:** A linear model providing baseline performance.
  3. **XGBoost:** A tree-based ensemble model with advanced capabilities.
- **Features and Target Variable:**  
  - The target variable is `"History of Mental Illness"`.
  - All other variables are considered as potential predictors.
- **Evaluation Metrics:**
  - Precision, Recall, F1-Score, and AUC-ROC for assessing performance.
  - Cross-validation for robustness.

---

## **How to Use**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/predicting-mental-health.git

cd predicting-mental-health
pip install -r requirements.txt
jupyter notebook
