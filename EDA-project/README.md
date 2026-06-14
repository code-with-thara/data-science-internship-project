# 🚢 Titanic Survival Prediction - Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to identify patterns and factors that influenced passenger survival. The analysis focuses on data cleaning, feature engineering, visualization, and extracting meaningful insights from the dataset.

---

## 🎯 Objectives

- Understand the structure and quality of the dataset.
- Perform data cleaning and preprocessing.
- Explore relationships between passenger attributes and survival.
- Identify key factors that influenced survival rates.
- Generate insights through statistical and visual analysis.

---

## 📂 Dataset

The dataset contains passenger information such as age, gender, ticket class, fare, embarkation point, and survival status.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Data Preparation

### Missing Value Handling

- Filled missing values in `Age` using the median.
- Filled missing values in `Embarked` using the mode.

### Feature Engineering

- Created `FamilySize` feature.
- Created `IsAlone` feature.

### Data Cleaning

- Removed unnecessary columns.
- Checked data consistency and data types.

---

## 🔍 Key Insights

### Gender
- Female passengers had significantly higher survival rates than male passengers.

### Passenger Class
- First-class passengers had better survival chances compared to other classes.

### Age
- Children showed higher survival rates than adults.

### Fare
- Passengers who paid higher fares generally had better survival outcomes.

---

## 📈 Analysis Performed

### Statistical Analysis
- Summary statistics
- Distribution analysis

### Visual Analysis
- Survival Distribution
- Gender vs Survival
- Passenger Class vs Survival
- Age Distribution

### Correlation Analysis
- Correlation Heatmap
- Feature Relationship Analysis

---

## 🎯 Outcome

The analysis revealed that gender, passenger class, age, and fare were among the most important factors influencing survival on the Titanic. These insights demonstrate how exploratory data analysis can uncover meaningful patterns within a dataset.
