# Adventure Works Sales Analysis



## 📌 Overview

The Adventure Works Sales Dashboard provides strategic insights into the performance of a fictional bicycle company over the period 2020–2022. Built using the Adventure Works dataset, it integrates data from sales, customers, products, and returns to deliver a comprehensive view of business operations. 
The dashboard highlights key metrics such as customer behavior, product performance, regional sales distribution, and return patterns. Through dynamic visualizations and KPIs, it supports data-driven decision-making and uncovers trends that drive strategic business growth.


![Overview](https://github.com/user-attachments/assets/34636b7b-0c87-455d-94a6-2e872468ff5b)



## 💡 Tools & Skills 

- Power BI Data Modeling
- Data Cleaning and Relationships
- DAX Measures 
- Dashboard Design and Theming
- Business Storytelling

## 🧹 Data Cleaning & Modeling

###  Calendar Table
Created a custom calendar table to support time intelligence features with:
- Month Name
- Day Name
- Quarter
- Start of Quarter
- Start of Month
- Start of Week

###  Customer Lookup Table
Added the following enriched columns:
- Full Name (First + Last)
- Is_Parent (Flag for customers with children)
- Age Group
- Income Level: categorized as:
  - Lower Middle Class  
  - Middle Class  
  - Upper Middle Class

###  Product Lookup Table
- Added **Gender Type** to define if the product is for Men, Women, or Unisex.

###  Sales Final Table
Merged yearly sales data (2020, 2021, 2022) into one unified **Sales Final Table** for consolidated analysis.

###  Measures Table
Created a centralized **Measure Table** with the following DAX measures:

- Total_Revenue
- Total_Cost
- Total_Orders
- Total_Quantity_Sold
- Total_Returned_Quantity
- Profit_Margin
- Profit_Margin_%
- Return_Rate_%


## 🚀 Key Features

- 📦 **Unified Sales Data**: Combined data from three years (2020–2022) into a single, clean dataset.
- 📊 **Interactive Dashboard**: Dynamic slicers, filters, and visualizations for exploring trends by product, region, and category.
- 🧠 **Smart Measures**: Custom DAX calculations for profit margin, return rate, total cost, quantity, and revenue.
- 🌍 **Geographical Insights**: Country- and continent-level breakdown of orders and revenue.
- 📆 **Time Intelligence**: Custom calendar table enables monthly, quarterly, and yearly trend analysis.
- 👥 **Customer Segmentation**: Demographic attributes such as income level, age group, and parental status used for enhanced analysis.
- 🧺 **Product Category Analysis**: Insights by Bikes, Accessories, and Clothing — including return behaviors and order patterns.
- 🎨 **Consistent Branding**: Custom color palette and branded visuals using Adventure Works' logo and theme.

---

![Screenshot_1](https://github.com/user-attachments/assets/16599c54-a427-40e5-8fec-c383a3677639)


---

## 📊 Key Visuals
-  Sales and orders by **continent** and **country**
-  Top 10 best-selling **products**
-  Orders by **category** (Accessories, Bikes, Clothing)
-  Monthly **trendline** of total revenue (2020–2022)

🔍 Key Insights
- Track which product categories drive the most revenue.
- Analyze seasonal trends using calendar-based sales data.
- Identify top-performing regions or customer types.
- Understand return patterns and how they affect net sales.

## ✨ Key Highlights

- 💰 **Total Revenue:** $24.91M
- 📦 **Total Orders:** 25K
- 💹 **Profit Margin:** $10.46M
- 🔁 **Return Rate:** 2.17%
- 🌍 **Top Region:** Europe
- 🚲 **Top Product:** Mountain-200 Black, 46

 


## 🔍 Top Insights 

1. 🛍️ Product Performance
   - The Mountain-200 bicycle series made the most money and had the most orders.
   - Products with higher profit usually had fewer returns, especially in Europe.

2. 🌍 Regional Insights
   - Europe had the highest sales and fewer returned items compared to other regions.
   - North America sold a lot of Road-250 bikes, but also had more returns than Europe.

3. 📦 Category Breakdown
   - Accessories (like helmets, bags, etc.) had the most number of orders.
   - Clothing sold the least and had the highest return rate — about 4.4%.

4. 👤 Customer Analysis
   - Dividing customers by age and income helps to target the right audience.
   - Most of the big spenders were from the Middle Class and Upper Middle Class groups.

5. 📅 Time Trends
   - Sales and revenue were higher at the beginning and end of each year, showing good times for promotions or sales events.
---

![Screenshot_2](https://github.com/user-attachments/assets/3df68078-f9db-405d-b2d4-d82b2ac7b4c7)

 --- 

## 📚 Data Story

Adventure Works is a company that sells bicycles, clothes, and accessories in places like Europe, North America, and the Pacific. To understand how the business is doing, they collected sales data from the last three years. This project puts all the data together and adds extra details like customer age, income, and product types. The dashboard helps answer simple questions like: Where are we selling the most? Which products are popular? Who are our main customers? Are we making good profit? With easy charts and numbers, the report helps the company make better decisions and grow their business.

---

## ✅ Recommendations

- ✅ **Double down on Europe**: Continue investing in marketing and distribution in Europe due to its superior revenue performance.
- ✅ **Expand Mountain Bike product line**: Introduce new models/variations in the Mountain-200 series.
- ✅ **Reduce Clothing return rate**: Re-evaluate sizing or product quality and optimize return policies.
- ✅ **Target Middle and Upper Middle Class customers**: Based on consistent high-spending behavior.
- ✅ **Leverage Q1 & Q4 seasonality**: Launch promotional campaigns to maximize seasonal demand.


