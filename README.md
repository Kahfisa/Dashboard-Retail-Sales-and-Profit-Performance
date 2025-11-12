# Retail-Sales-Performance

## Introduction
This dashboard provides an overview of retail business performance, displaying key metrics such as total transactions, total customers, total revenue, and profit. It also presents sales and transaction trends over time, breakdowns by product category, profit by city, customer distribution by city, and detailed tables highlighting top performing customers.

## Tools
- Python
- Google Looker Studio

## Dataset
|Dataset             |Column                                                                                                                                                                                                                |
|--------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|superstore          |row_id, order_id, order_date, ship_date, ship_mode, customer_id, customer_name, segment, country, city, state, postal_code, region, product_id, category, subcategory, product_name, sales, quantity, discount, profit|

Link: https://www.kaggle.com/datasets/vivek468/superstore-dataset-final

## Business Question
- What are the total transactions, number of customers, revenue, and profit from January 2014 to December 2017?
- What are the trends in sales and transactions from January 2014 to December 2017?
- Which product categories contribute the most to revenue?
- What is the distribution of profit across cities?
- Who are the customers with the highest spending?

## Dashboard Preview

<img width="1365" height="766" alt="image" src="https://github.com/user-attachments/assets/4b664518-cb08-4174-b87b-6cf55c0ff3d0" />

<img width="1364" height="767" alt="image" src="https://github.com/user-attachments/assets/d910c76c-05af-4f71-9393-a9d96bfa3cc3" />

Logo Source: [freepik](https://www.freepik.com/)

## Insight
- The number of transactions in Q1 tends to be relatively low each year but begins to rise in March. In Q2, the number of transactions remains relatively stable, with a slight decline in May during 2014 and 2015, while in 2016 and 2017, there was an increase in the same month. Entering Q3, there is a significant rise, especially in September, which marks one of the annual transaction peaks. Meanwhile, in Q4, a decline in transactions occurred in October and December during 2014–2016; however, in 2017, December transactions remained stable, indicating an improvement in the trend toward the end of the year.
- The fluctuation patterns between the Number of Transactions and Total Sales are almost identical throughout the year. However, two points require further analysis: in December 2016, the graph shows a decline in the number of transactions but an increase in total sales, suggesting higher-value purchases during that period. Meanwhile, in December 2017, the number of transactions remained stable, but total sales decreased, indicating a possible drop in average order value or a shift toward lower-priced products.
- Most customers come from three major cities: New York, Los Angeles, and San Francisco. These three cities also contribute the highest profits to the company, with respective contributions of $62,036 from New York, $30,440 from Los Angeles, and $17,507 from San Francisco.
- The product categories that contribute the most to total sales are Phones, Chairs, and Storage.
- Sean Miller, Tamara Chand, and Raymond Bunch are the top-performing sales contributors, generating revenues of $25,043, $19,052, and $15,117. They are followed by Tom Ashbrook, Adrian Barton, Ken Lonsdale, Sanjit Chand, and Hunter Lopez, who each contribute an average of around $14,000.



