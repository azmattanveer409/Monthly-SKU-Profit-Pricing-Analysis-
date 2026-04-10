# 📊 SKU Profit & Pricing Analytics Dashboard (Excel | Python | Power BI)

---

## 🚀 Project Overview

This project performs **SKU-level pricing and profitability analysis** on an e-commerce dataset to optimize pricing strategy, improve margin efficiency, and identify high-performing products.

The workflow combines **Excel for data cleaning**, **Python for feature engineering & visualization**, and **Power BI for interactive dashboarding** to deliver end-to-end business insights.

---

## 🎯 Objective

* Clean and standardize multi-platform pricing data
* Analyze SKU-level profitability patterns
* Identify high and low performing categories & products
* Detect pricing inconsistencies across platforms
* Build interactive dashboards for business decision-making
* Generate actionable pricing and product strategy insights

---

## 📂 Dataset Information

Key columns used in analysis:

* SKU, Style ID, Catalog, Category
* TP (Total Price / Cost Price)
* MRP Old, Final MRP Old
* Amazon, Flipkart, Myntra, Ajio, Snapdeal prices
* Profit, Profit Percentage
* Price Consistency
* Price Band (Low / Medium / High)

---

## ⚙️ Tools & Technologies

* **Excel** → Data cleaning & preprocessing
* **Python (Pandas, NumPy)** → Feature engineering & analysis
* **Matplotlib & Seaborn** → Visualization
* **Power BI** → Interactive dashboard & KPIs

---

## 🧠 Data Processing Workflow

* Handled missing and inconsistent values (`#`, `nil`, blanks)
* Converted price columns into numeric format
* Forward-filled platform pricing gaps
* Imputed TP values using SKU-wise mean
* Engineered features:

  * Profit = MRP Old - TP
  * Profit Percentage
  * Price Consistency Flag
  * Price Band (Low / Medium / High)

---

## 📊 Exploratory Data Analysis (EDA)

* SKU distribution across categories
* Profitability comparison by category
* Price consistency across platforms
* Profit vs MRP relationship
* Top-performing SKUs identification

---

## 📈 Visual Analysis (Python)

* 📊 Average Profit by Category
* 📦 SKU Distribution by Price Band
* 📉 Profit vs MRP Scatter Plot
* 🔥 Top 10 Most Profitable SKUs

---

## 🖥️ Power BI Dashboard

### 📌 Dashboard Title:

**SKU Profit & Pricing Intelligence Dashboard**

### 📊 KPIs:

* Total SKUs: 1,330
* Total Profit: ~2M
* Average Profit %: ~74%
* Total Categories: 9

### 🎛️ Slicers:

* Category
* Price Band (Low / Medium / High)
* Price Consistency

### 📊 Visuals:

* Profit by Category (Bar Chart)
* Profit vs Weight (Scatter Plot)
* SKU Distribution by Price Band (Donut Chart)
* Profit Contribution by SKU (Bar Chart)
* Profit Trend Analysis (Line Chart)

---

## 📊 Key Insights

---

1. **Category Profitability** → Gowns generate the highest margins, while Tops show weaker profitability.
2. **Price Band Concentration** → Over 90% of SKUs fall in the Medium price band, indicating strong mid-market focus.
3. **Profit vs MRP Relationship** → Strong positive correlation; higher MRP directly drives higher profit.
4. **Top Performing SKUs** → A few SKUs (e.g., OS1109, OS1056 series) dominate total profitability.
5. **SKU Concentration Risk** → Profit is concentrated in a small subset of SKUs despite large catalog size.
6. **Data Quality Issues** → Inconsistent category labels and missing values reduce analytical accuracy.

---

## 💡 Recommendations

---

1. Scale **high-performing categories (Gowns)** and replicate successful SKUs.
2. Optimize pricing strategy within the **Medium price band** (largest segment).
3. Introduce premium positioning for high-margin SKUs.
4. Clean and standardize category & pricing data for better decision-making.
5. Reduce low-performing SKUs to improve catalog efficiency.
6. Implement pricing dashboards with real-time margin tracking.
7. Monitor cross-platform pricing inconsistencies to improve competitiveness.

---

## 📁 Project Structure

```
├── data/
│   └── May-2022.csv
├── notebooks/
│   └── sku_analysis.ipynb
├── outputs/
│   ├── charts/
│   └── cleaned_data.xlsx
├── powerbi/
│   └── dashboard.pbix
├── README.md
```

---

## 📊 Expected Outcome

* Improved pricing strategy across SKUs
* Identification of high-margin product segments
* Better inventory and catalog optimization
* Data-driven pricing decisions across platforms
* Interactive dashboard for business stakeholders

---

## 🚀 Future Improvements

* Add machine learning model for **profit prediction per SKU**
* Automate pricing anomaly detection
* Deploy Power BI dashboard online (Power BI Service)
* Integrate real-time sales data
* Build Streamlit pricing optimization app

---

## 📊 Final Insights Summary

This project demonstrates a complete **data analytics pipeline from raw SKU pricing data to business intelligence dashboards**, enabling actionable insights for pricing optimization, product strategy, and profitability enhancement.
