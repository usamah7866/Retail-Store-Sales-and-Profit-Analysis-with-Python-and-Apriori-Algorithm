# Retail Store Sales and Profit Analysis with Python and Apriori Algorithm

This repository contains a **comprehensive sales and profit analysis project** based on the **Superstore dataset** (10,000+ rows of retail sales data).  
The project leverages Python libraries for **data processing, visualization, and association rule mining**, enabling insights into customer behavior, sales performance, and profit trends.

The project is based on the report:  
*Store Sales and Profit Analysis and Improvement*  
by Usama Habib and Ghaith Jamjoum.

---

## 📌 Features
- **Sales & Profit Analysis**
  - Sales by month, category, and sub-category
  - Profit analysis across multiple dimensions
  - Segment-wise sales and profit distribution  

- **Customer Behavior Analysis**
  - Association Rule Mining using the **Apriori algorithm** (via `mlxtend`)
  - Discover frequent item sets and product purchase patterns
  - Export association rules into CSV for further use  

- **Interactive Visualizations**
  - Monthly sales and profit trends
  - Category and sub-category breakdowns
  - Segment-level insights  

---

## ⚙️ Methodology
The workflow is structured as follows:  

1. **Data Input**  
   - Load *Sample-Superstore.csv* into a Pandas DataFrame.  
   - Clean and preprocess data (date formatting, new columns for month/year/day).  

2. **Exploratory Analysis**  
   - Sales by month, profit by month  
   - Sales & profit by category and sub-category  
   - Segment-level sales/profit comparison  

3. **Improvements**  
   - User filtering by product and country  
   - Ratio analysis: profit-to-sales ratios for specific filters  

4. **Association Rule Mining**  
   - Use **Apriori** to uncover frequent item sets  
   - Generate **association rules** to understand customer purchase behavior  
   - Save results into CSV for further recommendation system design  

---

## 🛠️ Tech Stack
- **Python 3.10+**
- Libraries:
  - `pandas` – Data processing  
  - `numpy` – Numerical operations  
  - `plotly` – Interactive visualizations  
  - `mlxtend` – Apriori algorithm and association rules  
