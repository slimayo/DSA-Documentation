# DSA_Capstone_Excel_Project
Documentation of DSA Excel Project

## Table of Contents
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tool](#tool)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results](#results)
- [Findings](#findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)

### Project Overview.

This data analysis project aims to provide insights that can guide in product improvement, marketing strategies and customer engagement through given product analysis and customer review data.

### Data Source.

The primary dataset used for this analysis is the "Amazon case study.xlsx" file, provided by DSA team.

### Tool.

Excel 
- [Download here](https://www.microsoft.com/en-us/microsoft-365/download-office?msockid=0739cabe1905633c0ca7de41184262b6)

### Data Cleaning.

In the initial data preparation phase, I performed the following tasks:

1. Data loading and inspection.
2. Handling missing values.
3. Creating necessary columns through the provided data from the dataset.
4. Data cleaning and formatting.

### Exploratory Data Analysis.

EDA involved exploring the dataset answer some major questions such as:

- What is the average discount percentage by product category?
- How many products are listed under each category?
- What is the total number of reviews per category?
- Which products have the highest average ratings?
- What is the average actual price vs the discounted price by category?
- Which products have the highest number of reviews? 
 And so on.....

### Data Analysis.

Did it with the use of some calculated columns and the use of pivot table.

### Results.
1. What is the average discount percentage by product category? Answer is on the Pivot table file attached
2. How many products are listed under each category? Answer is on the Pivot table file attached
3. What is the total number of reviews per category? Answer is on the Pivot table file attached
4. Which products have the highest average ratings? REDTECH, Syncwire, Swiffer, Oratech, Instant, FIGMENT, Campfire, Multifunctional, VRPRIME, Melbon, Aquadpure, 10k, Zuvexa, Spigen, Sujata, Cafe, Fujifilm, Scarters, Gadgetronics, Noise_Colorfit, Goldmedal, Redragon, Homeistic, Seagate, Cuzor, SupCares, Kyosei, Aqua, !!1000, WANBO
<img width="462" height="871" alt="image" src="https://github.com/user-attachments/assets/4e495e83-2dcb-4da8-9c3e-aa4b04f5ec8e" />


5. What is the average actual price vs the discounted price by category? Answer is on the Pivot table file attached
6. Which products have the highest number of reviews? Answer is on the Pivot table file attached
7. How many products have a discount of 50% or more? Answer is on the Pivot table file attached
8. What is the distribution of product ratings (e.g., how many products are rated 3.0, 
    4.0, etc.)? Answer is on the Pivot table file attached
9. What is the total potential revenue (actual_price × rating_count) by category? Answer is on the Pivot table file attached
10. What is the number of unique products per price range bucket (e.g., <₹200, 
    ₹200–₹500, >₹500)? Answer is on the Pivot table file attached
11. How does the rating relate to the level of discount? Answer is on the Pivot table file attached
12. How many products have fewer than 1,000 reviews? Answer is 1464 Products.
13. Which categories have products with the highest discounts? Electronics, Home & Kitchen and Computer & Accessories
14. Identify the top 5 products in terms of rating and number of reviews combined. In terms of Rating, boAt, AmazonBasics,        Redmi, SanDisk, TP-Link are top 5 and boAt, Samsung, Fire-Boltt, AmazonBasics, Redmi are top 5 in terms of reviews.

### Findings.

The analysis results are summarized as follows:

1. We know the satisfactory level of customer over our products.
2. We get to know particular products we need to improve on through the rating and reviews from customer.
3. It shows how discount rate can affect product demand.
4. We know which of our products move most.
5. We discover which of our products are most likely to first sell out due to demand rate.

### Recommendations.

Based on the analysis, we recommend the following actions:

- Invest more into marketing and promotions more on products in Electronics Category.
- Give more discount on products in Toys & Games Category to encourage more people buying.

### Limitations.

- Had to split the category into 5 differrent columns so as to be able to arrive at having the real category name needed for    analysis
- Had to count the reviews using comma as delimeter for each review.
