<h2 align="center">
   Flipkart Dataset Findings
 </h2>

   ![image](https://github.com/TendaiPhikiso/Flipkart-Dataset-Findings/assets/57633068/a34a5855-26f1-4b7f-a0e8-75f69a341df9)
   
## Introduction
Exploring Flipkart's product dataset, our aim is to identify patterns and trends. Following a comprehensive cleanup of the dataset, we've discovered important metrics that provide valuable insights. 
## Data Description 
#### Source of the Dataset

- The dataset used in this analysis is sourced from Kaggle.
- Data used from this analysis was collected in 2021

#### Structure and Format

- The dataset is presented in Excel.
- It consists of 393,120 rows and 14 columns.
- Currency used is ₹ Indian Rupee

#### Variables and Features
The cleaned dataset includes the following key variables and features:
<details>
<summary>
Click to view key variables
</summary>

1. **product_id**: Identifier assigned to each unique product in the dataset.
2. **actual_price**: The original price of the product before any discounts.
3. **average_rating**: The average customer rating based on reviews for the product.
4. **category**: The primary grouping/type that defines the product.
5. **discount**: The reduction percentage applied to the product's original price.
6. **out_of_stock**: Indicates whether the product is currently unavailable for purchase.
7. **seller**: The Individual selling the product.
8. **selling_price**: The current price at which the product is being offered for sale.
9. **sub_category**: More detailed classification within the main category, providing additional product details.
10. **brand**: The brand associated with the product.

</details>


## Problem Statement
In the context of the given dataset there is a need to conduct a comprehensive data analysis to derive  insights. The analysis will focus on understanding the pricing dynamics, stock availability, seller performance, and the impact of discounts on both product and subcategory ratings. By addressing these questions, we aim to uncover patterns, trends, and relationships within the dataset, providing valuable insights to inform business decisions and strategies.

## Case Study Questions 
**Price Metrices:**

1. What is the average actual/selling price?
3. what are the minimum and maximum actual/selling prices?

**Products:**

1. How many products are in & out of stock?
2. What's the priciest,  top 10 products in the dataset?

**Seller:**

1. By rating who are Flipkarts top sellers?
2. Based on the top 5 sellers, what brands do they sell?
3. What is the distribution of discount percentages offered by sellers?

**Categories vs Subcategories** 

1. By rating, which categories are performing?
2. By rating, which subcategories are performing?
3. What's the distribution of out of stock products
between categories and sub-categories?

**Discount:**

1. What's the most discounted category/ Subcategory?
2. Do you think the discount is responsible for the rating (based on products)? | Analyze the correlation between discount percentages and average ratings.
3. Do you think the discount is responsible for the rating (sub-categories)?
