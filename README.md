# 🛳 Titanic Dataset - Exploratory Data Analysis (EDA)

This project presents a comprehensive Exploratory Data Analysis (EDA) of the famous Titanic dataset from Kaggle. The objective is to uncover patterns, detect anomalies, and gain insights into the factors that influenced passenger survival during the Titanic disaster.

---

## 📂 Dataset Overview

- **Source**: [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)
- **Files Used**: `train.csv`
- **Target Variable**: `Survived` (0 = No, 1 = Yes)

---

## 🧪 EDA Objectives

- Understand the structure and contents of the dataset
- Handle missing values and data anomalies
- Analyze feature distributions and their relationship with survival
- Identify key predictors of survival
- Visualize trends and insights using plots

---

## 🔍 Key Insights

### 🎯 Target Distribution
- **62% did not survive**, while **38% survived**

### 🧑‍🤝‍🧑 Gender vs Survival
- **Females** had a much higher survival rate (~74%) than **males** (~19%)

### 🛏️ Class vs Survival
- 1st Class: ~63% survived  
- 2nd Class: ~47% survived  
- 3rd Class: ~24% survived

### 🎂 Age Distribution
- Median age: ~28 years
- Children had a higher survival chance, especially in 1st and 2nd class

### 👪 Family Size Effect
- Passengers with **1–2 family members** had higher survival rates than those alone or in large groups

### 💸 Fare Distribution
- Higher fare was positively correlated with survival

### ⛴️ Embarkation Port
- Passengers from **Cherbourg (C)** had the highest survival rate (~55%)

---

## ⚠️ Data Anomalies Identified

- Missing values in:
  - `Age` (~20%)
  - `Cabin` (~77%)
  - `Embarked` (2 rows)
- Fare outliers (e.g. \$512)
- Mixed data formats in `Ticket` and `Cabin`
- Uncommon family sizes (e.g., `SibSp = 8`)
- Imbalance in categorical features (`Sex`, `Embarked`)

---

## 📊 Visualizations Used

- Bar plots 
- Histograms 
- Box plots

---

## 🛠 Tools & Libraries

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn


