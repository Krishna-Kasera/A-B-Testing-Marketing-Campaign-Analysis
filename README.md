# A/B Testing: Marketing Campaign Analysis

## 📌 Project Overview
This project analyzes the effectiveness of **Advertisements (Ads) vs. Public Service Announcements (PSAs)** in driving conversions. The goal is to determine which approach yields higher engagement and conversion rates using **A/B testing** and statistical analysis.

### 📊 Key Findings
- **Ads significantly outperform PSAs** in driving conversions.
- **Statistical results:**
  - **Absolute Conversion Rate Difference:** 0.84%
  - **Relative Improvement:** 47.14%
  - **Z-Statistic:** 6.21 (indicating a strong difference)
  - **P-Value:** ~0.0 (high statistical significance)
- **Conclusion:** Ads are much more effective than PSAs for conversion optimization.

---
## 🧪 Methodology
### **1. Data Collection & Preprocessing**
- Dataset includes user interactions with **Ads and PSAs**.
- Random sampling ensures equal distribution across groups.
- Conversion rates are compared between groups.
- **Outlier Filtering:** The **Interquartile Range (IQR) method** is used to dynamically filter outliers and ensure a more accurate analysis.
- **Database Connection:** The dataset was **migrated from CSV into SQL Server Management Studio (SSMS)** and connected to both **Python and Power BI** for analysis and visualization.

### **2. Statistical Analysis**
- **A/B Testing Approach:** 
  - A **Z-Test for proportions** was conducted to assess statistical significance.
  - The p-value determines whether the observed difference is due to chance.
  
- **Interpretation of Results:**
  - A p-value < 0.05 means the difference is **statistically significant**.
  - A high Z-score confirms the difference is **not due to random chance**.

---
## 📈 Power BI Analysis & DAX Measures
### **Power BI Visualizations Include:**
- **Total Impressions & Conversion Rates by Day/Hour**
- **User Reach & Engagement Patterns**
- **Conversion Rate Trends with Confidence Intervals**
- **Comprehensive Analysis of Campaign and A/B Test**

---
## 📂 Files Included
| File Name | Description |
|-----------|-------------|
| `marketing_AB.csv` | Raw dataset containing A/B test data |
| `AB Testing.ipynb` | Jupyter Notebook with statistical analysis & calculations|
| `dashboard.pbix` | Power BI project file for deeper analysis |
| `measures.txt` | List of DAX measures used in Power BI |
| `description.txt` | A brief description of the project and dataset |
| `output.csv` | Processed A/B test results from the Jupyter Notebook |

## 🌐 Link to Deployed Dashboard
[View the interactive Power BI Dashboard](https://app.powerbi.com/reportEmbed?reportId=ae681465-0b11-445b-8fc9-b5bb2fcb9a77&autoAuth=true&ctid=d8d6e7dc-2b15-43c5-81fd-2efc145c9d2c)

## 🚀 Conclusion & Recommendations
- **Ads drive significantly higher conversions** than PSAs.
- **Marketing teams should prioritize ads** for conversion optimization.
- **Further analysis:** Experiment with different ad formats & targeting strategies.

## 🤝 Contributing
Feel free to raise issues or suggest improvements via GitHub!

---
## 📝 License
MIT License - You are free to use, modify, and distribute this project.


