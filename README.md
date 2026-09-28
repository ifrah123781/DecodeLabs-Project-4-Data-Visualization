# DecodeLabs-Project-4-Data-Visualization
Created data visualizations (Bar, Line, and Pie charts) using Matplotlib and Seaborn to communicate e-commerce sales performance, revenue trends, and fulfillment insights.
# Data Visualization & Storytelling

## Project Overview

This project focuses on creating visual representations of an e-commerce sales dataset to communicate key business insights clearly and effectively.

Using Python visualization libraries such as Matplotlib and Seaborn, different charts were developed to analyze product performance, revenue trends over time, order fulfillment, marketing channel contributions, and customer payment methods.

The dataset contains 1,200 orders across 14 original features related to customers, products, pricing, fulfillment status, and sales channels.

## Objectives

* Create visual representations of e-commerce data
* Communicate business insights clearly through visualizations
* Generate Bar, Line, and Pie/Donut charts
* Select appropriate visualizations for different data types
* Identify important patterns and trends
* Apply proper chart titles, axis labels, and value annotations
* Present analytical findings through data storytelling

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab / Jupyter Notebook
* Excel

## Dataset Information

* **Total Orders:** 1,200
* **Original Features:** 14
* **Date Range:** 2023–2025
* **Dataset Type:** E-commerce Sales Transactions

### Main Features

* OrderID
* Date
* CustomerID
* Product
* Quantity
* UnitPrice
* ShippingAddress
* PaymentMethod
* OrderStatus
* TrackingNumber
* ItemsInCart
* CouponCode
* ReferralSource
* TotalPrice

## Visualizations & Analysis Performed

### 1. Product Revenue Performance — Bar Chart

A vertical bar chart was created to compare total revenue across seven product categories.

| Product  |  Revenue |
| -------- | -------: |
| Chairs   | $195,620 |
| Printers | $195,613 |
| Laptops  | $192,127 |
| Tablets  | $186,569 |
| Monitors | $175,651 |
| Desks    | $167,460 |
| Phones   | $151,722 |

**Key Observation:** Chairs and Printers generated the highest total revenue, while Phones generated the lowest revenue among the analyzed products.

### 2. Temporal Sales Trend — Line Chart

A time-series line chart was created to track monthly total revenue from January 2023 through June 2025.

**Key Observation:** Monthly revenue generally fluctuated between approximately $30,000 and $55,000, with a notable peak exceeding $67,000 during mid-2024.

### 3. Fulfillment & Order Lifecycle — Donut Chart

A proportional donut chart was used to visualize the distribution of orders by fulfillment status.

| Order Status | Orders | Percentage |
| ------------ | -----: | ---------: |
| Cancelled    |    250 |      20.8% |
| Returned     |    247 |      20.6% |
| Pending      |    237 |      19.8% |
| Shipped      |    235 |      19.6% |
| Delivered    |    231 |      19.2% |

**Key Observation:** Cancelled and Returned orders together represented approximately 41.4% of total orders, highlighting an area for further operational analysis.

### 4. Marketing Acquisition Performance — Horizontal Bar Chart

A horizontal bar chart was created to compare revenue generated through different referral channels.

| Referral Source |  Revenue |
| --------------- | -------: |
| Instagram       | $275,285 |
| Email           | $261,809 |
| Google          | $250,441 |
| Facebook        | $250,411 |
| Referral        | $226,816 |

**Key Observation:** Instagram generated the highest revenue among the analyzed referral sources, followed by Email.

### 5. Payment Channel Utilization — Bar Chart

A bar chart was used to compare transaction frequency across different payment methods.

| Payment Method | Transactions |
| -------------- | -----------: |
| Online         |          258 |
| Cash           |          246 |
| Credit Card    |          234 |
| Debit Card     |          232 |
| Gift Card      |          230 |

**Key Observation:** Online payments had the highest transaction frequency, while overall transaction volumes were relatively close across the different payment methods.

## Key Observations

* Chairs and Printers were the highest-revenue product categories, generating approximately $195.6K each.
* Cancelled and Returned orders together represented approximately 41.4% of all orders.
* Monthly revenue generally remained within an approximate $30K–$55K range, with a notable peak above $67K in mid-2024.
* Instagram generated the highest revenue among the analyzed marketing channels.
* Online payment was the most frequently used payment method with 258 transactions.
* Different chart types helped communicate product, temporal, fulfillment, marketing, and payment patterns effectively.

## How to Run

### Using Google Colab

1. Open `DecodeLabs_Project_4.ipynb` in Google Colab.
2. Upload `Dataset for Data Analytics (3).xlsx` when prompted.
3. Run the notebook cells sequentially.
4. Review the generated charts and analytical observations.

### Local Python Environment

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn openpyxl
```

Open `DecodeLabs_Project_4.ipynb` using Jupyter Notebook, JupyterLab, or VS Code and run the cells sequentially.

## Skills Demonstrated

* Data Visualization
* Data Storytelling
* Chart Selection
* Bar Charts
* Horizontal Bar Charts
* Line Charts
* Donut/Pie Charts
* Data Aggregation
* Trend Analysis
* Insight Communication
* Python
* Pandas
* Matplotlib
* Seaborn

## Project Status

**Completed — DecodeLabs Internship Project 4**
