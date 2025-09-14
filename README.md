📊 Sales Data Analysis (Excel Project)
📌 Project Overview

This project focuses on analyzing a sales dataset using Excel. The goal was to clean the data, perform descriptive statistical analysis, identify outliers, and answer key business questions using Pivot Tables and Charts.

🛠 Steps Performed
1️⃣ Data Cleaning

Removed extra spaces using TRIM().

Rounded product prices using the ROUND() function.

Structured raw sales data into tabular format for easy analysis.

2️⃣ Descriptive Statistics

Calculated summary metrics for Price and Quantity using Excel’s Data Analysis ToolPak:

Mean, Median, Mode

Standard Deviation & Variance

Skewness & Kurtosis

Range, Min, Max

Sum & Count

🔎 Insight: The price distribution is right-skewed (Skewness = 1.62), meaning most products are low-priced, but a few are very high-priced.

3️⃣ Outlier Detection

Used Box & Whisker plots per manager.

Found outliers in pricing/sales that may require further investigation.

4️⃣ Pivot Table Analysis

Best Selling Product → Identified the top revenue-generating product.

Total Revenue → Summed all transactions (≈ 1886.64).

Revenue Breakdown by Payment Method → Grouped sales by payment type (cash, card, UPI, etc.).

📊 Key Business Questions Answered

What is our best-selling product?
→ Found using Pivot Table (Product vs Total Revenue).

What is our total revenue?
→ 1886.64 (based on Price × Quantity).

What is the revenue breakdown by payment method?
→ Created a pivot with payment methods to see contribution %.

📈 Visualizations

Box & Whisker plot → To detect outliers.

Pivot table → For best-selling products.

🛠 Tools Used

Microsoft Excel

TRIM & ROUND functions

Descriptive Statistics (Analysis ToolPak)

Pivot Tables & Charts

(Optional) Power BI for extended visualization

🚀 Future Improvements

Automate data cleaning with Python (Pandas).

Connect data directly to Power BI for real-time dashboards.

Add advanced ETL steps for large datasets.
