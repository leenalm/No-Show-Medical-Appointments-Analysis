# 📊 No-show Appointments Data Analysis

## 🧠 Overview
This project was completed as part of the **Udacity Data Analyst Nanodegree**.  
It analyzes the **No-show Appointments** dataset from Kaggle, which contains information about medical appointments in Brazil and whether patients showed up or not.  
The goal of this project is to identify the factors that influence patient attendance and explore trends related to demographics, medical history, and scheduling.

Dataset link: [No-show Appointments Dataset](https://www.kaggle.com/datasets/joniarroba/noshowappointments)

---

## 📁 Project Files
- `no_show_analysis.ipynb` – Main Jupyter Notebook containing all code, analysis, and visualizations  
- `no_show_analysis.html` – Static exported version for easy viewing  
- `data/` – Folder containing the dataset  
- `README.md` – Project documentation  

---

## 🧰 Tools & Libraries
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## 🔍 Project Objectives
The analysis explores the following questions:

1. Is there a relationship between patient **age** and the likelihood of showing up for an appointment?  
2. Do patients with certain **medical conditions** (hypertension, diabetes, alcoholism, or disabilities) have higher no-show rates compared to others?  
3. On which **days of the week** are patients most likely to miss their appointments?

---

## ⚙️ Data Cleaning & Preparation
- Handled missing and duplicate values  
- Corrected column data types for dates and booleans  
- Renamed columns for readability  
- Removed irrelevant or misleading variables (if any)  
- Created derived columns such as appointment weekday and waiting time  

---

## 📈 Exploratory Data Analysis (EDA)
Exploratory analysis was performed to understand the key patterns in the data.  
Visualizations were used to uncover trends and relationships.

Key findings include:
- **Age Effect:** Younger patients had higher no-show rates compared to older groups.  
- **Health Conditions:** Patients with chronic conditions such as hypertension and diabetes showed slightly better attendance rates.  
- **Day of Week:** The highest number of missed appointments occurred on **Wednesdays and Fridays**.  

---

## Skills Demonstrated
- Data cleaning and preprocessing using Pandas  
- Exploratory data analysis (EDA)  
- Data visualization using Matplotlib and Seaborn  
- Analytical storytelling and insight generation  
- Python data manipulation and reporting  
