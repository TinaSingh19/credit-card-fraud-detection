# credit-card-fraud-detection
Binary classification of credit card fraud using ML models
# Credit Card Fraud Detection

This project involves applying machine learning techniques to identify fraudulent transactions in a credit card dataset. The aim is to build a binary classification model that distinguishes between fraudulent and legitimate transactions.

## Dataset Overview
- **Source:** Taiwan Credit Card dataset (from Kaggle)
- **Size:** 30,000 observations × 25 features
- **Features:** A mix of numerical and categorical variables related to customer transactions and defaults.

## Project Workflow

### 1. Exploratory Data Analysis (EDA)
- Inspected missing values and class imbalance
- Used `matplotlib` and `seaborn` to visualize distributions, correlations, and outliers

### 2. Data Preprocessing
- Label encoding for categorical variables
- Train-test split (80–20)
- Feature scaling using StandardScaler

### 3. Model Training and Evaluation
Implemented and compared three models:
- **Logistic Regression**
- **Decision Tree**
- **Random Forest**

Metrics used for evaluation:
- Accuracy
- Confusion Matrix
- ROC Curve and AUC Score

### Best Accuracy: **82.72%**

## Tools & Technologies
- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

## How to Run
1. Clone the repository
2. Open the `.ipynb` file in Jupyter Notebook or Google Colab
3. Run all cells sequentially

## Note on Data
The original dataset is not included here. You can download it from Kaggle and place it in your working directory.

---

This project is a part of my machine learning portfolio focused on real-world fraud detection problems using Python.
