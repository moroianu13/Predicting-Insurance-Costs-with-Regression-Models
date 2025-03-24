# 🧠 Predicting Insurance Costs with Regression Models

This project explores and models a real-world dataset to predict **medical insurance charges** based on customer attributes such as **age, BMI, smoking status, and more**. It includes both **exploratory data analysis (EDA)** and various **regression models** to find the best prediction strategy.

---

## 📂 Dataset Overview
- **Rows**: 2,771
- **Columns**: `age`, `sex`, `bmi`, `children`, `smoker`, `region`, `charges`
- **Source**: IBM Data Science Course dataset

---

## 🎯 Objectives
- Clean and preprocess the data
- Visualize relationships between features
- Build and evaluate machine learning models for cost prediction:
  - Simple Linear Regression
  - Multiple Linear Regression
  - Polynomial Regression
  - Ridge Regression

---

## 📊 Key Insights
- **Smoking** has the strongest influence on medical charges.
- **Polynomial regression (degree=2)** gives the most accurate predictions.
- Feature scaling and transformation significantly improve model performance.

---

## 📈 Model Performance (Test R² Scores)

| Model                          | R² Score |
|-------------------------------|----------|
| Simple Linear (smoker only)   | 0.659    |
| Multiple Linear Regression    | 0.777    |
| Polynomial Regression         | 0.8475   |
| Ridge Regression              | 0.777    |
| Manual Polynomial Regression  | **0.8476** |

---

## 🛠️ Tools Used
- Python
- **Pandas**, **NumPy** for data manipulation
- **Matplotlib**, **Seaborn** for visualization
- **Scikit-learn** for model building:
  - `LinearRegression`, `Ridge`
  - `Pipeline`, `PolynomialFeatures`, `StandardScaler`
  - `train_test_split`, `mean_squared_error`

---

## 🧪 What I Learned
- How to structure a machine learning pipeline
- The impact of categorical features and encoding
- Using correlation and feature importance in real-world analysis
- Difference between simple, multiple, and polynomial regression

---

## 📁 Files
- `Data Analytics for Insurance Cost Data Set.ipynb` – Fully executed notebook with all steps
- `medical_insurance_dataset.csv` – Dataset used for training and evaluation

---

## 🚀 How to Run
1. Clone this repository
2. Make sure you have Jupyter and required Python libraries installed
3. Run the notebook `Data Analytics for Insurance Cost Data Set.ipynb`

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook
