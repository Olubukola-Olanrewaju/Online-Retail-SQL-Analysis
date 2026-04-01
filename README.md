# Online Retail SQL Analysis

## Project Objective

The goal of this project is to analyze retail transaction data to uncover sales patterns, customer behavior, and business opportunities using SQL.

## Business Questions

- Which products generate the most revenue?
- Who are the highest value customers?
- Which countries drive the most sales?
- Is there any seasonal trend in sales?

## SQL Skills Demonstrated

- Data cleaning
- Filtering and conditional logic
- Aggregation (SUM, COUNT)
- Grouping and sorting
- Case statements for segmentation
- Date formatting and time analysis

## Data Cleaning Process

* Removed records with missing product descriptions
* Removed records with missing customer IDs
* Excluded canceled transactions (InvoiceNo starting with 'C')
* Removed negative quantities (returns)

Clean dataset: 9,336 records from 12,959 total rows

## Analysis Performed

### 1. Top Products by Revenue

| Product                            | Revenue (£) |
| ---------------------------------- | ----------- |
| REGENCY CAKESTAND 3 TIER           | 5567.40     |
| BLACK RECORD COVER FRAME           | 3868.35     |
| WHITE HANGING HEART T-LIGHT HOLDER | 2806.30     |
| CHILLI LIGHTS                      | 2399.04     |
| RED WOOLLY HOTTIE WHITE HEART.     | 2394.00     |

### 2. Customer Segmentation

Customers were grouped based on total spending:

* High Value (≥ 5000)
* Mid Value (2000 – 4999)
* Low Value (< 2000)

Top Customers:

* Customer 15061 → £9407.34 (High Value)
* Customer 13777 → £6585.16 (High Value)
* Customer 17850 → £5391.21 (High Value)
* Customer 16210 → £4738.54 (Mid Value)
* Customer 16029 → £4271.52 (Mid Value)

### 3. Country-Level Insights

* United Kingdom dominates sales and revenue
* Other countries contribute smaller but meaningful sales
* Some countries show bulk buying behavior

### 4. Time-Based Analysis

* All transactions fall within December 2010
* Total Sales: £175,354.24
* Total Orders: 477
* Sales peak during the holiday season

## Key Insights

* A small number of products drive most revenue
* High-value customers contribute significantly to total sales
* The United Kingdom is the primary market
* Sales are highly seasonal (December peak)

 ## Top Products by Revenue

![Top Products]([top_products.png](https://github.com/Olubukola-Olanrewaju/Online-Retail-SQL-Analysis/blob/main/Top_Products.png))

## Customer Segmentation

![Customer Segmentation]([customer_segmentation.png](https://github.com/Olubukola-Olanrewaju/Online-Retail-SQL-Analysis/blob/main/Customer_Segmentation.png))

## Business Recommendations

* Focus retention strategies on high-value customers
* Promote top-performing products to increase revenue
* Expand marketing efforts to international markets
* Prepare inventory ahead of December peak periods
* Review low-performing products for improvement or removal

## Tools Used

* MySQL Workbench
* SQL

## Conclusion

This project shows how SQL can be used to clean data and generate real business insights from raw transactional data.
