# Fresh-Cart-Ad-Spend-Analysis

## Overview

This project aims to optimize digital advertising spend for Fresh Cart, an online grocery store, by leveraging business intelligence tools like Power BI. The analysis focuses on understanding ad campaign performance across various platforms (Facebook, Instagram, YouTube, Twitter, and Google Ads) and providing actionable insights to enhance Return on Ad Spend (ROAS).

![image](https://github.com/user-attachments/assets/0942048f-48d1-4840-b328-c998d0b12f58)


## Project Structure

- **Data**: Contains the raw ad campaign data provided by Fresh Cart's marketing team.
- **Power BI Reports**: Includes the Power BI report file used for the analysis.
- **Documentation**: This `README.md` file and other supporting documentation.

## Data Description

![Ad  data excel](https://github.com/user-attachments/assets/aeae4dff-0c3f-4062-bafc-39ada4976c25)

The dataset includes the following columns:

- **CampaignID**: Unique Identifier for each campaign.
- **Platform**: The platform where the ad was shown (e.g., Google Ads, Facebook).
- **AdDuration**: Duration of the ad campaign in weeks.
- **Cost**: Amount spent on the ad.
- **Impressions**: Number of times the ad was shown.
- **Clicks**: Number of times the ad was clicked.
- **Conversions**: Number of actions taken as a result of the ad.
- **ConversionValue**: Total sales value generated from the ad.
- **CPC**: Cost per click.

## Methodology

### 1. **Data Cleaning and Transformation**

![ad power query](https://github.com/user-attachments/assets/31a1fff1-ef14-4e8f-a74a-5feab47abaa6)

- **Step 1**: Clean and transform the raw data using Power Query in Power BI. Ensure all fields are correctly formatted and assigned appropriate data types.
- **Step 2**: Eliminate empty rows/columns and consolidate date entries into a single column.
- **Step 3**: Create an index column for primary keys in dimension tables.
- **Step 4**: Create a Calendar Table for Time intelligence Using DAX formula

 ![ad date table](https://github.com/user-attachments/assets/b8a2716a-5974-4c65-8a6e-b5512991e815)
 
### 2. **Data Modelling**

![Ad star schema](https://github.com/user-attachments/assets/122cb9a9-c137-4e90-8092-40195d63a72b)

- **Step 1**: Identify and categorize fields into dimension and fact tables.
- **Step 2**: Establish hierarchies and define granularity.
- **Step 3**: Create a star schema data model with fact tables for metrics and dimension tables for categorical data.

### 3. **Metric Calculation**

![ad kpi](https://github.com/user-attachments/assets/3a1c6df0-6468-4a5d-a5ce-07d99931de56)

- **Step 1**: Calculate key performance indicators (KPIs) such as `Conversion Rate`, `Cost per Conversion`, and `ROAS` using DAX in Power BI.
- **Step 2**: Implement calculated columns and measures to generate insights.

### 4. **Platform Comparison**
![Ad platformx](https://github.com/user-attachments/assets/24231f95-e6d4-4f8c-99e2-50c84e6fe681)

- **Step 1**: Compare the performance of different advertising platforms using visualizations in Power BI.
- **Step 2**: Identify the most effective channels for Fresh Cart’s campaigns.

### 5. **Campaign Analysis**
![Ad campaign](https://github.com/user-attachments/assets/ad0dd085-ae51-4e30-ba59-fd9a25693cba)

- **Step 1**: Conduct a deep dive into individual campaigns to uncover insights into high-performing ads.
- **Step 2**: Use trend line charts and matrix tables to track performance over time.

### 6. **Insights and Recommendations**

- **Step 1**: Synthesize findings to provide actionable insights.
- **Step 2**: Formulate strategic recommendations for optimizing ad spend.

## Key Insights

- **Facebook vs. Instagram**: Facebook outperforms Instagram in sales revenue, cost per conversion, and ROAS.
- **YouTube vs. Twitter**: YouTube delivers the highest ROAS and the lowest cost per conversion.
- **Google Ads**: Underperforms in comparison, requiring strategic reassessment.

## Recommendations

- **Facebook**: Increase ad spend, optimize targeting, and extend successful campaigns.
- **Instagram**: Refine targeting to lower costs and expand campaigns in high-performing regions.
- **YouTube**: Boost investment and analyze successful content strategies.
- **Twitter**: Optimize targeting and content, focusing on top-performing campaigns.
- **Google Ads**: Reevaluate strategy and identify underperforming campaigns for optimization.

## Conclusion

By following this methodology, you can replicate the analysis and gain insights into ad campaign performance, helping to optimize ad spend and enhance overall effectiveness. The approach can be adapted for other e-commerce platforms facing similar challenges.

## Resources

- **Interactive Power BI Report**: [Click here to View](https://app.powerbi.com/view?r=eyJrIjoiMDg5MzY0OGYtOTg5Ni00Y2FkLWIzYmQtMGVjMTZjMWNmOGY3IiwidCI6IjNlMDBmYTQzLWMyMzktNDQ4Ni1hOTM1LTU5MmI0ZjRkZGU4MSJ9)
- **Dataset**: [Download here](https://github.com/AbdurRahman-Olaniyan/Fresh-Cart-Ad-Spend-Analysis/edit/main/Data)

You can also view my detailed article where the project is well documented: [Click here](https://medium.com/@AbdurRahmanOlaniyan/precision-marketing-in-e-commerce-leveraging-business-intelligence-for-enhanced-ad-spend-2e55e76d8fac).


## Contact

For any questions or further information, feel free to reach out on [LinkedIn](https://www.linkedin.com/in/abdur-rahman-olaniyan/) or [Twitter](X.com/RahmanOlaniyan).
