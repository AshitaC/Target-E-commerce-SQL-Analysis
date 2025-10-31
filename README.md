
# Target Brazil E-commerce SQL Analysis

##  Project Overview
This project analyzes **100k orders** from **Target** Brazil (2016-2018) to uncover key business insights using **SQL (Google Big Query)**. The dataset covers customer demographics, order details, payments, shipping performance, and product reviews.

**Dataset schema:**

The data is available in 8 different csv files:

1. customers.csv

2. geolocation.csv

3. order_items.csv

4. payments.csv

5. reviews.csv

6. orders.csv

7. products.csv

8. sellers.csv

<img width="1299" height="783" alt="image" src="https://github.com/user-attachments/assets/ff4a0ff6-b428-4d86-b202-3efaad84f096" />

##  Project Statement

Analyzing the given dataset to extract valuable insights and provide actionable recommendations.  

#### In-depth Exploration

- Is there a growing trend in the no. of orders placed over the past years?
  
- Can we see some kind of monthly seasonality in terms of the no. of orders being placed?
  
- During what time of the day, do the Brazilian customers mostly place their orders? (Dawn, Morning, Afternoon or Night)
  
#### Evolution of E-commerce orders in the Brazil region:

- Get the month on month no. of orders placed in each state.
  
- How are the customers distributed across all the states?

#### Impact on Economy: 
- Analyze the money movement by e-commerce by looking at order prices, freight and others.

- Get the % increase in the cost of orders from year 2017 to 2018 (include months between Jan to Aug only).

- Calculate the Total & Average value of order price for each state.

- Calculate the Total & Average value of order freight for each state.

#### Analysis based on sales, freight and delivery time.

- Find the no. of days taken to deliver each order from the order’s purchase date as delivery time.

  Also, calculate the difference (in days) between the estimated & actual delivery date of an order.

- Find out the top 5 states with the highest & lowest average freight value.
  
- Find out the top 5 states with the highest & lowest average delivery time.
  
- Find out the top 5 states where the order delivery is really fast as compared to the estimated date of delivery.

#### Analysis based on the payments:

- Find the month on month no. of orders placed using different payment types.
  
- Find the no. of orders placed on the basis of the payment installments that have been paid. 

## Key Insights

- **Sales Trends**: Peak sales in **November**, most purchases made in the **afternoon and night**.
  
- **Customer Distribution**: Majority from **São Paulo, Rio de Janeiro, and Minas Gerais**.
  
- **Economic Impact**: **137% increase** in order costs from 2017 to 2018 (Jan-Aug).
  
- **Logistics**:
  
  - **Average delivery time**: 12 days.
    
  - **Orders arrive ~10 days earlier** than estimated.
    
  - **Highest freight costs & delays**: **Roraima**.
 
  - **Lowest freight costs & fastest delivery**: **São Paulo**.
    
- **Payment Insights**: Most orders were completed in **one installment**.

## Analysis Highlights

- **Seasonality & Trends**: Monthly & hourly purchase patterns.
  
- **Geographic Insights**: Customer locations & spending habits.
  
- **Economic Impact**: Cost evolution, freight & delivery efficiency.
  
- **Payment Behavior**: Installment-based purchasing trends.

## Business Recommendations

1. **Stock up inventory in November** to handle peak demand.
   
2. **Offer promotions from 12 PM to midnight** to maximize sales.
   
3. **Expand offerings & discounts in top-selling states** (São Paulo, Rio de Janeiro).
   
4. **Improve logistics in Roraima** due to high freight costs & slow delivery.

