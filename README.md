📊 Transaction Dataset Analysis

✅ Project Purpose 
 
- In this project, I analyzed a transaction dataset to understand:
- how much total sales happened

- which products and services perform best

- which customers spend more

- which locations generate more revenue

- how sales change over time

- how payment type affects spending

The goal is to convert raw transaction records into useful business insights.

🧠 How I Approached the Analysis

First, I loaded the dataset using pandas and checked:
column names,
data types,
sample rows,
dataset size

Then I converted the date column into proper datetime format so I could analyze month and quarter trends.

- After that, I grouped and summarized the data using:
sum → for total revenue,
mean → for averages,
count → for frequency,
groupby → for category comparison

💰 Key Revenue Findings

- Total revenue was calculated for all transaction amounts

- The highest single transaction was identified using max()

- Average transaction value was computed to understand typical customer spending

This helps measure overall business performance.

📅 Time Trend Findings

- I extracted month and quarter from transaction dates

- Monthly and quarterly sales totals were calculated

Finding: Some months and Q3 showed higher sales — indicating seasonal demand patterns.

👥 Customer Insights

- Counted total unique customers

- Calculated average transactions per customer

- Found top spending customers

- Measured repeat buyer percentage

Finding: A large percentage of customers are repeat buyers


🏷 Service & Product Insights

- Calculated total revenue per service category

- Identified most popular services by transaction count

- Found highest revenue products

- Compared average spending across services

Finding: Outdoor Recreation and Exercise & Fitness categories perform strongly.

🌍 Location Insights

- Compared revenue by state

- Found cities with most transactions

- Calculated average spend per state

Finding: California and Texas generate the highest total sales.

💳 Payment Insights

- Counted number of credit transactions

- Calculated total revenue from credit payments

- Compared average spending by payment type

Finding: Credit users spend more on average than cash users.

📦 Business Recommendations

Based on analysis:

- Stock more inventory in top service categories

- Focus marketing in high-revenue states

- Offer promotions for low-performing services

- Target repeat buyers with loyalty programs

- Use seasonal trends for campaign timing

🛠 Tools Used
Python,
Pandas,
Jupyter Notebook

📊 Business Insights —

Sales mostly come from Outdoor Recreation and Exercise & Fitness, with many repeat customers and seasonal patterns. Most revenue comes from states like California and Texas, and credit users spend more. The company should focus on top categories and regions while improving low-performing services and using loyalty programs to grow.
