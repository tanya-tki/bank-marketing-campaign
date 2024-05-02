# Analyzing Bank Customer Data for Better Term Deposit Campaign
Getting to Know Our Customers: Insights for Better Campaign Marketing

By: Tanyaluck Kanai
<br>Project Status: On going
<br>Date: 20 March 2024
<br>Tools: Python, Tableau

For a concise overview of the insights and strategic implications derived from this project, please [click here](https://public.tableau.com/app/profile/tanyaluck.kanai/viz/AnalyzingBankMarketingCampaigns/Demographics?publish=yes) to view the Tableau Dashboard.

## Table of Contents
[Introduction](#introduction)
<br>[Methodology](#methodology)
1. [Ask](#1-ask)
2. [Prepare](#2-prepare)
3. [Process (Data Cleaning)](#3-process-data-cleaning)
4. [Analyze](#4-analyze)
5. [Share](#5-share)
6. [Act](#6-act)

## Introduction
Banks often run marketing campaigns to encourage people to open term deposits, which are savings accounts that earn interest.
In this project, we dive into bank's customer data to uncover what drives customers to engage with term deposit products. Our goal is to leverage these insights to refine the company's marketing efforts, customize services, and strengthen customer relationships. By analyzing demographics, financial behaviors, and interaction patterns, we aim to identify actionable strategies that can enhance the bank's offerings and foster growth.

## Methodology 
In this project, we adopt a structured approach to data analysis known as the *Data Analysis Process*. Here's a breakdown of the steps we'll follow:

1. Ask : Defining our goals and the questions we aim to answer with our analysis.
2. Prepare: Gathering our dataset from Kaggle and ensuring it's ready for analysis.
3. Process (Data Cleaning): Using Python to clean and preprocess our data, making it suitable for detailed examination.
4. Analyze: Delving into the data to uncover patterns, trends, and insights that answer our initial questions.
5. Share: Visualizing our findings with Tableau, crafting a compelling narrative that conveys the story behind the data.
6. Act: Drawing conclusions and recommending actions based on our analysis to inform decision-making and strategy.# bank-marketing-campaign

## 1. Ask

**Business Objective**

The primary aim of this project is to enhance the effectiveness of the bank's marketing strategy for term deposit campaigns by identifying factors that influence customers' decisions to subscribe to term deposits. Understanding these factors will allow the bank to target the right customers more effectively and allocate resources more efficiently.

**Questions Driving the Analysis**

- Who subscribes?: Who are the customers that subscribe to term deposits (demographics, financial behavior, etc.?
- When do they subscribe?: Is there a pattern in terms of timing or customer lifecycle stage that influences subscription rates?
- How can we increase subscriptions?: Based on the characteristics of current subscribers, how can the bank tailor its marketing campaigns to convert non-subscribers?

## 2. Prepare

### About the Dataset
Our project uses a dataset from Kaggle that contains detailed information on bank customers and their responses to term deposit campaigns. It includes demographic details, financial data, and records of interactions with marketing efforts. This dataset is ideal for analyzing customer behavior and improving our banking services.

Please [click here](https://www.kaggle.com/datasets/seanangelonathanael/bank-target-marketing/data) to visit the dataset webpage on Kaggle.

### Dataset Variables Explanation
- age: Customer's age.
- job: Customer's occupation.
- marital: Customer's marital status.
- education: Customer's level of education.
- default: Whether the customer has credit in default.
- balance: Customer's average yearly balance.
- housing: Whether the customer has a housing loan.
- loan: Whether the customer has a personal loan.
- contact: Type of communication contact with the customer.
- day: Last contact day of the month.
- month: Last contact month of the year.
- duration: Last contact duration in seconds.
- campaign: Number of contacts performed during this campaign for the customer.
- pdays: Number of days since the customer was last contacted from a previous campaign.
- previous: Number of contacts performed before this campaign for the customer.
- poutcome: Outcome of the previous marketing campaign.
- deposit: Whether the customer subscribed to a term deposit.

## 3. Process (Data Cleaning)
Data processing is to find various inaccuracies, errors, inconsistencies in the data and get rid of them so that our primary business problem is not affected. 

For a detailed look at the Python code used to clean the data, please [click here to view the data cleaning process.](https://github.com/tanya-tki/bank-marketing-campaign/blob/main/data_cleaning_steps.ipynb)

## 4. Analyze

In the analyze phase of our project, we dive deep down into our dataset to uncover the underlying relationships, trends, and patterns that are essential to addressing our business problem.

Our analysis is divided into two parts: *Customers base overview* and *Subscribers analysis*

In the analyze phase of our project, we delve deep into our dataset to uncover the underlying relationships, trends, and patterns that are essential to addressing our business problem. This detailed examination is structured into two main parts:

### Part 1: Customers Base Overview
In this segment, we explore the general characteristics of our entire customer base. By analyzing demographic details, financial behaviors, and interaction patterns, we aim to establish a comprehensive understanding of our typical customer. This overview provides the foundational insights necessary for targeted marketing and product development.

### Part 2: Subscribers Analysis
The second part of our analysis focuses on the customers who have responded positively to term deposit campaigns — the subscribers. Here, we investigate the specific traits and behaviors that distinguish subscribers from non-subscribers, aiming to identify factors that influence their decision to engage with our term deposit products.

For an in-depth view of the Python code used to analyze these data segments, please [click here to view Customer Base Overview](https://github.com/tanya-tki/bank-marketing-campaign/blob/main/analyze_part_1_customerbase_overview.ipynb) and [click here to view Subscribers Analysis process.](https://github.com/tanya-tki/bank-marketing-campaign/blob/main/analyze_part_2_subscribers.ipynb)

## 5. Share

The insights and patterns discovered through our analysis have been transformed into interactive and visually engaging representations. Our Tableau dashboard provides a comprehensive view of the demographic profiles, financial behaviors, and contact engagements of our customers, enabling stakeholders to easily grasp the nuances of the data. To see the visualization of our findings, please check out the dashboard by following this link: [View Dashboard](https://public.tableau.com/app/profile/tanyaluck.kanai/viz/AnalyzingBankMarketingCampaigns/Demographics?publish=yes)


## 6. Act
Upon analyzing the data, several actionable strategies emerge to enhance the bank's marketing campaigns for term deposits:

**Refined Demographic Targeting:**
  - **Focus on High-Performing Demographics:** Continue to target married individuals in management, technician, and blue-collar roles, as these demographics have shown the highest subscription rates. Additionally, strategies should also focus on younger demographics (30-39 age group) which are active in the banking system and have demonstrated significant engagement.
  - **Tailored Campaigns for Retirees and Students:** These groups show high responsiveness to term deposits despite fewer contacts. Tailored products and marketing messages that address their specific financial needs and lifestyles could increase conversions.

**Optimization of Contact Strategies:**
  - **Limit Contact Frequency:** Analysis shows that the effectiveness of the marketing campaigns decreases with increased contact frequency. Limiting contact to 1-5 interactions per campaign cycle may enhance customer receptiveness and subscription rates.
  - **Adjust Contact Timing:** Leverage the insights on optimal contact times — especially targeting mid-February, all times in March, mid-September and late-October to early-December. These periods have been identified as having higher subscription rates, suggesting customers are more receptive to banking products during these times.

**Financial Product Customization:**
  - **Develop Segmented Financial Products:** Design term deposit products that appeal specifically to high balance customers who show a greater likelihood of subscription. Consider features like higher interest rates for larger deposits or loyalty benefits for long-term savings.

**Leverage Engagement History:**
  - **Re-engage Past Contacts:** Customers previously contacted 51-100 days before a campaign show a peak in subscription rates. Implement a strategy to re-engage these customers, potentially catching them at a more receptive moment. Also, initiate special re-engagement campaigns designed for clients who may have been out of touch for more than a year since subscription rate is rebound.
  - **Focus on Previously Successful Customers:** Customers who have successfully subscribed in the past or had positive outcomes from previous engagements should be prioritized for new term deposit offers.
    
**Campaign Adjustment Based on Performance Metrics:**
  - **Review and Adapt Based on Campaign Data:** Regularly review the campaign metrics such as the number of contacts made, call duration, and previous engagement history. Use this data to continuously refine and optimize the campaign strategies.

**Strategic Use of Data Insights:**
  - **Implement Advanced Analytics:** Use the insights from this analysis to further refine marketing strategies. This should include predictive analytics to forecast potential subscriber behavior and refine targeting criteria based on emerging trends.

By implementing these strategies, the bank can not only improve the effectiveness of its term deposit campaigns but also enhance customer engagement and satisfaction, leading to increased customer loyalty and revenue growth.
