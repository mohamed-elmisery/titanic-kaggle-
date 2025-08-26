# Titanic Dataset Exploration – Elevvo Internship Task 2

## 🚢 Project Overview
This project is part of the **Elevvo Internship – Task 2**.  
The goal was to explore the classic **Titanic dataset** from Kaggle, perform data cleaning, feature engineering, and visualize patterns affecting passenger survival.

---

## 🎯 Objectives
- Handle missing values and clean the dataset
- Engineer new features to enhance analysis
- Encode categorical variables for modeling
- Visualize survival patterns across different groups
- Gain practical experience with Python, Pandas, and data visualization

---

## 🛠️ Tools Used
- Python 3.x  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 🔹 Data Cleaning & Feature Engineering
- **Handled missing values:**  
  - `Age` → filled with median  
  - `Embarked` → filled with mode  
  - `Cabin` → created `Cabin_flag` (1 if cabin exists, 0 otherwise)  
- **Engineered features:**  
  - `FamilySize` = SibSp + Parch + 1  
  - `IsAlone` = 1 if traveling alone, 0 otherwise  
  - `Title` extracted from Name (Mr, Mrs, Miss …), rare titles grouped as `Rare`  
- **Encoded categorical variables:**  
  - `Sex`, `Embarked`, `Title` → numeric or one-hot encoding  

---

## 🔹 Key Features Used
`Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, `Cabin_flag`, `FamilySize`, `IsAlone`, `Embarked`, `Title`

---

## 📊 Data Visualization
- Survival rates by **Gender**  
- Survival rates by **Passenger Class (Pclass)**  
- Correlation heatmap of numerical features  

*(Attach your plots/screenshots here)*

---

## 🌟 Insights
- Females had higher survival rates than males  
- Higher classes had higher survival  
- Certain titles and family sizes affected survival  

---

## 💡 Human Perspective
Working on this dataset highlighted how **data tells human stories**. It provided insight into historical events while developing skills in **Python, data cleaning, feature engineering, and visualization**.

---

## 📁 Project Structure

