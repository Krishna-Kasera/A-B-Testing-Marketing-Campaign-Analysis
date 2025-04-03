# A/B Testing: Marketing Campaign Analysis

## 📌 Project Overview
This project looks at how well **Advertisements (Ads)** work compared to **Public Service Announcements (PSAs)** when it comes to getting people to take action (convert). By using **A/B testing** and some number crunching, we want to find out which of the two gets more people engaged and leads to more conversions.

### 📊 Key Findings
- **Ads are much better than PSAs** at getting people to convert.
- **Statistical results:**
  - **Difference in Conversion Rate:** 0.60%
  - **Improvement Percentage:** 45.94%
  - **Z-Statistic:** 6.49 (this means there’s a strong difference)
  - **P-Value:** rounded to around 0.0 (showing high significance)
- **Conclusion:** Ads are way more effective than PSAs for getting conversions.

---
## 🧪 Methodology
### **1. Data Collection & Preparation**
- ** Data Downloading:** We downloaded the data from Kaggle into local device. - [**Link to Dataset**](https://www.kaggle.com/datasets/faviovaz/marketing-ab-testing)
- **Outlier Filtering:** We used the **Interquartile Range (IQR) method** to remove any unusual data points for a more accurate analysis.
- **Database Connection:** We **migrated the dataset from Kaggle to SQL Server Management Studio (SSMS)** and connected it to **Python and Power BI** for further analysis and visualization.

### **2. Statistical Analysis**
- **A/B Testing Approach:** 
  - We used a **Z-Test for proportions** to see if the differences were statistically significant.
  - The p-value helps us understand if what we’re seeing is just random chance.

- **Interpreting the Results:**
  - If the p-value is less than 0.05, the difference is considered **statistically significant**.
  - A high Z-score means the difference is **not just random**.

---
## 📈 Power BI Analysis & DAX Measures
### **Power BI Visualizations Include:**
- **Total Impressions & Conversion Rates by Day/Hour**
- **Patterns in User Reach & Engagement**
- **Trends in Conversion Rates with Confidence Intervals**
- **Detailed Analysis of the Campaign and the A/B Test**

---
## 📂 Files Included
| File Name | Description |
|-----------|-------------|
| `marketing_AB.txt` | Link to the dataset from Kaggle |
| `AB Testing.ipynb` | Jupyter Notebook with the analysis and calculations |
| `dashboard.pbix` | Power BI project file for more detailed analysis |
| `measures.txt` | List of DAX measures used in Power BI |
| `data description.txt` | Brief description of the dataset columns |
| `conversion_statistics.csv` | Processed results from the A/B test |

## 🌐 Link to Deployed Dashboard
[View the interactive Power BI Dashboard](https://app.powerbi.com/reportEmbed?reportId=ae681465-0b11-445b-8fc9-b5bb2fcb9a77&autoAuth=true&ctid=d8d6e7dc-2b15-43c5-81fd-2efc145c9d2c)

## 🚀 Conclusion & Recommendations
- **Ads drive significantly higher conversions** than PSAs.
- **Marketing teams should prioritize ads** for conversion optimization.
- **Further analysis:** Whether timing when the most ads were shown affect conversion.

## 🤝 Contributing
Feel free to raise issues or suggest improvements via GitHub!

---
## 📝 License
MIT License - You are free to use, modify, and distribute this project.
