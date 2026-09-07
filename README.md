# Loan Approval Prediction using Machine Learning

## 📌 Overview

This project focuses on analyzing applicant financial and demographic information and predicting whether a loan application will be approved using machine learning classification techniques.

The dataset contains **1,000 applicant records and 20 features**, including income, credit score, existing loans, DTI ratio, savings, collateral value, loan amount, loan term, employment status, education level, property area, and other applicant characteristics.

## 🎯 Objective

The primary objective is to build and compare machine learning classification models for predicting the `Loan_Approved` target variable.

The project covers the complete machine learning workflow:

* Data loading and exploration
* Missing value handling
* Exploratory Data Analysis
* Categorical feature encoding
* Feature scaling
* Train-test splitting
* Model training
* Model evaluation
* Model comparison

## 📊 Dataset

The dataset contains the following major features:

* Applicant Income
* Coapplicant Income
* Employment Status
* Age
* Marital Status
* Dependents
* Credit Score
* Existing Loans
* DTI Ratio
* Savings
* Collateral Value
* Loan Amount
* Loan Term
* Loan Purpose
* Property Area
* Education Level
* Gender
* Employer Category

### Target Variable

`Loan_Approved`

The dataset contains 722 rejected and 278 approved applications.

## 🔍 Exploratory Data Analysis

The project performs exploratory analysis to understand:

* Target-class distribution
* Numerical feature statistics
* Applicant financial characteristics
* Relationships between features
* Distribution of important variables
* Potential patterns associated with loan approval

## 🧹 Data Preprocessing

The following preprocessing techniques are used:

### Missing Value Handling

* Mean imputation for numerical features
* Most-frequent-value imputation for categorical features

### Categorical Encoding

* Label Encoding
* One-Hot Encoding

### Feature Scaling

`StandardScaler` is used to standardize numerical model inputs.

### Train-Test Split

The dataset is divided into:

* **80% training data**
* **20% testing data**

## 🤖 Machine Learning Models

The following classification algorithms are implemented:

### 1. Logistic Regression

A linear classification model used as a baseline for loan approval prediction.

### 2. K-Nearest Neighbors (KNN)

A distance-based classification algorithm implemented with `k = 9`.

### 3. Gaussian Naive Bayes

A probabilistic classification algorithm based on Bayes' theorem.

## 📈 Model Evaluation

The models are evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

Using multiple evaluation metrics helps provide a more complete assessment of classification performance, especially when the target classes are not perfectly balanced.

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## 📁 Project Structure

```text
Loan-Approval-Prediction/
│
├── loan_approval_data.csv
│
├── loan_approval_Analysis.ipynb
│
├── README.md
├── requirements.txt
├── .gitignore
└── LICENSE
```

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/Sanket-Thorat99/Loan-Approval-Analysis.git
cd Loan-Approval-Analysis
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
notebooks/loan_approval_Analysis.ipynb
```

## 📌 Future Improvements

* Use a Scikit-learn `Pipeline` and `ColumnTransformer` for cleaner preprocessing.
* Add additional classification algorithms such as Random Forest and Support Vector Machine.
* Perform hyperparameter tuning using GridSearchCV or RandomizedSearchCV.
* Compare model performance using ROC-AUC and Precision-Recall curves.
* Perform feature importance analysis.
* Deploy the final model as a web application.

## 👨‍💻 Author

**Sanket Thorat**

Computer Science & Engineering Student
