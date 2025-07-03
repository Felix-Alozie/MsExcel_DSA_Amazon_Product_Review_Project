# 🛒 Amazon Product Review Analysis

## Project Overview

This project explores and analyzes product and customer review data from Amazon to uncover actionable insights for product optimization, marketing strategy, and customer engagement. Conducted as part of the Data Science Accelerator (DSA) final project, the analysis simulates the responsibilities of a Junior Data Analyst at **RetailTech Insights**, an e-commerce analytics company serving sellers on platforms like Amazon.

Through Excel-based data analysis techniques—including pivot tables, calculated fields, and data visualization—the project answers strategic questions on pricing, discount behavior, customer ratings, and revenue opportunities.

## Data Source

- **Source:** [DSA Canvas LMS Platform](https://canvas.instructure.com/courses/11955369/files/folder/DSA%20Capstone%20Project%20Files)
- **Dataset Format:** Microsoft Excel (.xlsx)
- **Context:** Product listing and customer reviews from Amazon’s e-commerce platform
- **Data Fields:** Product ID, Category, Actual Price, Discounted Price, Ratings, Rating Count, and Discount %

## Tools Used

- **Microsoft Excel**
  - Pivot Tables
  - Calculated Columns
  - Trim: Triming Category using the formular =TRIM(LEFT(C2, FIND("|", C2 & "|") - 1))
  - Conditional Formatting
  - Charts (Bar, Pie, Histogram)

## Exploratory Data Analysis

The following business questions were addressed during the analysis:

1. **Average Discount % by Product Category**
2. **Number of Products per Category**
3. **Total Reviews per Category**
4. **Products with Highest Average Ratings**
5. **Average Actual Price vs Discounted Price by Category**
6. **Products with Highest Number of Reviews**
7. **Products with Discount ≥ 50%**
8. **Distribution of Product Ratings**
9. **Total Potential Revenue by Category**
10. **Unique Products by Price Range**
11. **Rating vs Discount Analysis**
12. **Products with <1,000 Reviews**
13. **Categories with Highest Discounts**
14. **Top 5 Products by Rating × Review Count**

## DashBoard
<img width="929" alt="Amazon Dashboard" src="https://github.com/user-attachments/assets/ec5fdb42-b37d-47b4-8d03-9d4e07e22774" />

1. The Electronics category dominates in revenue generation with over ₦88,021 million, followed by Computers & Accessories and Health & Personal Care. These categories should be prioritized for inventory optimization, cross-promotions, and strategic advertising. Sales teams can target upselling and bundling strategies around these top-performing categories to maximize revenue.
2. The overall average product rating is above 4.1, indicating strong customer satisfaction. However, most ratings cluster between 3.8 and 4.6, suggesting there's room to improve product quality and customer experience, especially for items rated below 3.5. Marketing and support teams should investigate low-rated items to resolve product flaws or clarify product descriptions.
3. There are 653 products with discounts of 50% or more, yet a noticeable decline in product ratings at these high-discount points suggests that steep discounts may not always correlate with customer satisfaction. Management should evaluate whether excessive price cuts are compromising product perception, and implement smarter markdowns tied to quality assurance.
4. With over 1,465 unique products, the catalog shows impressive breadth. However, a significant 301 products have fewer than 1,000 reviews, which may point to underperforming listings or limited visibility. These items could benefit from targeted campaigns, influencer reviews, or enhanced product descriptions to boost engagement and conversions.
5. The dashboard reveals a ₹200–₹500 price range contains the majority of product listings, and many top-reviewed products fall within this mid-range bracket. Focusing on this pricing tier can offer a sweet spot for profitability and customer acquisition. The top 5 rated and reviewed products also serve as models for replicating success. The teams should study their positioning, presentation, and fulfillment practices.

