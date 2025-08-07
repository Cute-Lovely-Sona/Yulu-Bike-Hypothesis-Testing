![Yulu](https://upload.wikimedia.org/wikipedia/commons/e/ea/Yulu_Logo.jpg)

# 🚲 Yulu Bike Demand Prediction – Hypothesis Testing Project

> This project focuses on identifying which factors significantly impact the demand for shared electric cycles using hypothesis testing.

---

## 🚀 Project Overview

Yulu is a micro-mobility platform offering electric cycles. The company faced a decline in demand and wanted to explore key factors affecting rentals such as season, weather, and working day status.

---

## 🧠 Key Business Questions

- Does working day impact bike rental demand?
- Is demand different across seasons?
- Does weather influence the number of rentals?
- Are weather and season dependent on each other?

---

## 📊 Summary of Insights

- ✅ Rentals are higher on **working days**
- ✅ Rental demand is **not equal across seasons**
- ✅ Weather significantly affects usage
- ✅ Weather is dependent on the season

---

## 🛠️ Tools & Technologies Used

- Python  
- Pandas  
- Matplotlib / Seaborn  
- SciPy (T-test, ANOVA, Chi-square)  
- Jupyter Notebook  

---

## 📈 Exploratory Data Analysis (`Yulu_Business_Case_Study_Sona.ipynb`)

> 📌 Objective: Explore dataset and find variable relationships

- Checked datatypes, missing values, and summary
- Plotted histograms, boxplots, and bar charts
- Performed univariate and bivariate analysis
- Visualized distributions across weather, season, working days

---

## 🧪 Hypothesis Testing

> 📌 Objective: Test business assumptions with statistical methods

- ✅ **T-test**: Working day vs non-working day rentals
- ✅ **ANOVA**: Rentals across different seasons and weather
- ✅ **Chi-square test**: Dependency between weather and season

---

## 📂 Dataset Info

- Columns: datetime, season, holiday, workingday, weather, temp, humidity, windspeed, casual, registered, count  
- Target Variable: **count** (total rentals)

---

## 📌 Outcome

Yulu can optimize fleet deployment based on season, working day, and weather to increase overall demand and operational efficiency.

