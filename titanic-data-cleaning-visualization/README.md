# 🚢 Titanic Data Cleaning and Visualization Project
Data cleaning, preprocessing, and visualization of the Titanic dataset to extract meaningful insights.

## 📌 Introduction
This project focuses on cleaning, preprocessing, and visualizing the Titanic dataset to understand the factors that influenced passenger survival. The goal is to extract meaningful insights from the data.

---

## 🛠️ Tools Used
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Jupyter Notebook / Google Colab  

---

## 📂 Dataset
The dataset used is `Titanic-Dataset.csv`, which contains passenger details such as PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, and Embarked.

---

## ⚙️ Methodology

### 📥 Data Loading and Inspection
- Loaded dataset using Pandas  
- Checked structure using `info()` and `head()`  
- Identified missing values and duplicates  

---

### 🧹 Data Cleaning
- Age → filled with mean value  
- Embarked → filled with mode value  
- Cabin → converted into feature `HasCabin`  
- No duplicate rows found  
- Outliers handled using IQR method  

---

### 🧠 Feature Engineering
- FamilySize = SibSp + Parch + 1  
- Title extracted from Name and grouped  

---

### 📊 Data Visualization & Insights
- Survival distribution by gender  
- Passenger class impact on survival  
- Age distribution analysis  
- Fare vs survival relationship  
- Family size impact on survival  

---

## 🎯 Conclusion
This project demonstrates a complete data analysis workflow from raw data to insights. Key factors such as gender, passenger class, fare, and family size strongly influenced survival outcomes.

Dataset is now clean and ready for machine learning models.
