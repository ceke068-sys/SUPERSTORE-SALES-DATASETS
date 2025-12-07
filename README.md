# SUPERSTORE-SALES-DATASETS
Retail dataset of a global superstore for 4 years. Perform EDA and Predict the sales of the next 7 days from the last date of the Training dataset
![Image](https://github.com/user-attachments/assets/9953b8ec-cab6-4807-895e-f5918206b938)
# OBJECTIVES
# 📊 Retail Sales Analysis & 7-Day Sales Forecasting  
### Global Superstore Dataset (4 Years)

This project performs an end-to-end analysis of a retail dataset, including data cleaning, exploratory data analysis (EDA), trend interpretation, and forecasting future sales using regression techniques. All analysis and visualizations were created in **Excel**, making the project accessible for business-focused analytics.

## 📁 Dataset Overview

The dataset contains **9,800 transaction records** from a Global Superstore, with **18 columns** covering order details, customer information, product attributes, and sales amounts.
# BUSINESS QUESTION

1.       What are the Total sales for all customers
2.       How many customers made order in total?
3.       What are the total sales made from each city?
4.       Which city has the highest sales and which has the least sales?
5.       What are the total sales from each region?
6.       Which region has the highest sales and which has the least sales?
7.       How many sales order were made by each segment of customers?
8.       What are the total revenue from each segment
9.       Does the ship mode determine the volume of sales made

### **Feature Summary**

| Column | Description |
|--------|-------------|
| Row ID | Unique row identifier |
| Order ID | Unique order identifier |
| Order Date | Date the order was placed |
| Ship Date | Date the order was shipped |
| Ship Mode | Shipping method (Standard, First Class, etc.) |
| Customer ID | Unique customer identifier |
| Customer Name | Full customer name |
| Segment | Customer segment (Consumer, Corporate, Home Office) |
| Country | Country of order |
| City | Customer city |
| State | Customer state |
| Postal Code | Postal/ZIP code |
| Region | Market region |
| Product ID | Unique product code |
| Category | Product category |
| Sub-Category | Detailed product type |
| Product Name | Product description |
| Sales | Sales amount for the order line |

---

## 🧹 Data Cleaning Steps

1. Converted `Order Date` and `Ship Date` to proper date formats.
2. Checked and removed duplicate rows using `Row ID` and `Order ID`.
3. Standardized text fields (e.g., product names, customer names).
4. Removed rows with invalid or mixed data types (e.g., letters in date fields).
5. Created derived fields:
   - Daily Sales  
   - Month & Year of Order  
   - Delivery Time (Ship Date − Order Date)

---

## 🔍 Exploratory Data Analysis (EDA)

The EDA focused on identifying patterns in sales, customer behavior, and product performance.

### **Key Insights**
- **Sales Trend Over Time:**  
  Sales show a positive trend with periodic fluctuations—typically higher during Q4 and lower mid-year.

- **Top Performing Categories:**  
  - **Technology** generates the highest revenue.  
  - **Office Supplies** has the highest order volume.  
  - **Furniture** shows lower profit margins in several sub-categories.

- **Customer Segments:**  
  - **Consumer segment** contributes the largest portion of total sales.  
  - **Corporate** shows steady growth, especially in Office Supplies.

- **Shipping Performance:**  
  - **Standard Class** is the most used mode.  
  - Faster shipping modes (First Class, Same Day) have smaller but profitable usage.

- **Regional Distribution:**  
  - Strongest sales come from **West** and **East** regions.  
  - Opportunities exist for targeted promotions in lower-volume regions.

All visualizations—including trend lines, pivot charts, and category comparisons—were developed in **Excel**.

---

## 📈 Regression Analysis & Forecasting

The forecasting task predicts **sales for the next 7 days** after the last date in the dataset.

### **Model Approach**
- Used **parametric regression assumptions** based on:  
  - daily aggregated sales  
  - linear trend analysis  
  - moving averages and smoothing  
- Created **forecast formulas in Excel**  
- Included **prediction intervals** to capture uncertainty around the forecast.

### **Deliverables**
- 7-day sales forecast table  
- Upper and lower prediction bounds  
- Sales trend visualization  
- Interpretation of forecast trajectory

## 🛠 Tools Used

- **Excel** (Data cleaning, EDA, regression, forecasting)
- **Pivot Tables** (For data Summarization)
- **Charts*** (For Pattern discovery and Visualization)
- **Regression Analysis*** ( Testing predictor effect on purchase frequency )
- **GitHub** (Project documentation & versioning)

## 🧠 Interpretation & Business Insights
This section describes what the results imply from a business decision-making perspective.

### **1. Sales Trend Interpretation**
Sales show an upward trajectory over the years, indicating consistent business growth. Seasonal spikes suggest strong performance during the last quarter (likely holiday periods).

**Implication:**  
Inventory planning should prioritize Q4 stock increases.
### **2. Product Performance Interpretation**
- **Technology** is the highest revenue generator — these items should be prioritized in marketing campaigns.
- **Furniture** often shows lower profit despite reasonable sales volume — likely due to high shipping costs or discounts.

**Implication:**  
Repricing or reducing shipping cost on large furniture items could improve profitability.

---

### **3. Customer Segment Interpretation**
- **Consumers** remain the strongest buying group.
- **Corporate** customers show stable repeat purchases.

**Implication:**  
Potential exists for loyalty programs targeted at Consumer and Corporate segments.

---

### **4. Shipping Mode Interpretation**
Standard Class dominates, but faster shipping options contribute meaningfully to customer satisfaction.

**Implication:**  
Introduce shipping incentives—e.g., free First Class shipping for orders above a threshold.

---

### **5. Forecast Interpretation**
The 7-day forecast shows a continuation of the recent sales trend.  
Prediction intervals indicate possible fluctuations, but overall demand should remain stable in the short term.

**Implication:**  
Short-term planning for staffing and inventory should follow the estimated sales levels. No sudden demand spike is expected.

Overall Interpretation

Your project shows that the business is growing steadily, with strong seasonal patterns and reliable customer segments. Technology drives the highest revenue, while Furniture requires strategic improvement due to lower margins.
The forecast validates short-term stability, helping the business plan for inventory, staffing, and marketing.

I"m open to collaboration or feedback. Always feel free to connect with me via
ceke068@gmail.com, https://www.linkedin.com/in/chris-eke-947029226/


                  |				
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
															
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
