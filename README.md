# Task-3-Heart-Disease-Prediction
Heart Disease Prediction

```markdown
# Heart Disease Prediction Analysis

## 🎯 Task Objective
The primary goal of this project is to build a machine learning model capable of predicting the risk of heart disease in patients based on clinical health data. The focus is on creating a reliable binary classification model that can assist in medical screening processes.

## 📊 Dataset
- **Source:** Heart Disease UCI Dataset (available on Kaggle).
- **Observations:** 920 records with 16 clinical features.
- **Features include:** Age, Sex, Chest Pain Type (`cp`), Resting Blood Pressure (`trestbps`), Cholesterol (`chol`), Maximum Heart Rate (`thalch`), and ST depression (`oldpeak`).
- **Preprocessing:** Handled missing values via Median/Mode imputation and transformed categorical data using One-Hot Encoding.

## 🤖 Models Applied
- **Algorithm:** Logistic Regression (with Feature Scaling).
- **Data Split:** 80% Training / 20% Testing with stratification.
- **Scaling:** `StandardScaler` was applied to ensure all clinical measurements were weighted equally during model optimization.

## 📈 Key Results and Findings
- **Accuracy:** ~84.78% on the unseen test set.
- **ROC-AUC Score:** **0.917**, indicating excellent model discrimination between healthy and diseased patients.
- **Primary Risk Factors:**
    - **`ca` (Major Vessels):** The strongest clinical indicator of heart disease.
    - **`oldpeak`:** High ST depression during exercise significantly correlates with risk.
- **Protective Factors:**
    - **`thalch`:** Higher maximum heart rate during exercise is the strongest indicator of cardiovascular health in this dataset.

## 🛠️ Skills Demonstrated
- Exploratory Data Analysis (EDA) & Visualization (Seaborn/Matplotlib).
- Data Cleaning and Feature Engineering.
- Binary Classification Pipeline Development.
- Model Evaluation (Confusion Matrix, ROC Curve, AUC).
```
