# National-Family-Health-Survey-NFHS-Data-Analysis
This project provides an exploratory data analysis (EDA) of the National Family Health Survey (NFHS) dataset. NFHS is a large-scale survey that collects information on population, health, nutrition, and socio-economic indicators across districts and states in India.

# 📊 NFHS Data Analysis

[![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)](https://www.python.org/)  
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)  

---

## 🔹 Overview
This project provides an **exploratory data analysis (EDA)** of the **National Family Health Survey (NFHS)** dataset, which captures key statistics on **population, health, nutrition, education, and socio-economic indicators** across India.  

The analysis focuses on:
- Understanding **district and state-wise trends**
- Identifying **health, literacy, and child nutrition gaps**
- Visualizing **correlations and patterns** in socio-economic and health indicators

---

## 📂 Dataset
- **Source:** [NFHS Official Website](https://rchiips.org/nfhs/)  
- **Data Size:** ~706 districts × 109 attributes  
- **Key Features:**
  - Demographics: Population age groups, sex ratio, households
  - Education: Literacy, school attendance
  - Health: BMI, blood pressure, anaemia, diabetes
  - Child indicators: Vaccination, stunting, wasting, breastfeeding
  - Lifestyle: Tobacco & alcohol consumption
  - Maternal & family planning: Antenatal visits, institutional births

---

## 🗂 Project Structure

NFHS_Data_Analysis/
│
├── data/
│ └── NFHS_cleaned.csv
│
├── notebooks/
│ ├── NFHS_EDA.ipynb
│ └── NFHS_Correlation_Analysis.ipynb
│
├── plots/
│ ├── literacy_distribution.png
│ └── child_nutrition.png
│
├── README.md
└── requirements.txt


---

## 📈 Analysis & Visualizations
1. **Data Cleaning & Preprocessing**
   - Missing values handled  
   - Standardized column names  
   - Converted percentages and numeric values  

2. **Descriptive Statistics**
   - Histograms, boxplots, and distributions for literacy, health, and nutrition  

3. **Correlation Analysis**
   - Heatmaps to identify relationships between indicators  
   - Example: Maternal education vs child nutrition  

4. **Comparative Analysis**
   - Men vs Women lifestyle habits (tobacco & alcohol)  
   - State-wise literacy and health metrics  

5. **Key Insights**
   - Wide disparities in women literacy across districts  
   - Child malnutrition (stunting, wasting) remains a challenge  
   - Strong correlation between maternal education and child health outcomes  

---

## 🛠 Technologies Used
- **Python 3.x**  
- **Pandas & NumPy** – Data cleaning & manipulation  
- **Matplotlib & Seaborn** – Visualizations  
- **Jupyter Notebook** – Analysis & reporting  

---

## ⚡ How to Run
1. **Clone the repository**
```bash
git clone https://github.com/yourusername/NFHS_Data_Analysis.git
cd NFHS_Data_Analysis
