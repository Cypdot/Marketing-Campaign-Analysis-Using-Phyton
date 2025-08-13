# 📊 Marketing Campaign Performance Analysis

## 📌 Project Overview
This project analyzes a marketing campaign dataset to uncover performance trends, calculate key marketing metrics, and generate actionable insights.  
The goal is to help decision-makers understand which campaigns work best and how to optimize marketing strategies for higher returns.

The analysis includes:
- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Key metric calculations
- Insight generation
- Data visualization
- Recommendations for improvement

---

## 📂 Dataset Overview
- **Rows:** 200,005  
- **Columns:** 15  
- **Key Metrics:** ROI, Click-Through Rate (CTR), Cost Per Click (CPC), Conversion Rate  
- **Channels Analyzed:** Google Ads, Instagram, Facebook, Email, and more.  

*(Dataset included only if publicly available; otherwise link to source)*

---

## 🛠 Tools & Technologies
- **Python** – Pandas, Matplotlib, Seaborn
- **Jupyter Notebook**
- **Google Slides** for presentation

---

## 🔍 Analysis Workflow
1. **Data Cleaning**
   - Removed special characters from column names.
   - Converted dates to a consistent format.
   - Handled missing values.
   
2. **Initial Exploration**
   - Calculated dataset statistics (mean, median, std).
   - Checked unique values for key categorical columns.
   - Identified outliers in metrics like CPC and CTR.

3. **Metric Calculations**
   - **CTR** = (Clicks / Impressions) × 100  
   - **CPC** = Spend / Clicks  
   - **Conversion Rate** = (Conversions / Clicks) × 100  

4. **Visualization**
   - Bar charts comparing ROI by channel.
   - Line charts showing CTR trends over time.
   - Scatter plots of CPC vs. CTR.
   - Heatmaps for correlation analysis.

5. **Insight Generation**
   - Found top-performing channels based on ROI and CTR.
   - Highlighted campaigns with unusually high CPC for review.
   - Identified location-based trends in conversions.

---

## 📈 Key Insights
- **Google Ads** and **Instagram** deliver the highest conversion rates.
- Some campaigns have extremely high CPC, suggesting budget inefficiency.
- Lower CPC is generally linked to higher CTR.
- Location plays a significant role in campaign performance.

---

## 🚀 Recommendations
- Reallocate budget from high-CPC underperformers to high-ROI campaigns.
- Investigate unusually high CPC campaigns for possible targeting or bidding issues.
- Leverage high-performing channels for seasonal promotions.
- Optimize ad creatives in low-conversion locations.

---

## 📁 Repository Contents
- `marketing_campaign_analysis.ipynb` – Full Python analysis code.
- `presentation_slides.pdf` – Final presentation slides with charts & insights.


