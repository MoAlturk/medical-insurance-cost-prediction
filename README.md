# Medical Insurance Cost Prediction

An end-to-end Machine Learning project to predict individual medical insurance costs using regression analysis. This project is part of my practical machine learning portfolio.

## 🛠️ Project Overview
- **Objective:** Predict medical insurance charges based on personal and demographic features (e.g., age, BMI, smoking status).
- **Language:** Python
- **Environment:** Google Colab / Jupyter Notebook
- **Libraries:** Pandas, NumPy, Scikit-Learn

## 📊 Pipeline Steps

1. **Data Loading & Inspection:** Loaded the dataset and inspected columns, data types, and missing values.
2. **Feature Engineering:** Converted categorical variables (such as `sex`, `smoker`, and `region`) into numerical format using One-Hot Encoding (`pd.get_dummies` with `drop_first=True`).
3. **Data Splitting:** Split the dataset into 80% training and 20% testing sets (`train_test_split`).
4. **Feature Scaling:** Standardized features using `StandardScaler` on the training set and transformed the testing set to prevent data leakage.
5. **Model Training:** Trained a **Linear Regression** model using Scikit-Learn.
6. **Evaluation:** Evaluated model performance using Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared ($R^2$) Score (achieving an $R^2$ of ~0.78).

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone [https://github.com/MoAlturk/medical-insurance-cost-prediction.git](https://github.com/MoAlturk/medical-insurance-cost-prediction.git)
