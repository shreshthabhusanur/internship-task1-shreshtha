# Internship Task 1 — Data Cleaning & Preprocessing
*by Shreshtha Bhusanur*

## 🎯 Objective
To perform data cleaning, preprocessing, encoding, scaling, and outlier handling on the Titanic dataset.

## 🧩 Steps Performed
1. **Exploration** — Checked data shape, data types, and missing values using `info()`, `describe()`, and visualizations.
2. **Missing Value Handling** — Filled missing numeric values (`Age`, `Fare`) using median; categorical values (`Embarked`) using mode; replaced `Cabin` with “Unknown”.
3. **Encoding** — Applied One-Hot Encoding on categorical features like `Sex`, `Embarked`, and `Deck`.
4. **Scaling** — Standardized numeric columns (`Age`, `Fare`, `SibSp`, `Parch`) using `StandardScaler`.
5. **Outlier Handling** — Detected and removed outliers using the IQR (Interquartile Range) method.
6. **Output** — Saved the cleaned dataset as `titanic_cleaned.csv`.

## ⚙️ How to Run
```bash
# Clone this repository
git clone [https://github.com/shreshthabhusanur/internship-task1-shreshtha]
cd internship-task1-shreshtha

# Run in Jupyter Lab or Notebook
jupyter lab task1_data_cleaning.ipynb
