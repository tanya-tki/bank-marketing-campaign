# Analyzing Bank Customer Data for Better Term Deposit Campaign
Getting to Know Our Customers: Insights for Better Campaign Marketing

By: Tanyaluck Kanai
<br>Project Status: On going
<br>Date: 20 March 2024
<br>Tools: Python, Tableau

For a concise overview of the insights and strategic implications derived from this project, please [click here](https://public.tableau.com/app/profile/tanyaluck.kanai/viz/AnalyzingBankMarketingCampaigns/Demographics?publish=yes) to view the Tableau Dashboard.

## Introduction
Banks often run marketing campaigns to encourage people to open term deposits, which are savings accounts that earn interest.
In this project, we dive into bank's customer data to uncover what drives customers to engage with term deposit products. Our goal is to leverage these insights to refine the company's marketing efforts, customize services, and strengthen customer relationships. By analyzing demographics, financial behaviors, and interaction patterns, we aim to identify actionable strategies that can enhance the bank's offerings and foster growth.

## Methodology 
In this project, we adopt a structured approach to data analysis known as the *Data Analysis Process*. Here's a breakdown of the steps we'll follow:

1. Ask : Defining our goals and the questions we aim to answer with our analysis.
2. Prepare: Gathering our dataset from Kaggle and ensuring it's ready for analysis.
3. Process: Using Python to clean and preprocess our data, making it suitable for detailed examination.
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

## 3. Process
Data processing is to find various inaccuracies, errors, inconsistencies in the data and get rid of them so that our primary business problem is not affected.

## 4. Analyze

In the analyze phase of our project, we dive deep down into our dataset to uncover the underlying relationships, trends, and patterns that are essential to addressing our business problem.

Our analysis is divided into two parts: *Customers base overview* and *Subscribers analysis*

## 5. Share

The insights and patterns discovered through our analysis have been transformed into interactive and visually engaging representations. Our Tableau dashboard provides a comprehensive view of the demographic profiles, financial behaviors, and contact engagements of our customers, enabling stakeholders to easily grasp the nuances of the data. To see the visualization of our findings, please check out the dashboard by following this link: [View Dashboard](https://public.tableau.com/app/profile/tanyaluck.kanai/viz/AnalyzingBankMarketingCampaigns/Demographics?publish=yes)


## 6. Act

Upon analyzing the data, several actionable strategies emerge to enhance the bank's marketing campaigns for term deposits:

Targeted Marketing Approaches: Tailor marketing campaigns to specific demographic and financial profiles that have shown higher propensity for subscription. For instance, focus on married individuals with tertiary education and management roles who have demonstrated a higher subscription rate.

Optimization of Contact Strategy: Adjust the frequency of campaign contacts to avoid customer fatigue. Our analysis indicates that the highest subscription rates occur at lower contact frequencies, specifically in the early stages of customer engagement.

Seasonal Timing: Leverage the insights on timing to maximize engagement. For instance, increase marketing efforts during early months and specific periods like March and December, where subscription rates are notably higher.

Financial Product Customization: Develop customized financial products that cater to the needs of different customer segments identified in the analysis, such as offering more attractive terms on deposits to high-balance holders or simplified application processes for younger, tech-savvy customers.

Continuous Monitoring and Adjustment: Implement a feedback loop to continuously monitor the effectiveness of these strategies and make adjustments based on real-time data and evolving market conditions.
