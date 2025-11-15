# Internship Task 2 — Exploratory Data Analysis (EDA)
**Author:** Shreshtha Bhusanur  
**Dataset:** Titanic Dataset (Kaggle)  
**Repository:** https://github.com/shreshthabhusanur/internship-task1-shreshtha  

---

## 🎯 Objective
The goal of Task 2 is to perform Exploratory Data Analysis (EDA) on the Titanic dataset to understand:
- Data distribution  
- Missing values  
- Outliers  
- Feature relationships  
- Correlations and patterns  

This helps decide what preprocessing and modeling steps to apply next.

---

## 🧩 Steps Performed

### **1. Summary Statistics**
- Checked dataset shape, data types, and missing values.  
- Computed mean, median, standard deviation, and distribution properties.  
- Identified columns like *Age*, *Cabin*, and *Embarked* with missing values.

### **2. Distribution Analysis**
- Plotted histograms and KDE plots for numerical features such as `Age` and `Fare`.  
- Observed skewness (especially in `Fare`).  
- Understood the spread of each variable.

### **3. Outlier Detection**
- Created boxplots for key features.  
- Detected high outliers in `Fare`.  
- Analyzed spread of values across `Pclass` and `Sex`.

### **4. Categorical Data Insights**
- Plotted countplots for `Pclass`, `Sex`, and `Embarked`.  
- Observed higher survival among:
  - Females  
  - First-class passengers  

### **5. Relationship Analysis**
- Generated pairplots to visualize multivariate relations.  
- Created a correlation heatmap to understand feature relationships.  
- Found strong negative correlation between `Pclass` and `Fare`.

### **6. Exported Outputs**
- Saved EDA summary statistics as `eda_summary_stats.csv`  
- Saved plots inside the **plots/** folder  

---

## 📂 Folder Structure


---

## ⚙️ How to Run the Notebook

### **1. Clone the repository**

```bash
git clone https://github.com/shreshthabhusanur/internship-task1-shreshtha
cd internship-task1-shreshtha/task2
pip install pandas numpy matplotlib seaborn plotly scipy jupyterlab
jupyter lab task2_EDA.ipynb

