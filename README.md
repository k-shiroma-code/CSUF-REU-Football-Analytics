# UEFA Football Match Outcome Prediction

As a community college student, I was fortunate to find a research opportunity at California State University, Fullerton, where I volunteered in a data science project. As I brainstormed ideas, the UEFA European Championship (Euros) had just begun, providing a perfect opportunity to explore predictive modeling.

This project aims to predict the outcomes of Euros football matches using historical data. The goal is to classify match results as **home win**, **draw**, or **away win**.

In addition to Logistic Regression and XGBoost, I experimented with Decision Trees, Random Forests, and a Neural Network built with TensorFlow/Keras.  

> **Note:** Due to file corruption during upload, the full implementations of these additional models were not preserved in the current version of the repository.

---

## Project Workflow

### 1. Data Acquisition & Cleaning
- Collected and preprocessed historical match data  
- Engineered features, including dynamic team Elo ratings  

### 2. Modeling
- Trained and evaluated classification models:
  - **Logistic Regression**
  - **XGBoost Classifier**
- Additional experiments:
  - **Decision Trees**
  - **Random Forest Classifier**
  - **Neural Network (TensorFlow/Keras)**  

### 3. Evaluation
- Assessed model performance using:
  - Classification reports  
  - Confusion matrices  

---

## File Overview

- **`EurosPrediction.ipynb`**  
  Contains the full implementation, including:
  - Data processing  
  - Feature engineering  
  - Model training and evaluation  

- **`results.csv`**  
  Includes model predictions and performance metrics  

---

## Environment & Dependencies

### Platform
- JupyterLab  

### Python Version
- 3.8+  

### Required Packages

```bash
pip install pandas numpy scikit-learn xgboost matplotlib seaborn
