# 🛍️ AAL Sales Analysis – Q4 2020

**Author**: DIPTENDU LODH  
**Project**: Sales Performance Analysis of AAL (Australia Apparel Limited)  
**Quarter**: Q4 2020 (October–December)  
**Tools**: Python, Pandas, NumPy, Seaborn, Matplotlib, JupyterLab

---

## 📈 Project Overview

AAL is a prominent Australian clothing brand operating across various states and cities, catering to a broad customer base from kids to seniors. This project analyzes AAL’s sales data for Q4 2020 to:

- Identify high and low-performing states.
- Evaluate demographic performance (Kids, Women, Men, Seniors).
- Generate time-based sales trends.
- Enable data-driven decision-making for the upcoming year.

The head of Sales & Marketing has requested an in-depth analysis to inform investment decisions and sales strategy optimization.

---

## ✅ Project Objectives

### 1. **Data Wrangling**
- Handle missing data via median imputation.
- Normalize `Sales` and `Unit` columns using MinMaxScaler.
- Clean and standardize column names.
- Group data for insightful aggregation.

### 2. **Data Analysis**
- Compute descriptive statistics (mean, median, mode, std).
- Rank sales performance by state and demographic group.
- Generate weekly, monthly, and quarterly sales reports.

### 3. **Data Visualization**
- Bar plots and boxplots for state-wise and group-wise comparisons.
- Time-of-day sales frequency analysis.
- Dashboard-quality visualizations using Seaborn.

### 4. **Report Generation**
- Export analysis reports as CSV and TXT.
- Save charts in a dedicated `/outputs/charts/` directory.
- Maintain code, plots, and insights in a single Jupyter Notebook.

---

## 📂 Directory Structure

```
SalesAnalysisAAL/
├── data/
│   └── AusApparalSales4thQrt2020.csv
├── notebooks/
│   └── AAL_Sales_Analysis.ipynb
├── outputs/
│   ├── charts/
│   │   ├── state_demographic_sales.png
│   │   ├── group_sales_boxplot.png
│   │   └── sales_by_hour.png
│   └── reports/
│       ├── descriptive_stats.csv
│       ├── group_sales.csv
│       ├── state_sales.csv
│       ├── rankings.txt
│       ├── stat_summary.txt
│       ├── weekly_sales.csv
│       ├── monthly_sales.csv
│       └── quarterly_sales.csv
├── README.md
└── requirements.txt
```
---

## 📊 Sample Visualizations
### State-wise Sales by Group
### Sales Distribution by Group
### Sales by Hour of Day
---

## 🛠️ Setup Instructions

### Clone the repository:
```
git clone https://github.com/your-username/SalesAnalysisAAL.git
cd SalesAnalysisAAL
```

### Install dependencies:
```
pip install -r requirements.txt
```

### Open JupyterLab and run the notebook:
```
jupyter lab notebooks/AAL_Sales_Analysis.ipynb
```
---

## 📦 Requirements

### See requirements.txt for all dependencies, including:
```
pandas
numpy
seaborn
matplotlib
scipy
scikit-learn
jupyterlab
```
---

## 📌 Key Insights

### Top Performing States: Identified based on total revenue.

### Underperforming Regions: Recommended for new sales strategies.

### Peak Sales Hours: Crucial for personalized marketing efforts.

### Demographic Trends: Helps in targeted promotions for kids, women, men, and seniors.

---

## 📣 Recommendations

### Invest more in high-growth states.

### Launch sales campaigns for underperforming demographics.

### Utilize time-of-day insights for flash sales and offers.

### Leverage data normalization and aggregation for efficient reporting pipelines.

---

## Plots

### Group Sales Box Plot
![](/images/group_sales_boxplot.png)

### Sales by Hour
![](/images/sales_by_hour.png)

### State Demographic Sales
![](/images/state_demographic_sales.png)

---

## Screenshot

![](/images/jupyter_result.png)

---

**Note: .txt and .csv files are saved in /outputs/reports/ directory**