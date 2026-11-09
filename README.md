### ShopSim-Ecommerce-Analysis
An e-commerce data analysis project using Excel, Power Query and Power BI to explore sales, product performance, customer behaviour, profitability and order fulfilment through interactive dashboards.

### Dashboard Preview
#### Sales and Product Performance
![Sales and Product Performance](Images/ShopSim_Sales_and_Product_Performance.png)

#### Customer and Operational Performance
![Customer and Operational Performance](Images/ShopSim_Customer_and_Operation_Performance.png)

### Project Overview
ShopSim E-commerce Analysis is a data analytics project based on a simulated e-commerce business. The project examines the business's performance over a 12-month period, from January to December 2025. The analysis goes beyond sales figures to explore product performance, customer behaviour, profitability, geographical sales distribution and order fulfilment. Microsoft Excel, Power Query and Power BI were used to prepare, analyse and present the data through an interactive dashboard.

### Project Objectives
The main objectives of this project were to:
- Examine and prepare the e-commerce dataset for analysis.
- Evaluate overall business performance using key performance indicators (KPIs).
- Analyse monthly revenue trends.
- Identify high-performing products and product categories.
- Examine estimated gross profit and profit margins.
- Understand customer purchasing patterns and revenue contributions.
- Analyse revenue distribution across Nigerian states.
- Examine order statuses, cancellations and fulfilment performance.
- Present the findings through an interactive Power BI dashboard.

### Business Questions
The analysis was designed to answer questions such as:
- How much revenue did the business generate?
- How did revenue change from month to month?
- Which product categories generated the highest revenue?
- Which individual products performed best?
- How profitable were the products?
- Which customers contributed the most revenue?
- How was revenue distributed across Nigerian states?
- What percentage of orders were successfully delivered?
- How many orders were cancelled or returned?

### Dataset Description
The project used a simulated e-commerce dataset covering January to December 2025. The dataset contained four main tables:
1. Customers: Contains customer information, including demographic and location details.
2. Products: Contains product information and pricing details.
3. Orders: Contains order dates, payment methods and order statuses.
4. OrderDetails: Contains individual products purchased, quantities, selling prices and discounts.

#### A separate Calendar table was also created to support monthly and time-based analysis.
#### Note: The dataset was created for learning and portfolio demonstration. It does not represent the actual records of a registered business.

### Tools Used
- Microsoft Excel: Initial data inspection and preparation.
- Power Query: Data cleaning and transformation.
- Power BI Desktop: Data modelling, analysis and dashboard development.
- DAX: Creating calculations and key performance indicators.

### Data Cleaning and Preparation
The four datasets were examined to identify missing information, duplicate records, inconsistent entries and formatting problems. The cleaning process included:
- Removing duplicate records.
- Standardising text entries and categories.
- Correcting date and numeric formats.
- Identifying missing and invalid values.
- Checking customer and product references.
- Preparing the tables for analysis.
A total of 30 data quality issues were identified. Nineteen were corrected, while 11 were documented because the required information was unavailable. Missing information was not replaced with guessed values.
#### The data quality issues and actions taken to remedy them are presented in the data Quality log sheet in the "Data" folder.

### Data Modelling
The datasets were connected in Power BI using their identification fields.
The main relationships included:
* Customers connected to Orders through CustomerID.
* Orders connected to OrderDetails through OrderID.
* Products connected to OrderDetails through ProductID.
* Calendar connected to Orders through OrderDate.
This structure allowed information from the different tables to work together during analysis.

### Dashboard Overview
The Power BI report contains two interactive pages.
Page 1: Sales and Product Performance
This page focuses on the financial and product performance of the business.
It includes:
- Total revenue.
- Total quantity sold.
- Average order value.
- Estimated gross profit.
- Estimated gross profit margin.
- Monthly revenue trends.
- Revenue by product category.
- Individual product performance.
Users can explore the results using filters for month, product category and payment method.

