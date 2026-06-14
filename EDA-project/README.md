🚢 Titanic Survival Prediction - Exploratory Data Analysis (EDA)

📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to uncover patterns, trends, and factors that influenced passenger survival. The analysis includes data cleaning, feature engineering, statistical exploration, and data visualization to gain meaningful insights and prepare the dataset for future predictive modeling.

---

🎯 Objectives

- Explore and understand the Titanic dataset
- Assess and improve data quality
- Handle missing values effectively
- Create meaningful features for analysis
- Identify factors affecting passenger survival
- Generate insights through visualization and statistical analysis
- Prepare the dataset for machine learning models

---

📂 Dataset

The dataset used is Titanic-Dataset.csv, which contains passenger details such as PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, and Embarked.

---

🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

📊 Data Preparation

The following preprocessing steps were performed:

- Missing values in Age were filled using the median value.
- Missing values in Embarked were filled using the most frequent category.
- New features such as Title, FamilySize, and IsAlone were created.
- Categorical variables were encoded for analysis and modeling.
- Data quality checks were performed to ensure consistency and completeness.

---

🔍 Key Insights

##Gender

Female passengers had a significantly higher survival rate than male passengers.

##Passenger Class

Passengers traveling in higher classes had better chances of survival compared to those in lower classes.

##Age

Children generally showed higher survival rates than many adult passengers.

##Family Size

Passengers traveling with small families were more likely to survive than those traveling alone or in very large families.

##Fare

Higher ticket fares were associated with increased survival rates.

##Cabin Availability

Passengers with recorded cabin information tended to have higher survival rates, suggesting a relationship between cabin allocation and passenger class.

---

📈 Analysis Performed

- Data Quality Assessment
- Missing Value Analysis
- Statistical Summary Analysis
- Feature Engineering
- Survival Analysis
- Correlation Analysis
- Data Visualization

Visualizations Included

- Survival Distribution
- Survival by Gender
- Survival by Passenger Class
- Age Distribution
- Family Size Analysis
- Correlation Heatmap

---

🎯 Outcome

The exploratory analysis identified several important factors influencing passenger survival, including gender, passenger class, fare, age, family size, and cabin availability. These findings provide valuable insights into the dataset and establish a strong foundation for building predictive machine learning models.

