# E-commerce-_customer_behaviour-analysiss
 
 Studying how customers interact with a brand and make purchasing decisions online, 
 helping businesses understand preferences, optimise strategies, and improve customer experience. 

E-Commerce Multi-Analysis

In this e-commerce project, I worked on various analyses, such as customer behaviour analysis, 
Churn Analysis, Sales Forecasting, and Revenue Analysis.

Work flow

1, Preprocess

1.1, Understanding the data

1.2, checking the missing value

1.3, checking duplicate

1.4, Check for Data Types Consistency

Installation

!pip install ydata-profiling

2. Exploratory Data Analysis (EDA)

It is a method used by data scientists to understand the characteristics of a dataset 
and identify patterns, anomalies, and relationships within it.

2.1, Distribution Plots (KDE)

2.2, Count Plots for Categorical Variables

2.3, Understanding Trends & Patterns:- Customer Demographics, Top Product Categories, Product Pricing, 
Purchase Trends, Quantity Purchased, Total Purchase Amount, Payment Methods, Returns Analysis, Age versus Spending, Correlations and High-Value Customers.

2.4, A Time Series plot: It can show sales trends over time. Total Purchase Amount and Monthly Sales Trend plot.

3. Customer Behaviour Analysis

It is the process of studying and understanding how customers interact with a business, 
including their purchasing habits, preferences, and motivations.

3.1 Basic Metrics (total spend, number of purchases) Who are your most valuable customers?

3.2 RFM Analysis (Regency, Frequency, Monetary) Group customers by loyalty/engagement.

3.3 Customer Segmentation Personalised marketing strategies.

4. Churn Analysis

It is the process of examining why customers stop using a product or service, often referred to as customer attrition. 

It involves analysing data on customer behaviour, usage patterns, and feedback to identify the factors leading to churn.

4.1 Predict churn risks: Find customers likely to leave. Build a model that predicts if a customer is likely to churn (stop purchasing).

4.2 Customers who haven't purchased in a long time (high Regency).

4.3 Build Prediction Model: a simple Logistic Regression model and Predict Individual Churn Probabilities.

4.4 Get Risk Scores:- Predict the probability of churn for each customer. 
Plot Risk Distribution: how risky your whole customer base is.
Show Top Risk Customers:-Simple Data Frame of top customers.
Action Plan Suggestion

Installation
!pip install streamlit

4.5 Churn Risk Web App using Streamlit

Part Feature

•	Upload customer data (CSV)

•	 Predict churn risk in real-time

•	Show Top Risk Customers

•	Show Risk Distribution Chart

•	Show Suggested Action Plans

5. Sales Forecasting

It is the process of predicting a company's future sales revenue over a specific period, typically a month, quarter, or year.

5.1 Model: 1, Customer Lifetime Value (CLV):-Regency, Frequency, Monetary Value (This is called RFM Analysis), RFM plus Regression for CLV. 

•	By using RFM, predict CLV using an XGBoost model.

•	Regency = Days since last purchase

•	Frequency = Number of purchases

•	Monetary Value = Average purchase amount

•	Sort and get the Top 10 Customers Predicted Customer Lifetime Value (CLV) and take action.

5.2 Sales Forecasting: a time series forecasting approach because sales = time-based data. 
I used ARIMA and the Prophet Model. First Train and Predict future sales.

Installations

!pip install-- upgrade pmdarima

! pip install prophet

5.2.1 ARIMA, which stands for Autoregressive Integrated Moving Average, is a popular statistical model used for time series forecasting.
Forecasting

•	Daily forecast 

•	Monthly forecast 

•	Export to CSV 

•	I forecast the next 90 days.

5.2.2 Prophet is an open-source forecasting tool developed by Facebook's Core Data Science team. 

The model uses an additive approach, incorporating non-linear trends with yearly, weekly, and daily seasonality, as well as holiday effects.

•	seasonality (weekly, yearly)

•	Show holiday effects

•	Plot components separately (trends + seasonality)

6, Revenue Analysis

Revenue analysis is the process of examining a company's income sources to understand its financial health and identify areas for growth.

6.1 General Revenue Overview

•	Total Revenue: We'll sum up the Total Purchase Amount.

•	Average Order Value (AOV) This is the average revenue per purchase.

•	Total Orders: This equals the number of rows (transactions).

•	Top 5 Product Categories by Revenue

•	Revenue Trends by Year (based on Purchase Date)

6.2 Advanced Revenue Trend Visualisations

•	Monthly Revenue Trend: Visualise how revenue changes month-by-month.

•	 Revenue by Customer: Find top-spending customers.

•	Return Impact on Revenue: How much revenue is lost to returns?

•	Which categories/customers have the highest return rate?

•	Revenue by Age Group or Gender: Demographic breakdown of who spends more.

6.3, Monthly trends or Customer Segments

Revenue by Customer Segment, age and gender

