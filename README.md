# SUPERSTORE-SALES-DATASETS
Retail dataset of a global superstore for 4 years. Perform EDA and Predict the sales of the next 7 days from the last date of the Training dataset
![Image](https://github.com/user-attachments/assets/9953b8ec-cab6-4807-895e-f5918206b938)
# OBJECTIVES
Perform an Exploratory Data Analysis (EDA) and a Regression-based Sales Forecast for the next 7 days, using Excel formulas, Pivot Tables, and Charts.
# BUSINESS QUESTION

# 1.       What are the total sales for all customers?
2.       How many customers made order in total?
3.       What are the total sales made from each city?
4.       Which city has the highest sales and which has the least sales?
5.       What are the total sales from each region?
6.       Which region has the highest sales and which has the least sales?
7.       How many sales order were made by each segment of customers?
8.       What are the total revenue from each segment
9.       Does the ship mode determine the volume of sales made
| Column         | Description                                               |
| -------------- | --------------------------------------------------------- |
| **Order Date** | Date when the order was placed                            |
| **Ship Date**  | Date when the product was shipped                         |
| **Segment**    | Customer segment (Consumer, Corporate, Home Office)       |
| **Country**    | Country or region                                         |
| **Category**   | Product category (Furniture, Office Supplies, Technology) |
| **Sales**      | Sales amount for the transaction                          |
| **Quantity**   | Units sold                                                |
| **Discount**   | Discount applied                                          |
| **Profit**     | Profit realized                                           |
| Column                      | Formula                         | Meaning               |
| --------------------------- | ------------------------------- | --------------------- |
| **A:** Date                 | —                               | Daily order date      |
| **B:** Sales                | —                               | Sum of daily sales    |
| **C:** Previous Day (Lag 1) | `=OFFSET(B2,-1,0)`              | Yesterday’s sales     |
| **D:** 7-Day Moving Avg     | `=AVERAGE(OFFSET(B2,-7,0,7,1))` | Rolling mean          |
| **E:** Day of Week          | `=WEEKDAY(A2,2)`                | Monday=1 ... Sunday=7 |
| **F:** Month                | `=MONTH(A2)`                    | Extract month number  |

| File                                 | Description                                |
| ------------------------------------ | ------------------------------------------ |
| `Superstore_4yrs.xlsx`               | Cleaned dataset                            |
| `EDA_Dashboard.xlsx`                 | Pivot tables, charts, and summaries        |
| `Sales_Forecast.xlsx`                | Regression output and 7-day forecast table |
| `README_Excel_Sales_Regression.docx` | Documentation (this file)                  |

	Forecast = Intercept 
           + (Lag1 * Coeff_Lag1)
           + (7DayAvg * Coeff_7DayAvg)
           + (DayOfWeek * Coeff_DayOfWeek)
           + (Month * Coeff_Month)
							
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
															
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
								
