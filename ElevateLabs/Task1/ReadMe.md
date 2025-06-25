# 🛠️ AML_Intern_Elevate  
## 🧼 Titanic Data Cleaning & Preprocessing Report  

This notebook documents the complete data cleaning and preprocessing workflow applied to the Titanic dataset in preparation for machine learning.

---

## 📊 Dataset  
- **Source:** Titanic Passenger Data (Kaggle / open-source)

---

## ✅ Key Preprocessing Steps  

1. **Data Exploration**
   - Loaded dataset
   - Inspected data types and missing values

2. **Missing Value Treatment**
   - Imputed missing values in the `Age` column
   - Filled missing `Embarked` values
   - Dropped the `Cabin` column due to high missing ratio

3. **Categorical Encoding**
   - Converted `Sex` and `Embarked` to numerical using label encoding / one-hot encoding

4. **Feature Scaling**
   - Standardized continuous features: `Age` and `Fare` using `StandardScaler`

5. **Outlier Detection & Removal**
   - Applied IQR method with boxplot visualizations
   - Removed extreme outliers from `Fare` and `Age`

---

## 🧰 Tools & Libraries  

- **Programming Language:** Python  
- **Libraries:**  
  - `pandas`, `numpy` – data manipulation  
  - `matplotlib`, `seaborn` – visualizations  
  - `scikit-learn` – preprocessing tools  

---

## 📦 Output  

- Final dataset cleaned and transformed for ML use
- **Shape after outlier removal:** _e.g., 860 rows × 8 columns_  
  _(Actual shape will depend on thresholds used in outlier detection)_

---
