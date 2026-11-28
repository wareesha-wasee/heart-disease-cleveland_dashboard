   ❤️ Heart Disease Cleveland – Data Analysis

An Exploratory Data Analysis (EDA) project using the Heart Disease Cleveland dataset to explore patient characteristics, clinical measurements, and recorded heart condition patterns.

---

📌 Project Overview

This project explores the Cleveland Heart Disease dataset to understand patterns and relationships among different health-related variables.

The analysis focuses on age, chest pain, cholesterol, resting blood pressure, maximum heart rate, and recorded heart condition.

---

🔎 Key Research Areas

- Age distribution of patients
- Cholesterol level distribution
- Most common chest pain type
- Distribution of recorded heart condition
- Relationship between age and maximum heart rate
- Relationship between cholesterol and resting blood pressure
- Average cholesterol by condition category
- Condition distribution across sex groups
- Missing values, duplicates, and outliers

---

📊 Dataset Information

Detail| Description
Dataset| Heart Disease Cleveland
Source| Kaggle – Heart Disease Cleveland UCI
Records| 297
Columns| 14
Missing Values| 0
Duplicate Rows| 0
Target Column| condition

Dataset Source: "Kaggle – Heart Disease Cleveland UCI" (https://www.kaggle.com/datasets/cherngs/heart-disease-cleveland-uci)

---

🛠️ Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Streamlit
- Jupyter Notebook

---

🧹 Data Preparation & Cleaning

- Imported and inspected the dataset using Pandas.
- Checked missing values and duplicate records.
- Reviewed data types.
- Identified potential outliers using the IQR method.
- Retained the identified outliers as potentially genuine measurements.

---

📈 Key Findings

1. Most patients in the dataset are between 50 and 65 years old.
2. Age and maximum heart rate show a negative correlation of approximately -0.395.
3. Condition has a positive correlation with thal (0.52) and ca (0.46).
4. Average cholesterol is 251.85 for condition 1 and 243.49 for condition 0.

These findings describe patterns in this dataset and are not medical conclusions.

---

📂 Project Structure

Heart-Disease-Cleveland/
│
├── EDA/
│   └── Heart_Disease_Data_Analysis.ipynb
│
├── Dataset/
│   └── heart_cleveland_upload.csv
│
├── app.py
├── requirements.txt
├── heart.png
└── README.md

---

📊 Interactive Streamlit Dashboard

The dashboard provides interactive exploration of the dataset through:

- Key performance indicators (KPIs)
- Age and patient profile charts
- Chest pain distribution
- Heart condition analysis
- Interactive filters
- Plotly visualizations
- Raw data exploration

🔗 Live Dashboard:
https://heart-disease-clevelanddashboard-hxbsnq9weetezfrsn8yza2.streamlit.app/

---

🚀 Project Status

- [x] Data preparation
- [x] Exploratory Data Analysis
- [x] Data visualization
- [x] Missing values and duplicate checks
- [x] Outlier analysis
- [x] Streamlit dashboard
- [x] GitHub repository

---

🎯 Conclusion

This project demonstrates how exploratory data analysis and interactive visualization can help identify patterns and relationships in a health-related dataset.

The findings provide an educational overview of the dataset and support further data exploration.

---

👩‍💻 Author

Wareesha

Data Analysis Project – Heart Disease Cleveland

GitHub Repository:
https://github.com/wareesha-wasee/heart-disease-cleveland_dashboard

Note: This project is for educational and data analysis purposes only. It is not intended for medical diagnosis or treatment.
 
 
