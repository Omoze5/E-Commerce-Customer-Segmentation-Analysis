# E-Commerce Customer Segmentation Analysis
## Project Overview
ShopSmart Inc. is an e-commerce platform that sells a variety of products online. The company aims to optimize its website and enhance customer satisfaction by understanding customer behavior and preferences. To achieve this goal, ShopSmart Inc. plans to analyze the data collected from its website to gain insights into customer interactions, purchasing patterns, and product preferences.
## Project Objective 
Project Objective: The objective of this project is to utilize data from ShopSmart Inc.'s website to understand customer behavior and preferences. By analyzing the data, the company aims to:
1. Segment customers based on their preferences, geographic location, and purchasing behavior.
2. Enhance website usability and user experience based on insights gained from customer interactions.
3. Optimize product offerings and marketing strategies to improve customer satisfaction and retention.
## Data Source
The data for this project was sourced from ShopSmart Inc.'s website and will include various attributes such as customer IDs, device IDs, transaction details, product information, and timestamps of customer interactions, its a 5 datasets from different tables, the first task is to merge the datasets, clean and wrangle the dataset, engineer new features from event data.
## Data Cleaning/Preparation
*  The first task was to merge the 5 datasets
*  There was no missing values in the dataset after merging
*  There was no duplicates and redundant columns were dropped
*  New features like event_type, total_amount was generated from the existing columns
*  The event_date and checkout time were all converted to the datatime module.
*  Outliers was detected in the price column and also replaced by the median.
## Exploratory Data Analysis
Questions to be answered using EDA in this project are:

a.     **Visit Frequency**:

How often does this customer visit the website, based on the provided data?

Can you identify any patterns or trends in the customer's visit frequency?

b. 	**Location Analysis**:

What is the customer's location based on the provided data?

How might the customer's location influence their purchasing behavior?

c.  	**Overall Purchase Behavior**:

Based on the data provided, what insights can you draw about this customer's overall behavior on the website?

How might these insights inform marketing strategies or personalized recommendations for this customer?