Page 2: Customer and Operational Performance
This page focuses on customer contributions and order management.
It includes:
- Active customers.
- Total orders.
- Cancelled order rate.
- Order fulfilment rate.
- Average revenue per customer.
- Revenue by Nigerian state.
- Revenue by customer gender.
- Top 10 customers by revenue.
- Order status distribution.
Users can explore the results using filters for month, gender, order status and payment method.

### Key Insights and Findings
Some of the major findings from the analysis include:
- The business generated total revenue of approximately ₦273.84 million.
- A total of 4,363 units were sold.
- Estimated gross profit was ₦59.29 million, with a gross profit margin of 21.65%.
- Fashion generated the highest revenue among the five product categories, recording approximately ₦63.48 million.
- December recorded the highest monthly revenue of approximately ₦30.35 million.
- Female customers contributed 51.31% of total revenue, while male customers contributed 48.69%.
- Kano recorded the highest revenue among the identified Nigerian states.
- Out of 1,000 orders, 70.40% were delivered, while 6.90% were cancelled and 3% were returned.

### Project Limitations
The analysis was based on simulated data and therefore does not represent the actual performance of a real business. In addition, some records contained missing or invalid information that could not be reliably recovered. Estimated gross profit did not include shipping expenses or other operating costs and should not be interpreted as net profit.

### Recommendations
Based on the findings from the analysis, the following actions are recommended to improve the business's sales performance, profitability, customer relationships and order management.

1. Review Product Pricing and Profit Margins: 
 The business should regularly review the selling prices and costs of products with low profit margins. For example, Wall Clock 37 and Wireless Earbuds 43 recorded gross profit margins of only 5.26% and 5.68%, respectively. Management could review their purchase costs, negotiate better prices with suppliers or make reasonable adjustments to their selling prices. Products such as Desk Lamp 18 and Steam Iron 05, which recorded margins of 37.87%, could also be considered when planning future product purchases and promotional activities.

2. Improve Inventory Management:
 Inventory decisions should be based on both product demand and profitability rather than sales revenue alone. Products with consistently high sales quantities and good profit margins should receive priority when planning restocking. For instance, products such as T-shirt 47, which recorded the highest quantity sold among the ten leading products, could be monitored closely to avoid running out of stock. Products with lower sales or profit margins should be reviewed before additional stock is purchased.

3. Strengthen Customer Retention and Engagement:
 Since female and male customers contributed 51.31% and 48.69% of revenue respectively, marketing activities should continue to target both groups. The business could introduce loyalty rewards, personalised product offers and discounts for repeat purchases. It should also pay attention to its highest revenue-generating customers by tracking their purchase history and providing targeted offers that encourage them to continue shopping with the business.

4. Focus on Geographical Sales Opportunities:
 The business should use its geographical sales results to guide marketing and delivery decisions. Kano and Edo recorded the highest revenue contributions, making them important markets to maintain and develop. Management could strengthen delivery arrangements and promotional activities in these states while investigating why locations such as Rivers State and the Federal Capital Territory recorded lower revenue. Targeted promotions and improved delivery options could help attract more customers in these areas.

5. Improve Order Processing and Delivery:
 With an order fulfilment rate of 70.40%, a cancellation rate of 6.90% and a return rate of 3%, the business should pay closer attention to orders that are not successfully completed. Management could introduce regular monitoring of orders that remain in processing or shipping for extended periods. Customers should also receive timely updates about their orders. In addition, the reasons for cancellations and returns should be recorded and reviewed to identify recurring problems, such as delivery delays or incorrect product information.

6. Improve Customer and Transaction Records:
 The business should introduce proper checks when recording customer and order information to reduce missing or invalid entries. For example, customer IDs, order dates and delivery locations should be required fields when recording new transactions. Dropdown lists can also be used for fields such as payment methods, order statuses and states to reduce inconsistent entries. These measures would improve the quality of future reports and make business performance easier to monitor.

### Project Files
The repository contains the files used in the project, including the dataset, Power BI report, dashboard screenshots and supporting documentation.

### How to View the Project
To explore the dashboard:
1. Download the Power BI report from the reports folder
2. Open it using Microsoft Power BI Desktop.
3. Navigate between the two report pages.
4. Use the available filters to explore different aspects of the business.


