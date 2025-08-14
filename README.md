# **TAILWIND TRADERS SALES DATA ANALYSIS**

## OBJECTIVE

The objective of this project is to analyze the Tailwind Traders dataset using Power BI, perform data transformation and modeling, and create Sales and Profit reports for business insights. The analysis also integrates multi-currency exchange rates using Python script.
________________________________________
## DATA SOURCES
**•	Sales Data** – Contains sales transactions including gross product price, tax per product, quantity purchased, loyalty points etc.

**•	Purchase Data** – Contains purchase transactions.

**•	Countries Data** – Contains country names, country id & exchange id.

**•	Exchange Data** – Integrated using a Python script to convert sales in local currencies to USD.
________________________________________
## Power BI

**Step 1: Data Loading & Transformation**

1.	Open Tailwind Traders Sales Excel file:  Calculate Gross Revenue, Total Tax & Net Revenue from the sales data and add these as separate columns.
   
2.	Open Power BI and import this data.
	
3.	Transform the data: Change column data types to appropriate types.
  
4.	Import Purchase Data and apply similar transformations.
  
5.	Import Countries Data.
  
6.	Use Python Script to create an Exchange Data table for converting sales into USD.
   
________________________________________

**Step 2: Data Modeling**

1.	Create the following tables:
   
    o	Calendar Table – For time intelligence calculations.

    o	Sales in USD Table – Integrates exchange rates with sales.

2.	Establish relationships between tables:
   
    o	Sales ↔ Sales in USD Table

    o	Sales ↔ Countries Table
  
    o	Countries ↔ Exchange Data Table

    o	Purchases ↔ Calendar Table

    o	Sales ↔ Purchase Table

3.	Verify the model using diagram view and ensure relationships are correct.
________________________________________

**Step 3: Calculated Measures**

  •	Yearly Profit Margin

  •	Quarterly Profit

  •	Year-to-Date (YTD) Profit

  •	Median Sales
________________________________________

**Step 4: Prepare Sales Report**

1.	Bar Chart – Loyalty Points by Country
   
2.	Column Chart – Quantity Sold by Product
  
3.	Pie Chart – Median Sales Distribution by Country
	
4.	Line Chart – Median Sales Over Time
  
5.	Cards – Visualize key measures:
	
    o	Stock

    o	Quantity Purchased

    o	Median Sales

6.	Slicer – Country Name from Sales in USD table
________________________________________

**Step 5: Profit Report**

1.	Bar Chart – Net Revenue by Product
   
2.	Donut Chart – Yearly Profit Margin by Country
   
3.	Area Chart – Yearly Profit Margin Over Time
   
4.	Cards – Visualize key measures:
   
    o	YTD Profit

    o	Net Revenue USD

5.	KPI – Gross Revenue USD
   
6.	Slicer – Date from Calendar Table
________________________________________

## CONCLUSION

This project demonstrates end-to-end data analysis in Power BI for Trailwind Traders:

•	Importing and transforming multiple data sources

•	Data modeling with relationships and calculated measures

•	Python integration for currency conversion

•	Visualizing actionable insights through sales and profit reports

The dashboards provide insights into sales performance, profit margins, and country-level contributions, helping stakeholders make data-driven decisions.

