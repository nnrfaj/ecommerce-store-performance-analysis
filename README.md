# E-commerce Performance Analysis for SMACOP Online Store

## Scenario

SMACOP is a fictional online retailer specializing in high-end consumer electronics, primarily offering Apple products such as iPhones, Apple Watches, and AirPods.

The company operates globally, with a strong presence in North America, Europe, and Oceania. As a data analyst for SMACOP, I was tasked with analyzing the company's sales data from October 2023 to August 2024 to identify trends, assess performance, and provide actionable insights to drive business growth.

## Data Source

The dataset used realistic product information, pricing, and simulated customer behavior.

A Python script was developed with the help of ChatGPT and Claude (LLMs) to generate synthetic transaction data using Jupyter Notebook, incorporating variables such as product details, customer demographics, purchase information, and geographical information.

The script used probability distributions to create a dataset that mimics real-world e-commerce patterns.

## Tools Used for Analysis

The data analysis was carried out using the following tools.

**1.) Excel**

Data files (products, orders, and customers CSV files) were loaded into Power Query for initial transformation and cleaning.

![1 loaded data into power query](https://github.com/user-attachments/assets/5e325d7a-41f9-4f41-82dd-20ac3b370b4e)

The dataset tables were then loaded into Power Pivot for data modeling, where calculated fields such as Age Groups (derived from customer ages), Revenue (calculated from product price and quantity sold), and Average Order Value (calculated from revenue and order numbers) were created.

![2 loaded data into power pivot](https://github.com/user-attachments/assets/92a1b391-fe7a-4100-841e-c39a068f4cfe)

![3 data modelling in power pivot](https://github.com/user-attachments/assets/a7bf963c-a16c-4021-87ca-46fc5bdcdb2c)

Pivot Tables were then used to conduct the full analysis, focusing on the company’s North Star metrics. This enabled the identification of key trends, customer behavior, and product performance.

**2.) Tableau**

Designed an interactive dashboard to visualize key metrics and trends related to sales and revenue.

[**See the Dynamic Tableau Dashboard**](https://public.tableau.com/app/profile/adefajo.rasaq/viz/EcommercePerformanceAnalysis-RevenueDashboard/SalesDashboard)

[**Also Check My Profile on Tableau**](https://public.tableau.com/app/profile/adefajo.rasaq/vizzes)

## Key Analysis Results

### 1.) Total Revenue

The analysis revealed a total revenue of $8,925,814, reflecting the overall sales performance of the store across all product categories and customer segments.

![4 total revenue](https://github.com/user-attachments/assets/f7532502-acd7-4c0b-9816-5cbb18a2c859)

### 2.) Average Order Value (AOV)

Customers on average spend $892.58 per order.

![5 average order value (AOV)](https://github.com/user-attachments/assets/a7575e3a-2999-45b7-818d-148986e20625)

### 3.) Revenue per Customer

On average, each customer contributed $4,462.91 to the total revenue, highlighting the significant purchasing power of the customer base.

![6 revenue per customer](https://github.com/user-attachments/assets/aa002d98-91f9-4d6a-b08b-969e0be9018f)

### 4.) Order Frequency

In 2023, the highest order volume was recorded in December with 944 orders, followed by October with 934 orders, and November with 894 orders.

![7 order frequency by month](https://github.com/user-attachments/assets/e235b82b-655b-44d9-88fd-f87f81d4dbb6)

In 2024, August led with 992 orders, followed by March with 925 orders, and January with 923 orders. These figures suggest a strong seasonal trend in sales performance.

### 5.) Product Revenue

The iPhone 15 Pro (1TB) generated the highest revenue at $644,570, followed closely by the iPhone 15 Pro Max (1TB) with $638,001 in revenue, and the AirPods Max with $619,821.

![8 product performance](https://github.com/user-attachments/assets/6ea209bb-c51b-4538-97f3-49a6e6258cf1)

Despite the iPhone 15 Pro’s top revenue, the iPhone 15 Pro Max (1TB) achieved a higher Average Order Value of $1,921.69 compared to the iPhone 15 Pro (1TB) at $1,820.92.

The AirPods Max achieved a lower AOV of $642.97 due to its price and higher order volume of 964 orders compared to the iPhone 15 Pro Max’s 332 orders and the iPhone 15 Pro’s 354 orders.

### 6.) Sales Volume by Product

The highest-selling products were the AirPods lineup (Earbud category), with the AirPods Max leading at 1,129 units sold, followed by AirPods 2 (1,127 units), AirPods Pro 2 (1,090 units), and AirPods 3 (1,039 units).

![9 revenue and quantity sold by product](https://github.com/user-attachments/assets/65c1e53b-8491-4fb9-90c1-b306081291c1)

These were followed by the Apple Watch Ultra 2 (709 units), Apple Watch Series 9 Aluminum (676 units), and Apple Watch Series 9 Stainless Steel (670 units).

Although the AirPods led in sales volume, iPhones were the primary revenue drivers.

### 7.) Category Performance

Smartphones dominated revenue generation with $6,344,894 from 5,506 sales.

![10 revenue and quantity sold by category](https://github.com/user-attachments/assets/88d41f08-618b-407f-84a2-0e24dc394ae5)

Smartwatches contributed $1,358,325 from 2,055 sales, while Earbuds added $1,222,595 from 4,385 sales.

The product portfolio consists of 13 smartphones, 3 smartwatches, and 4 earbuds.

### 8.) Customer Demographics

Customers aged 45-49 contributed the highest revenue, totaling $1,568,955 from 2,105 units sold.

![11 revenue by age group](https://github.com/user-attachments/assets/95f969ce-3e21-4621-83a2-e0f0566d5a07)

They were followed by customers aged 40-44 with $1,495,704 in revenue and 1,986 units sold, and customers aged 20-24 with $1,489,210 in revenue and 2,000 units sold.

The female customer segment purchased 6,145 units and generated $4,567,455 in revenue, outperforming the male segment, which purchased 5,801 units and contributed $4,358,359 in revenue.

![13 revenue and quantity sold by gender](https://github.com/user-attachments/assets/150de2e7-d175-4dfb-9585-d0569c0940c9)

### 9.) Geographic Insights

The United States generated the highest revenue at $3,409,791 with 4,559 units sold, followed by Canada with $1,361,153 (1,777 units), Australia with $1,336,126 (1,814 units), and the United Kingdom with $1,247,961 (1,719 units).

![12 revenue and quantity sold by region and country](https://github.com/user-attachments/assets/0ea4499d-91d2-4115-8096-e7e35c8b4d6f)

North America was the top-performing region with $4,831,612 in revenue from 6,418 units sold, followed by Europe with $1,925,793 from 2,597 units, and Oceania with $1,336,126 from 1,814 units. Asia trailed with $605,170 in revenue from 790 units sold.

## Insights

### 1.) Product Performance

High-end products, particularly iPhones, are driving revenue (contributing over 70% of total revenue) despite lower sales volumes.

AirPods are the best-selling products by quantity but contribute less to overall revenue. The smartphone category is the primary revenue driver, followed by smartwatches and earbuds.

This shows a diverse product mix with high-value items driving revenue and accessories driving volume. The diverse product mix helps stabilize revenue across different customer segments.

The Average Order Value and Revenue per Customer suggest customers are buying premium products or multiple items per order.

### 2.) Customer Behavior

Older customers (45-49 age range) are the most valuable in terms of revenue and quantity purchased indicating a mature and potentially affluent customer base.

There's a strong showing from younger customers (20-24), indicating a diverse customer base.

Female customers slightly outperform male customers in both quantity purchased and revenue generated.

### 3.) Geographical Performance

North America, particularly the United States, is the strongest market. There's significant potential in Europe and Oceania markets.

Asia appears to be an underperforming market compared to other regions.

### 4.) Seasonal Trends

Peak order months align with key shopping seasons, like December (holiday season) and back-to-school periods in October, and August.

## Recommendations

The result of the analysis and insights derived from it leads to these strategic recommendations.

### 1.) Product Strategy

Focus marketing efforts on high-revenue products like the iPhone 15 Pro and Pro Max models.

Consider bundling AirPods with higher-priced items like the Pro iPhones to increase the Average Order Value.

This can include something like recommending accessories or upgrades during the purchase process or creating attractive bundles combining popular items (e.g., iPhone + AirPods) to increase overall transaction value.

Expand the smartwatch lineup, as it shows strong performance with fewer product options.

### 2.) Customer Targeting

Develop targeted marketing campaigns for the 45-49 age group, emphasizing premium products.

Create initiatives to increase engagement with the 20-24 age group, potentially through student discounts or younger-skewing product bundles.

Tailor marketing messages to appeal to female customers, as they're slightly outperforming male customers.

### 3.) Geographical Expansion

Prioritize North America for growth (United States and Canada in particular).

Invest in strengthening the market presence in Europe and Oceania to capitalize on their potential.

Develop a strategy to boost performance in the Asian market, possibly through localized marketing or partnerships.

### 4.) Seasonal Planning

Prepare for increased demand during the holiday season (October-December) by ensuring adequate inventory and support staff.

Consider running targeted campaigns or promotions in August to capitalize on the high sales volume.
