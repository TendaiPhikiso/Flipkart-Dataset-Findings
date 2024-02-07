<h2 align="center">
   Flipkart Dataset Findings
 </h2>
 
  ![image](https://github.com/TendaiPhikiso/Flipkart-Dataset-Findings/blob/main/Header.png)


   
# Introduction
This report delves into the findings from the Flipkart's product dataset. Following a thorough cleanup, we've uncovered noteworthy observations. Our analysis focused on understanding various price metrics, providing a comprehensive view of the seller and actual prices on the platform, examining stock availability, evaluating how sellers and brands are performing, and investigating the impact of discounts on both
product and subcategory ratings. This report aims to present a clear and comprehensive overview of these dynamics. 

#### Report: [Click to View PDF](https://github.com/TendaiPhikiso/Flipkart-Dataset-Findings/blob/main/Flipkarts-DataFindings.pdf)

# Data Description 
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


# Case Study Questions 

Delving into the specifics of our product dataset, a noteworthy observation is the presence of 28,080 unique products.

There are 498 distinct sellers & 346 brands contributing to the platform's diverse product offerings. The dataset comprises a total of 4 categories and 22 subcategories, reflecting the comprehensive range of offerings available to Flipkart’s users.

## Price Metrics Analysis:

### 1. What is the average actual/selling price?

To identify the benchmark of the typical cost of products within the Flipkart dataset, we carried out the Avg of actual product price and the selling price

| Average of Actual Price | Average of Selling Price |
| ----------------------- | ------------------------ |
|        ₹ 1,415.25       |          ₹ 705.58        |

### 2. What are the minimum and maximum actual/selling prices?

The range between minimum and maximum prices for both actual and selling prices provides insights into the diversity of pricing within the dataset.
   
|  Minimum Actual Price   | Minimum  of Selling Price|
| ----------------------- | ------------------------ |
|         ₹ 150.00        |         ₹ 99.00          |

|  Maximum Actual Price   | Maximum  of Selling Price|
| ----------------------- | ------------------------ |
|       ₹ 12,999          |         ₹ 7,999          |


## **Product Analysis**

### 1. How many products are in & out of stock?
   
| Out of stock products      |    1,644     | 5.85%  |
| -------------------------- | ------------ | ------ |
| In stock products          |    26,436    | 94.15% |

Analysing the inventory status of Flipkart's product catalog, we found that out of 28,080 products, 5.85% items are currently out of stock. This indicates a relatively small portion of products temporarily 
unavailable for purchase. On the contrary, a significant majority of Flipkart's inventory, 94.15%, are currently in stock. The balanced distribution between in-stock and out-of-stock items showcases a healthy inventory management approach, catering to the diverse needs of Flipkart's customers.

### 2. What's the priciest,  top 5 products in the dataset?

<p align="left"> 
    <img src="https://github.com/TendaiPhikiso/Flipkart-Dataset-Findings/assets/57633068/a9ccac9e-d5c0-456d-8441-60534f16cc35" alt="Image">
</p>

<p align="left">
  <img src="https://github.com/TendaiPhikiso/Flipkart-Dataset-Findings/assets/57633068/4522e2ba-2331-4a5e-93bf-5519ecb0f90e" width="210" height="300" alt="Image Alt Text" />
  <img src="https://github.com/TendaiPhikiso/Flipkart-Dataset-Findings/assets/57633068/63813536-73e9-4e92-9bda-3f8c71c5b35e" width="150" height="300"alt="Image Alt Text" />
  <img src="https://github.com/TendaiPhikiso/Flipkart-Dataset-Findings/assets/57633068/98d9930b-6fbb-4556-9300-ae4488ec7247" width="210" height="300"alt="Image Alt Text" />
  <img src="https://github.com/TendaiPhikiso/Flipkart-Dataset-Findings/assets/57633068/37a30105-bcab-4080-84eb-d7c9864353af" width="150" height="300"alt="Image Alt Text" />
   <img src="https://github.com/TendaiPhikiso/Flipkart-Dataset-Findings/assets/57633068/570d62ef-8580-4200-9dce-f221dd25b31d" width="210" height="300"alt="Image Alt Text" />
</p>

All the top 5 priciest products in the dataset share the same price tag of ₹ 12,999. A noteworthy observation is the consistency in product types, with a focus on suits, jackets, and sweatshirts. This suggests that these high-priced items cater to a particular niche or demand for sophisticated and stylish men's apparel.

## **Brand Analysis**

### 1. By rating, which top 10 brands are performing?	
This analysis reveals the performance of top 10 brands based on weighted averages, combining factors like the number of products and average ratings. The weighted average allows for a fair evaluation, giving prominence to brands with a combination of high ratings and a substantial product presence.

In this context, Reebok emerges as the top performer, showcasing consistent excellence across a significant product range. Arbour closely follows in the second spot, demonstrating a commendable balance between quality and quantity. Notably, Keoti, despite having an average rating of 3.82, ranks sixth when considering the weighted average. This highlights the significance of the weighted average, which ensures that both ratings and the number of products contribute meaningfully to how top-performing brands are ranked.

![image](https://github.com/TendaiPhikiso/Flipkart-Dataset-Findings/assets/57633068/ed6e57e2-2b66-4d4e-b09f-1235e42f6f63)

### 2.Which top 10 brands have the highest product count?
 	 
![image](https://github.com/TendaiPhikiso/Flipkart-Dataset-Findings/assets/57633068/801b2ee9-cb65-4601-aa84-d35b29848cf2)

### 3. Create a table showcasing the average actual/selling prices for the top 15 brands that have the highest number of products in the dataset.

#### Actual(Product price)
![image](https://github.com/TendaiPhikiso/Flipkart-Dataset-Findings/assets/57633068/3c5dd501-6ccc-4f98-b704-d5b6fc5e04bd)

#### Selling price		
![image](https://github.com/TendaiPhikiso/Flipkart-Dataset-Findings/assets/57633068/dd7071df-9344-40ff-8a18-b7435ce7bb89)


## **Seller Analysis**

### 1. By rating who are Flipkarts top sellers?

Delving into Flipkart’s seller ratings, from our findings RETAILNET emerges as the top seller with an average rating of 4.11 across 1416 products, ARBOR closely follows with a 4.10 rating and 783 products. However, SANDSMARKETING ranks as a bottom seller with a lower 2.68 rating across 887 products, signaling potential challenges in customer satisfaction. 
 	 	
![image](https://github.com/TendaiPhikiso/Flipkart-Dataset-Findings/assets/57633068/fc281fc8-a03b-428a-97fa-0fcd342046cf)

### 2. Based on the top 5 sellers, what brands do they sell?

![image](https://github.com/TendaiPhikiso/Flipkart-Dataset-Findings/assets/57633068/147b7d81-fdfc-4d44-a337-b5cd838e26f4)


## Categories & Subcategories Analysis

### 1. By rating, which categories are performing?	 

While the average rating for Bags, Wallets & Belts is 4.13, indicating positive feedback, it's crucial to note the small sample size of only 41 products within this category. The analysis suggests that caution is needed when considering Bags, Wallets & Belts as the bestperforming category. In contrast, Clothing and Accessories, with 27,118 products, provides a much larger dataset for assessing customer preferences.

Weighted rating was carried out as it helped provide a balanced view of how well each product category is performing. By taking into account both the number of products and their average ratings, it gives a fair representation of the overall performance, considering not only the variety of products but also how satisfied customers are with them.

![image](https://github.com/TendaiPhikiso/Flipkart-Dataset-Findings/assets/57633068/d0f9e2c5-1a3b-4610-9234-d094b76a42af)

### 2. By rating, which subcategories are performing?

The weighted average rating for subcategories was conducted to offer a comprehensive evaluation of their performance. By considering both the quantity (number of products) and the quality (average rating), this assessment provides insights into the overall success of each subcategory. 

Notably, Topwear emerges as the top-performing subcategory, excelling in both the diversity of products and customer satisfaction.

![image](https://github.com/TendaiPhikiso/Flipkart-Dataset-Findings/assets/57633068/0ed28b81-7fb0-4724-9c90-cd0c30f05125)

### 3. What's the distribution of out of stock products between categories and sub-categories?
In the given dataset, out-of-stock products are found in two main categories: Clothing & Accessories and Footwear. 

The distribution of these out-of-stock products differs among subcategories, with the highest numbers in Topwear, followed by Clothing Accessories, Bottomwear & winter wear.

![image](https://github.com/TendaiPhikiso/Flipkart-Dataset-Findings/assets/57633068/780ab92c-ceb9-427d-87fe-9e9490ff38b4)


## Discount Analysis

### 1. What's the most discounted Subcategory?
**Most Discounted Subcategories**: Most Discounted Subcategories: Brand Trunk Bags, Wallets & Belts (74%): This subcategory has the highest average discount among all. 

Other highly discounted subcategories worth noting are Fabrics (66%), Roy Clothing and Accessories (65%), and SUNSHOPPING Bags, Wallets & Belts (63%).

![image](https://github.com/TendaiPhikiso/Flipkart-Dataset-Findings/assets/57633068/dfa7a8f2-b604-4454-be5f-4202db2ae804)


### 2. Do you think the discount is responsible for the rating (based on products)? | Analyse the correlation between discount percentages and average ratings.

In analysing the scatter plot, a negative relationship between product ratings and discounts is observed. The slope of the line indicates that as the discount increases, the rating tends to decrease.

This suggests that the discount does not necessarily have an influence on customers' rating of the product due to a high discount. On average, there is a slight tendency for higher ratings to be associated with slightly lower discounts.


![image](https://github.com/TendaiPhikiso/Flipkart-Dataset-Findings/assets/57633068/75303c7c-3e8e-42cb-b31b-c4a0c09f20b9)

## Conclusion 

In summary, our analysis highlights Retailnet and Arbor as top-rated sellers, along with Reebok and Arbour as leading brands. The standout subcategory is Topwear. 

Our analysis suggests that offering high discounts does not guarantee better product ratings. It is important to consider other factors such as product quality, sizing as they play a crucial role in customer satisfaction. 

Furthermore, our study reveals a trend where the priciest products are predominantly tailored to men's apparel. These insights provide valuable perspectives on seller and brand dynamics, subcategory performance, and the influential factors shaping customer ratings within the Flipkart platform.
