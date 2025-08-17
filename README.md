
# 🏅 Olympics BMI Analysis

## 📌 Project Overview

This project analyzes **Olympic athlete data** with a focus on **Body Mass Index (BMI) trends**.  
By combining the **120 Years of Olympic History dataset** with a derived **BMI dataset**, it explores how BMI varies across **sports, gender, and time**, providing valuable health and performance insights.

## 🎯 Objectives

- Calculate and analyze BMI of Olympic athletes  
- Identify trends across **sports, genders, and years**  
- Compare BMI distributions for different athlete groups  
- Provide an **interactive Streamlit dashboard** for exploration  

## 📊 Dataset

- **Primary dataset**: [120 Years of Olympic History: Athletes and Results (Kaggle)](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results)  
- **Derived dataset**: `athlete_bmi_dataset.csv` (BMI values calculated from height & weight)  

⚠️ The original `athlete_events.csv` exceeds GitHub size limits, so it is included as a **compressed file (`athlete_events.zip`)**.  

## 🛠️ Methodology

The project was carried out in six structured steps:

1. **Data Ingestion**  
   - Imported the Olympic dataset (`athlete_events.csv`) and the derived BMI dataset (`athlete_bmi_dataset.csv`).  
   - Used a compressed version of the dataset to handle GitHub’s file size limits.  

2. **Data Cleaning & Preprocessing**  
   - Filled missing values in height, weight, and age.  
   - Converted data types and removed redundant columns.  
   - Standardized athlete records across different years and sports.  

3. **BMI Calculation**  
   - Calculated BMI using the formula:  
     \[
     BMI = \frac{Weight(kg)}{Height(m)^2}
     \]  
   - Classified BMI into categories: **Underweight, Normal, Overweight, Obese**.  

4. **Exploratory Data Analysis (EDA)**  
   - Generated summary statistics for athletes.  
   - Analyzed BMI distributions by gender, sport, and country.  
   - Studied BMI changes across Olympic years.  

5. **Visualization**  
   - Designed clear and informative charts for BMI distributions and trends.  
   - Compared BMI across countries, sports, and genders.  
   - Used **Matplotlib, Seaborn, and Plotly** for static and interactive visuals.  

6. **Interactive Dashboard**  
   - Built an interactive dashboard using **Streamlit**.  
   - Added filters (Year, Sport, Gender, Country) for dynamic exploration.  
   - Integrated simple predictive features (e.g., weight estimation from height).  

✔️ This workflow ensured **clean data, precise BMI insights, meaningful visualizations, and an interactive user-friendly dashboard**.

## 🚀 Features

- 📊 BMI distribution by **sport & gender**  
- 📈 Trend analysis across Olympic years  
- 🌍 Country-wise athlete BMI comparisons  
- 🏃 Interactive filtering with Streamlit  

## 📂 Project Structure

```

olympics-bmi-analysis/
│── app.py                # Streamlit application
│── requirements.txt      # Dependencies
│── README.md             # Documentation
│
├── data/
│   ├── athlete\_bmi\_dataset.csv
│   ├── athlete\_events.zip   # compressed dataset (<25 MB)
│
└── docs/
└── (optional project notes)

````

## ⚙️ Installation & Running Locally

### 1️⃣ Clone this repository
```bash
git clone https://github.com/prachi9303/olympics-bmi-analysis.git
cd olympics-bmi-analysis
````

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Streamlit app

```bash
streamlit run app.py
```

## 📈 Key Findings

* **BMI varies significantly across sports** (e.g., gymnasts vs. weightlifters)
* **Gender differences** in BMI patterns are consistent across decades
* Over time, **variation in BMI has increased**, showing diverse athletic body types

## 🌟 Future Improvements

* Add **predictive modeling** for BMI & performance
* Include **geographic visualizations** (BMI by country maps)
* Deploy app on **Streamlit Cloud / Hugging Face**


# DataAnalytics # DataScience # AthleteAnalytics # Visualization



