# Machine Learning Model Identification and Dataset Exploration

This project explores multiple public datasets and identifies the appropriate type of machine learning model to be applied for each. It includes dataset loading, sample visualizations, and model classification (e.g., regression, classification, supervised, etc.).

---

## 📁 Datasets Explored

### 1. Loan Amount Prediction
- **Source**: [Kaggle](https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset)
- **Description**: Predict loan approval based on applicant details like income, education, and credit history.
- **Model Type**: 
  - **Learning**: Supervised
  - **Problem**: Classification (`Loan_Status` is categorical)

---

### 2. Handwritten Character Recognition
- **Source**: [MNIST Dataset](http://yann.lecun.com/exdb/mnist/)
- **Description**: Recognize handwritten digits (0–9) from grayscale images.
- **Model Type**:
  - **Learning**: Supervised
  - **Problem**: Multi-class Classification

---

### 3. Email Spam Classification
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/spambase)
- **Description**: Detect whether an email is spam or not based on extracted features.
- **Model Type**:
  - **Learning**: Supervised
  - **Problem**: Binary Classification (`label` = 0 or 1)

---

### 4. Diabetes Progression Prediction
- **Source**: `sklearn.datasets.load_diabetes`
- **Description**: Predict disease progression based on ten physiological features.
- **Model Type**:
  - **Learning**: Supervised
  - **Problem**: Regression (target is a continuous variable)

---

### 5. Iris Flower Classification
- **Source**: `sklearn.datasets.load_iris`
- **Description**: Classify iris flowers into three species based on sepal/petal dimensions.
- **Model Type**:
  - **Learning**: Supervised
  - **Problem**: Multi-class Classification

---

## 📦 Required Libraries

```bash
pip install pandas scikit-learn seaborn opendatasets tensorflow
