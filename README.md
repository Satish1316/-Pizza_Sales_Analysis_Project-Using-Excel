
### Pizza Sales Analysis


### 1. Overview
This project focuses on analyzing the pizza sales data to help a fictional pizza company improve its sales strategy. The analysis includes revenue performance, customer preferences, and operational insights based on the sales data of various pizza types, sizes, and order times. 

The goal of the project is to provide key insights and recommendations that the company can use to enhance its sales, optimize menu offerings, and better target its customer base.

### 2. Project Goals
- Develop essential metrics based on the provided dataset.
- Construct a dashboard following the stakeholder requirements.
- Generate actionable insights that go beyond the predefined metric list and dashboard mockup.

### 3. Import & Explore Data

#### Using SQL to Explore Data
Exploring the data before diving into analysis is key to understanding customer behavior, pizza preferences, and sales patterns.

#### Dataset Overview:
- `dim_pizzas`: This table contains information about the pizza types, their sizes, and base prices.
- `dim_orders`: This table lists the order details such as order IDs, dates, and times.
- `fact_sales`: This fact table includes sales transactions with order IDs, pizza IDs, quantities, and sales amounts.
- `fact_customers`: Contains data on customer IDs, locations, and purchase histories.

### 4. Data Modelling
Data modeling is the foundation of the analysis. In this project, data was modeled using Power BI’s Power Query. The following steps were followed:

- Data cleaning, formatting, and transformation using Power Query.
- Establishing relationships among tables, adopting the Star Schema methodology.
- Validating the data against the metrics provided by stakeholders.

### 5. Dashboard Designing
Based on the mockups received as requirements, the following views were designed:

#### Views:
| **Views** | **Description** |
|-----------|-----------------|
| **Overall** | Provides a comprehensive overview of pizza sales, revenue, and customer insights. |
| **Revenue** | Analyzes the revenue from pizza sales, order sizes, and customer orders. |
| **Order Insights** | Focuses on the frequency of orders, pizza types, and the best-selling pizza categories. |

#### Basic Metrics:
- **Day Type**: Determines whether sales were made on weekdays or weekends.
- **Pizza Type**: Various pizza types like Classic, Specialty, and Supreme are analyzed.
- **Order Time**: Order times were categorized into morning, afternoon, evening, and night.
- **Customer Location**: City-wise customer data.
- **Order ID**: Unique identifier for every order placed.

#### Measures:
| **Measures** | **Description** |
|--------------|-----------------|
| **Total Revenue** | Total revenue generated from pizza sales. |
| **Total Orders** | Number of pizza orders placed. |
| **Average Order Value** | Average revenue per order. |
| **Total Quantity Sold** | Total number of pizzas sold. |
| **Revenue per Pizza Type** | Revenue breakdown by pizza category. |
| **Most Popular Pizza Size** | The most frequently ordered pizza size. |
| **Cancellation Rate** | Percentage of canceled orders. |

### 6. Filters Used
- **Pizza Type**: To filter sales performance by pizza category.
- **Order Time**: To analyze sales during specific time periods.
- **Customer Location**: To see location-based customer preferences.
- **Order Size**: To explore the size of the orders (small, medium, large).

### 7. Dashboard Created
A comprehensive dashboard was created based on the provided data and stakeholder requirements. This dashboard provides key insights into pizza sales performance, customer behavior, and helps optimize business strategies.

### 8. Project Outcomes
#### Learnings from this Project:
- Gained expertise in creating custom visuals for sales analysis using Power BI.
- Identified patterns in pizza sales, such as the popularity of specific pizza sizes during weekends.
- Developed insights into customer behavior that helped in crafting marketing strategies.

#### Key Metrics:
- **Total Revenue**: Amount generated from pizza sales.
- **Total Orders**: Number of successful orders.
- **Average Order Value**: Average amount spent per order.
- **Most Popular Pizza**: The most frequently ordered pizza type.
- **Revenue Loss from Cancellations**: Financial loss due to canceled orders.

### 9. Insights from the Dashboard:
- **Classic pizzas** are the most popular, contributing to 45% of total revenue.
- The **evening time** sees the highest number of orders, accounting for 50% of total sales.
- **Medium-sized pizzas** are the most ordered, followed by large pizzas.
- The highest revenue was generated during the weekend, particularly on **Fridays** and **Saturdays**.
- **Order cancellations** resulted in a revenue loss of approximately 15%.
- **City A** generated the highest revenue, while **City B** had the most orders but a lower average order value.

