# CodeAlpha Task 2: Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project focuses on Exploratory Data Analysis (EDA) of a retail sales dataset. The objective is to understand the data, identify patterns and trends, detect data quality issues, and generate meaningful business insights using Python.

## 🎯 Objectives
- Understand the dataset structure and data types.
- Identify missing values and duplicate records.
- Analyze sales and profit across product categories and regions.
- Explore monthly sales trends.
- Identify top-performing products.
- Analyze correlations between numerical variables.
- Detect potential outliers using the Interquartile Range (IQR) method.
- Generate data-driven business insights.

## 🛠️ Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- GitHub

## 📂 Project Structure
```text
CodeAlpha-Task2-EDA/
│
├── CodeAlpha_Task2_EDA.ipynb
├── EDA_Report.md
├── README.md
└── images/
    ├── correlation_heatmap.png
    ├── sales_profit_category.png
    ├── monthly_sales_trend.png
    └── top_10_products.png
```

*Note: Include only the files and images that you have actually created.*

## 📊 Analysis Performed

### 1. Data Understanding
- Inspected the first few records.
- Reviewed column names, data types, and dataset dimensions.
- Generated descriptive statistics.

### 2. Data Quality Assessment
- Checked missing values.
- Identified duplicate rows.
- Reviewed numerical and categorical variables.

### 3. Sales and Profit Analysis
- Compared sales and profit across product categories.
- Analyzed regional performance.
- Examined monthly sales trends where date information was available.
- Identified the top 10 products by total sales.

### 4. Correlation Analysis
Created a correlation heatmap to understand relationships between numerical variables.

### 5. Outlier Detection
Used the Interquartile Range (IQR) method to identify potentially unusual Sales and Profit values. Outliers were reviewed rather than automatically removed.

## 💡 Key Business Insights
The following insights should be completed using the actual results from the analysis:

1. **Category Performance:** Identify the category with the highest total sales.
2. **Profitability:** Identify the category with the highest total profit.
3. **Regional Performance:** Determine which region generates the highest total profit.
4. **Sales Trends:** Identify months or periods with comparatively high or low sales.
5. **Product Performance:** Identify the top-performing products based on total sales.
6. **Data Quality:** Summarize the missing values, duplicate records, and potential outliers found.

## 📈 Results
This project demonstrates how Python can be used to explore retail data, identify trends, evaluate data quality, and support business decision-making through statistical analysis and visualization.

## ▶️ How to Run the Project
1. Download or clone this repository.
2. Open `CodeAlpha_Task2_EDA.ipynb` in Google Colab or Jupyter Notebook.
3. Upload the required retail sales CSV dataset
