# 📊 Loan Sanction Amount Prediction using Linear Regression

This project predicts **Loan Sanction Amount (USD)** based on various customer and financial features using machine learning techniques. The dataset is sourced from Kaggle and includes both numerical and categorical features.

---

## 📁 Dataset

- Dataset: [Kaggle - Predict Loan Amount Data](https://www.kaggle.com/datasets/phileinsophos/predict-loan-amount-data)
- Files used:
  - `train.csv`: Training dataset with customer attributes and loan information.

---

## 🧠 Objectives

- Perform data preprocessing (missing values, encoding, outlier handling).
- Apply feature scaling (Z-score normalization).
- Visualize key features and distributions.
- Train a **Linear Regression** model to predict the loan sanction amount.
- Evaluate performance using:
  - Train-test split
  - K-Fold Cross-Validation

---

## ⚙️ Technologies Used

- Python 🐍
- Google Colab
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## 🧹 Steps Performed

### 1. Data Preprocessing
- Dropped unnecessary columns (`Name`, `Customer ID`)
- Imputed:
  - Numerical columns using **Median**
  - Categorical columns using **Mode**
- Encoded categorical variables using **One-Hot Encoding**
- Mapped binary features ('Y'/'N') to 1/0
- Handled missing values in the target column (`Loan Sanction Amount (USD)`)

### 2. Data Visualization
- Histograms, boxplots, and scatter plots to analyze distributions and relationships.
- Correlation heatmap to check feature importance.

### 3. Outlier Treatment
- Applied **IQR-based capping** to reduce influence of extreme outliers.

### 4. Feature Scaling
- Normalized numerical features using **Z-score normalization**.

### 5. Model Training and Evaluation
- Model: **Linear Regression**
- Performed:
  - Train/Test split (80/20)
  - 5-Fold Cross-Validation
- Evaluation metrics:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R² Score

---

## 📈 Results

The model’s performance was evaluated using both a hold-out test set and 5-fold cross-validation. Evaluation included both error metrics and plots:

- ✅ **Residual plots**
- ✅ **True vs Predicted plot**
- ✅ **Feature importance bar chart (coefficients)**

---


## 📝 Author

- Sandhya Giribabu
- Project for **Machine Learning Lab**
- July 2025

---
