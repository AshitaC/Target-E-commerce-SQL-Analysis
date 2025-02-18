
# Target Brazil E-commerce SQL Analysis

##  Project Overview
This project analyzes 100,000 orders from Target Brazil (2016-2018) to uncover key business insights using SQL. The dataset covers customer demographics, order details, payments, shipping performance, and product reviews.

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

## Technologies Used
- SQL (Google BigQuery)
- Data Exploration & Aggregation
- Time Series & Trend Analysis
- Geospatial Data Analysis

## Dataset
The dataset includes the following CSV files:
1. `customers.csv` - Customer details
2. `geolocation.csv` - Location data
3. `order_items.csv` - Order line items
4. `payments.csv` - Payment details
5. `reviews.csv` - Customer reviews
6. `orders.csv` - Order metadata
7. `products.csv` - Product attributes
8. `sellers.csv` - Seller information

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

