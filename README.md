# AdventureWorks Sales Analysis - Power BI Project

##  Project Overview
The **AdventureWorks Sales Analysis** Power BI project provides a **comprehensive analysis** of sales performance, customer behavior, product trends, and regional insights. This dashboard helps businesses track revenue growth, profit margins, and customer retention while identifying key areas for improvement.

## Dataset Information
The dataset consists of multiple CSV files related to **sales transactions, customers, products, territories, and returns** from **2020 to 2022**. These files were merged and cleaned to create a structured data model in Power BI.

###  Dataset Files Used:
1. **AdventureWorks Sales Data 2020.csv**
2. **AdventureWorks Sales Data 2021.csv**
3. **AdventureWorks Sales Data 2022.csv**
4. **AdventureWorks Customer Lookup.csv**
5. **AdventureWorks Product Lookup.csv**
6. **AdventureWorks Product Categories Lookup.csv**
7. **AdventureWorks Product Subcategories Lookup.csv**
8. **AdventureWorks Territory Lookup.csv**
9. **AdventureWorks Returns Data.csv**
10. **AdventureWorks Calendar Lookup.csv**

##  Insights & Analysis
The Power BI dashboard provides the following key insights:

### **1 Sales Performance Analysis**
- **Total Revenue** by Year , week,months
- **Top & bottom products by sales**
- **Profit Margins & Growth Rate**

### **2 Customer Insights**
- **Total Customers**
- **Average Revenue per Customer**
- **Top Spending Customers and customers by education level,gender and occupation**

### **3 Product Performance**
- **Best-Selling Products & Categories**
- **Total products**
- **Return Rate & Impact on Sales**

### **4 Returns insights **
- **Sales by Region & Country**
- **Returns by continent, region and country**
- **Total returns and total loss from returns**

### ** 5 Regional  Sales analysis **
- **Best Sales by Region & Country**
- **Top Performing Territories**
- **Sales Rep Performance & Commissions Earned**

##  Data Cleaning & Processing Steps
✔ **Merged** sales data from 2020-2022 into a single table.
✔ **Removed duplicates** and handled missing values.
✔ **Standardized date format** for better time-based analysis.
✔ **Created relationships** between datasets (Sales, Customers, Products, etc.).
✔ **Added calculated columns** (e.g., Profit, Order Year, Return Flag).
✔ **Applied DAX measures** for advanced insights.

##  Key DAX Measures Used
- **Total Sales** = `SUM(Sales[Sales Amount])`
- **Profit Margin (%)** = `DIVIDE(SUM(Sales[Profit]), SUM(Sales[Sales Amount]), 0)`
- **Repeat Customer %** = `DIVIDE(Repeat Customers, Total Customers, 0) * 100`
- **Total Returns** = `COUNT(Returns[Return ID])`
- **Return Rate (%)** = `DIVIDE(COUNT(Returns[Return ID]), COUNT(Sales[Order ID]), 0) * 100`


##  How to Use the Dashboard
1. **Open the Power BI file** (`adventureWork_sales_project.pbix`).
2. **Explore the different report pages** using the tabs at the bottom.
3. **Hover over charts** to see detailed tooltips & insights.
4. **Apply filters** (e.g., Year, Region, Product Category) to drill down data.

##  Future Enhancements
✅ Adding **Forecasting Models** for sales prediction. 

✅ Creating **Interactive Drill-Throughs** for deep analysis. 

✅ Implementing **Custom Alerts** for sales & return trends.


1. Revenue Growth Trends
   
Factors affecting revenue growth:

✅ Market Demand – Changes in customer demand for products.

✅ Seasonality – Sales fluctuations based on different months/quarters.

✅ Economic Conditions – Inflation, recession, or economic growth affecting purchasing power.

✅ Promotions & Discounts – Impact of marketing campaigns on revenue.

✅ Competition – Presence of competitors offering similar products at better prices.

✅ Supply Chain & Inventory – Availability of stock affecting the ability to meet demand.


2. Top-Performing Products

   
Factors affecting product sales performance:

✅ Product Quality & Features – Customer preference for high-quality products.

✅ Pricing Strategy – Competitive pricing vs. premium pricing.

✅ Marketing & Branding – Brand awareness and advertising impact.

✅ Customer Reviews & Ratings – Social proof influencing buying decisions.

✅ Availability & Delivery Time – Stock shortages and delivery delays affecting sales.

3. Customer Behavior & Loyalty

   
Factors affecting customer retention & repeat purchases:

✅ Product Satisfaction – Good experience increases repeat purchases.

✅ Customer Service Quality – Quick response & issue resolution.

✅ Loyalty Programs – Discounts, offers, and exclusive deals for repeat customers.

✅ Market Trends – Changing customer preferences over time.



4. Product Return Trends

   
Factors affecting product returns:

✅ Product Defects & Quality Issues – Poor-quality products lead to high return rates.

✅ Mismatched Customer Expectations – Incorrect product descriptions or misleading marketing.

✅ Return Policy – Flexible return policies can increase returns.

✅ Delivery Issues – Late or damaged shipments leading to customer dissatisfaction.

✅ Customer Preferences – Changing mind or buying a competitor's product instead.


5. Regional Sales Performance

   
Factors influencing sales across different regions:

✅ Population Density & Demand – Higher demand in urban vs. rural areas.

✅ Economic Factors – Average income levels and spending power in each region.

✅ Regional Preferences – Cultural and lifestyle preferences for certain products.

✅ Local Competition – Presence of local competitors affecting sales.

✅ Logistics & Distribution – Efficiency of supply chain and warehouse locations.






##  Conclusion
This Power BI dashboard **provides a 360° view** of sales performance, customer behavior, and product trends. It enables **data-driven decision-making** for business growth.




