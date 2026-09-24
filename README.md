# Customer Shopping Behavior Analysis

An end-to-end data analytics project analyzing customer shopping behavior using **Python, SQL, and Power BI**. The project explores purchasing patterns, customer segments, product preferences, discounts, subscriptions, and revenue trends to generate actionable business insights.

## Overview

The goal of this project is to understand customer purchasing behavior and identify patterns that can support business decision-making.

The analysis covers:
- Customer demographics and purchasing patterns
- Product and category performance
- Customer segmentation
- Subscription behavior
- Discount usage
- Revenue trends across age groups
- Shipping and purchasing behavior

The project follows an end-to-end analytics workflow:

**Data Cleaning → Exploratory Data Analysis → SQL Analysis → Power BI Dashboard → Business Insights**

## Dataset

The dataset contains **3,900 customer purchase records** with **18 columns**.

Key attributes include:
- Customer demographics: Age, Gender, Location
- Purchase details: Item, Category, Purchase Amount, Season, Size, Color
- Shopping behavior: Discount Applied, Previous Purchases, Purchase Frequency
- Customer feedback: Review Rating
- Subscription and shipping information

The dataset contained **37 missing values in the Review Rating column**, which were handled during data preprocessing. :contentReference[oaicite:0]{index=0}

## Tools

- **Python** – Data cleaning, preprocessing, feature engineering, and exploratory data analysis
- **Pandas** – Data manipulation and analysis
- **PostgreSQL** – SQL-based business analysis
- **Power BI** – Interactive dashboard and data visualization

## Dashboard

An interactive **Power BI dashboard** was created to visualize key customer and sales metrics.

The dashboard includes:
- Average Purchase Amount
- Number of Customers
- Average Review Rating
- Customer subscription distribution
- Revenue and sales by category
- Revenue and sales by age group
- Interactive filters for customer and purchase attributes

The dashboard reports an average purchase amount of **$59.76**, approximately **3.9K customers**, and an average review rating of **3.75**. :contentReference[oaicite:1]{index=1}

## Results

The analysis generated several business insights:

- Customers were segmented into **New, Returning, and Loyal** groups based on purchase history.
- **3,116 customers** were classified as Loyal, 701 as Returning, and 83 as New. :contentReference[oaicite:2]{index=2}
- Express shipping had a slightly higher average purchase amount than Standard shipping: **$60.48 vs. $58.46**. :contentReference[oaicite:3]{index=3}
- The analysis identified the top-rated products and the most purchased products within each category.
- Discount-dependent products were identified based on the percentage of discounted purchases.
- Revenue was analyzed across different age groups, with the Young Adult group contributing the highest revenue in the analysis. :contentReference[oaicite:4]{index=4}
- Subscription and repeat-purchase behavior were analyzed to understand customer loyalty and engagement. :contentReference[oaicite:5]{index=5}
