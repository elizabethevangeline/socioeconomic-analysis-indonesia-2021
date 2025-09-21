# ⚖️ Economic Inequality in Indonesia (2021)

## 📌 Project Overview  
This project explores **socio-economic inequality in Indonesia (2021)** using publicly available data from BPS (via Kaggle).  
The goal is to uncover **patterns, disparities, and insights** across provinces — focusing on poverty, education, life expectancy, and economic output (PDRB).  

I use **R (tidyverse, ggplot2, corrplot)** for data cleaning, EDA, and visualization.

---

## 📂 Dataset  
- **Name**: Socio-Economic of Indonesia in 2021  
- **Source**: [Kaggle](https://www.kaggle.com/datasets/dannytheodore/socio-economic-of-indonesia-in-2021?resource=download)  
- **Shape**: 34 provinces × multiple socio-economic indicators  
- **Focus Variables**: Poverty rate, PDRB, Life expectancy, Education, Expenditure per capita  

---

## 🧼 Data Preprocessing  
- Checked and handled *missing values*  
- Encoded categorical variables (province, city/regency)  
- Subsetted numerical variables for correlation analysis  
- Used descriptive statistics (`summary()`) to get an overview  

---

## 📊 Exploratory Data Analysis (EDA)  
- **Descriptive Stats**: mean, median, distribution per indicator  
- **Visualizations**:  
  - Histogram → distribution of poverty rates, PDRB  
  - Correlation heatmap → links between education, income, and life expectancy  
  - Bar chart → top/bottom provinces in poverty & expenditure  
  - Scatter plot → PDRB vs Life Expectancy (positive trend)  
  - Boxplot → variation in average years of schooling  

---

## 🔎 Key Insights  
- **Papua** → highest poverty rate despite relatively high expenditure → economic gap inside the region  
- **Java provinces** → consistently higher education level & life expectancy  
- Strongest correlation: **education ↔ expenditure per capita (0.668)** → education investment strongly tied to income  
- Provinces with low PDRB often overlap with lower education and higher poverty  

---

## ✅ Conclusion  
- Economic inequality in Indonesia remains **regionally skewed**.  
- **Java vs Eastern Indonesia** (Papua, Maluku, NTT) shows the sharpest divide.  
- Education stands out as a **key driver for reducing poverty and boosting welfare**.  

---

## 🚀 Future Work  
- Try clustering (K-Means) to group provinces by socio-economic similarity  
- Time series comparison (2020 vs 2021 vs 2022) if data is available  
- Interactive dashboard Power BI  

---

## 📚 References  
- [Dataset: Socio-Economic of Indonesia 2021 (Kaggle)](https://www.kaggle.com/datasets/dannytheodore/socio-economic-of-indonesia-in-2021?resource=download)  
- [Exploratory Data Analysis - Wikipedia](https://en.wikipedia.org/wiki/Exploratory_data_analysis)  
- [Pearson Correlation - UB Statistika](https://ss.mipa.ub.ac.id/korelasi-pearson/)  
