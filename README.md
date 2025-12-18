**Online Retail Customer Segmentation (RFM Analysis)**

**---Project Overview---**

This project focuses on analyzing a transnational dataset containing all transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.

The primary goal was to assist the Marketing Director in understanding customer behavior and sales performance to drive data-driven decisions. Specifically, the analysis answers three key business questions:

What are the best-selling products?

Which countries generate the most revenue?

Who are the most valuable customers? (Solved using RFM Segmentation)

**---Data Source---**

The dataset used in this analysis is the Online Retail dataset. Due to GitHub's file size limitations, the raw .csv file is not included in this repository.

Link to the original data: [Online Retail Dataset on Kaggle](https://www.kaggle.com/datasets/vijayuv/onlineretail)

**---Methodology and Tech Stack---**

Language: Python 3

Libraries: Pandas, Matplotlib, Seaborn

**---Key Techniques---**

Data Cleaning: Handling missing values (CustomerID and Description), removing negative quantities, and filtering out invalid prices.

Exploratory Data Analysis (EDA): Sales distribution by country and identification of the top 5 most sold products.

RFM Analysis: Customer segmentation based on Recency (days since last purchase), Frequency (total number of transactions), and Monetary (total spend).

**---Key Findings---**

1. Best-Selling Products
The analysis identified the top 5 products by quantity sold, such as World War 2 Gliders and Jumbo Bag Red Retrospot. These items drive the bulk of the volume and are crucial for inventory management.

<img width="983" height="590" alt="image" src="https://github.com/user-attachments/assets/7bff930f-dbfa-4891-bc46-8c0045bb32e7" />

3. Top Markets (Revenue by Country)
Excluding the UK, the top international markets were identified. Netherlands, EIRE, and Germany emerged as the most profitable regions, suggesting focused marketing campaigns in these areas.

<img width="889" height="490" alt="image" src="https://github.com/user-attachments/assets/07ac45a9-f016-4e1b-9b39-2449b66e3ae5" />

5. Customer Segmentation
Using the RFM model, customers were assigned scores and categorized into segments.

<img width="1189" height="590" alt="image" src="https://github.com/user-attachments/assets/1f946356-7295-429c-a719-822a23a42954" />



Champions: A specific group of 573 high-value customers who buy frequently, recently, and spend the most was identified.

Actionable Insight: A list of the top 100 Champion customers was generated for targeted high-value marketing actions.
