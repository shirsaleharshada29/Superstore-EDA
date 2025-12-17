# 📊 Exploratory Data Analysis (EDA) on Superstore Sales Data

## 📌 Project Overview
This project performs a complete **Exploratory Data Analysis (EDA)** on the **Sample Superstore dataset** to understand sales performance, profit patterns, discounts, and customer behavior before applying any formal statistical or predictive modeling techniques.

EDA helps in identifying key variables, relationships, missing values, outliers, and overall data structure, which is essential for reliable data-driven decision-making.

---

## 🎯 Objective
- To understand the structure and characteristics of the Superstore sales data  
- To analyze relationships between **Sales, Profit, Discount, and Quantity**  
- To identify missing values and outliers  
- To extract meaningful business insights using visualization techniques  

---

## 📂 Dataset Information
- **Dataset Name:** Sample - Superstore.xlsx  
- **Source:** Sample Superstore Dataset  
- **Size:** 9,994 rows × 21 columns  

### 🔑 Key Variables
- **Sales:** Revenue generated per order (USD)
- **Profit:** Net profit after discounts (USD)
- **Quantity:** Number of units sold
- **Discount:** Discount applied to orders
- **Category & Sub-Category:** Product classification
- **Segment:** Customer segment
- **Region, State, City:** Geographic details
- **Order Date & Ship Date:** Transaction timeline

### 🧾 Data Types
- **Numerical:** Sales, Profit, Quantity, Discount, Postal Code  
- **Categorical:** Category, Sub-Category, Segment, Region, State, City, Ship Mode  
- **Datetime:** Order Date, Ship Date  
- **ID Columns:** Row ID, Order ID (not used for modeling)

---

## 🔍 Missing Data Analysis
- Only **Postal Code** column contains missing values  
- **11 missing values (~11.01%)**
- Discussed common handling techniques:
  - Mean
  - Median
  - Mode
  - Dropping values (if required)

---

## 📊 Exploratory Data Analysis & Visualizations

### ✔ Bar Chart
- Used to analyze record distribution across **States**
- **California** has the highest number of records
- **North Carolina** ranks tenth

### ✔ Scatter Plots
- **Sales vs Profit:** Positive relationship  
- **Discount vs Profit:** Negative relationship (higher discount → lower profit)

### ✔ Histograms
- Distribution of **Sales, Profit, Quantity, Discount**
- Most orders have low sales and profit
- High values occur rarely

### ✔ Heatmap (Correlation Analysis)
- Strong positive correlation between **Sales and Profit**
- Discount shows weak or negative correlation with other numeric variables

### ✔ Boxplots
- Used to identify outliers
- **Sales** contains the highest number of outliers
- Profit and Discount have fewer extreme values

---

## 📈 Key Findings
- **Total Sales:** 2,295,526.00 USD  
- **Total Profit:** 286,389.12 USD  
- **Total Quantity Sold:** 37,837 units  
- Sales and Profit increase together
- Higher discounts generally reduce profit
- Office Supplies category has the highest order count
- West region contributes the most orders

---

## 🧠 Conclusion
- EDA revealed important relationships between key business variables
- Sales and Profit are strongly linked
- Discounts negatively impact profitability
- Outliers are mainly present in Sales
- Visualization techniques greatly improve data understanding

EDA provides a strong foundation for further statistical analysis and predictive modeling.

---

## 🚀 Next Steps
- Handle outliers using appropriate statistical techniques
- Perform feature engineering
- Apply predictive models (Sales/Profit forecasting)
- Conduct advanced analysis (regression or classification)

---

## 🛠 Tools & Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 👤 Author
**Harshada Shirsale**  
Date: December 13, 2025
