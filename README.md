 
# ❤️ Heart Disease Cleveland – Data Analysis & Dashboard

## 📌 Project Overview
This project focuses on Exploratory Data Analysis (EDA) and interactive visualization of the Heart Disease Cleveland dataset. The goal is to explore patient health information and identify patterns related to heart disease.

## 📊 Dataset Information
- **Dataset Name:** Heart Disease Cleveland
- **Source:** [Kaggle – Heart Disease Cleveland UCI](https://www.kaggle.com/datasets/cherngs/heart-disease-cleveland-uci)
- **Total Records:** 297
- **Total Features:** 14
- **Target Column:** `condition`

## 🛠️ Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Streamlit

## 📈 Dashboard Features
- Interactive sidebar filters
- Four key performance indicators (KPIs)
- Age distribution analysis
- Cholesterol distribution
- Chest pain type analysis
- Heart condition comparison
- Age and maximum heart rate relationship
- Correlation heatmap
- Raw data viewer

## 🔍 Key Findings
- No missing values were found in the dataset.
- No duplicate records were found.
- Age and maximum heart rate show a negative correlation.
- Average cholesterol is higher in patients with heart disease in this dataset.
- Potential outliers were identified during analysis.

## 📁 Project Files
- `app.py` – Streamlit dashboard application
- `heart_cleveland_upload.csv` – Dataset
- `Heart_Disease_Data_Analysis.ipynb` – EDA notebook
- `heart.png` – Dashboard illustration
- `requirements.txt` – Required Python libraries
- `.gitignore` – Files excluded from Git tracking

## ▶️ How to Run the Project

Install the required libraries:

```bash
pip install -r requirements.txt
```

Run the Streamlit application:

```bash
streamlit run app.py
```

## 👩‍💻 Author
Created as a Data Analysis and Visualization project.
