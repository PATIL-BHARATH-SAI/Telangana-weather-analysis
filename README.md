# 🌦 Telangana Weather & Climate Data Analysis

## 📘 Project Overview
This project analyzes **Telangana’s weather and climate data (2010–2024)** to uncover trends, anomalies, and actionable insights using **Power BI** and **Exploratory Data Analysis (EDA)** techniques.  

The study highlights how weather variations impact **agriculture, health, infrastructure, and energy** — providing valuable insights for **policy-making**, **disaster management**, and **sustainable development**.

---

## 🧠 Problem Statement
Weather fluctuations significantly affect multiple sectors:

- 🌾 **Agriculture** — Crop yield prediction, irrigation planning  
- 🏥 **Health** — Heatwave and humidity-related illness tracking  
- 🏗 **Infrastructure & Transport** — Flood risk analysis  
- ⚡ **Renewable Energy** — Wind and solar forecasting  

**Goal:**  
To analyze weather data (rainfall, temperature, humidity, and wind) across Telangana’s districts and identify **seasonal patterns**, **extreme events**, and **long-term climate trends**.

---

## 🎯 Objectives
- Analyze rainfall, temperature, humidity, and wind across districts/mandals  
- Identify extreme events, anomalies, and trends  
- Compare district-level weather patterns  
- Provide insights for agriculture, health, and policy planning  

---

## 🧩 Data Information
**Data Source:** Scraped weather datasets from public sources such as **IMD** and **Climate Data Online**  
**Size:** ~6,51,000 rows × 9 columns  
**Time Period:** 2010–2024  
**Granularity:** Daily → Aggregated to monthly/seasonal/yearly  

**Columns:**
- District  
- Mandal  
- Date  
- Rain (mm)  
- Min Temp / Max Temp  
- Min Humidity / Max Humidity  
- Min Wind Speed / Max Wind Speed  

---

## 🧹 Data Cleaning & Preparation
Key steps:
- Removed duplicates & missing values  
- Handled inconsistent formats and units  
- Interpolated missing data  
- Standardized column names  
- Treated outliers (using Winsorization)  
- Converted data types (dates, numerics, categoricals)

---

## 🔧 Data Transformation & Feature Engineering
- **Created new features:**
  - `Temperature Range = Max Temp – Min Temp`  
  - `Humidity Range = Max Humidity – Min Humidity`  
  - `Wind Range = Max Wind Speed – Min Wind Speed`
- **Extracted** Year, Month, Quarter, and Season for trend analysis  
- **Aggregated** data at district and yearly levels  
- **Normalized** numerical features for fair comparison  

---

## 📊 Exploratory Data Analysis (EDA)
Performed in **Power BI** and optionally with **Python**

### 🔹 Univariate Analysis
- Distribution of rainfall, temperature, humidity, and wind  
- Summary statistics: mean, median, std, variance  

### 🔹 Bivariate Analysis
- Rainfall vs Temperature correlation  
- Humidity vs Rainfall relationship  
- District-wise comparison using bar and line charts  
- Seasonal and year-over-year trend analysis  

---

## 🧾 Key Business Questions
1. Which districts experience the highest and lowest rainfall?  
2. What are the seasonal weather patterns?  
3. How do rainfall, temperature, humidity, and wind correlate?  
4. Which districts face extreme weather events?  
5. What are the long-term temperature and rainfall trends?  

---

## 💡 Insights & Conclusion
- 🌧 **Rainfall:** 70% concentrated during monsoon season  
- 🌡 **Temperature:** Rising yearly trend — possible climate change indicator  
- 💧 **Humidity:** Strong correlation with rainfall levels  
- 🌬 **Wind Speed:** Extreme events observed in open/coastal districts  
- 📈 **Overall:** Clear evidence of *seasonality*, *anomalies*, and *long-term climate shifts*

---

## 🧰 Tools & Technologies
- **Power BI** — Interactive dashboards & visualizations  
- **Excel / CSV** — Data preprocessing & cleaning  
- **Python (optional)** — For feature engineering and analysis  
- **IMD Data Sources** — Raw dataset extraction  

---

## 👨‍💻 Author
**Name:** Patil Bharath Sai  
**University:** Kalasalingam Academy of Research and Education, Tamil Nadu  
**Degree:** B.Tech – CSE (AI & ML)  

### 💼 Work Experience
- DevTown – Data Science Intern  
- Bharat Intern – Machine Learning Intern  
- My Company – Backend Developer  
- Forage – Accenture Data Analyst Virtual Internship  

### 🌐 Connect With Me
- [LinkedIn](https://www.linkedin.com/in/patil-bharath-sai-b7065027a/)  
- [GitHub](https://github.com/PATIL-BHARATH-SAI)

---

## 📁 Project Files
| File Name | Description |
|------------|-------------|
| `Telangana_Weather_Climate_Analysis.pbix` | Power BI Dashboard file |
| `Telangana_Weather_Report_EDA_Project_Innomatics_Project.pptx` | Project Presentation |

---

## 🚀 Future Work
- Integrate real-time weather APIs for live insights  
- Build ML models for rainfall and temperature prediction  
- Expand project scope to include pan-India weather data  

---

## 🙏 Acknowledgements
- **IMD (Indian Meteorological Department)** for weather data  
- **Innomatics Research Labs** for project guidance  
- Mentors and peers for feedback and support  

---

### ⭐ If you found this project interesting, don’t forget to star the repo and follow for updates!
