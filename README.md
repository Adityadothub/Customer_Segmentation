# 📊 Customer Segmentation Analysis using RFM & K-Means Clustering

---

# 🚀 Project Overview

Customer segmentation is one of the most important analytical techniques used by businesses to understand customer behavior, improve customer retention, optimize marketing strategies, and increase overall revenue generation.

This project focuses on analyzing customer purchasing behavior using **RFM (Recency, Frequency, Monetary)** analysis and **K-Means Clustering** to identify different categories of customers based on their purchasing patterns.

The dataset used in this project contains transactional retail data including:
- Customer purchase history
- Invoice details
- Product-level information
- Country-wise transactions
- Revenue generated from customer transactions

The project transforms raw transactional data into meaningful customer-level insights and applies machine learning techniques to segment customers into actionable business groups.

---

# ❓ Business Problem

Businesses often struggle to answer questions such as:

- Which customers generate the highest revenue?
- Which customers are becoming inactive?
- Which customer groups should be prioritized for retention?
- Which geographical regions contribute most to the business?
- How can businesses personalize marketing strategies based on customer behavior?

Without customer segmentation, businesses usually apply generalized strategies, which often lead to:
- Poor customer retention
- Inefficient marketing spending
- Reduced customer engagement
- Revenue loss from inactive customers

This project aims to solve these business problems using data-driven customer segmentation techniques.

---

# 🎯 Objective of the Project

The primary objectives of this project are:

✅ Understand customer purchasing behavior  
✅ Identify high-value and low-value customers  
✅ Analyze customer activity patterns  
✅ Perform customer segmentation using RFM metrics  
✅ Generate actionable business insights  
✅ Improve business decision-making through analytics  

---

# 📂 Dataset Information

The dataset contains online retail transaction data with the following features:

| Feature | Description |
|---|---|
| InvoiceNo | Unique invoice number |
| StockCode | Product/item code |
| Description | Product description |
| Quantity | Number of products purchased |
| InvoiceDate | Date of transaction |
| UnitPrice | Price per product |
| CustomerID | Unique customer identifier |
| Country | Customer country |

---

# 🧹 Data Cleaning & Preprocessing

Several preprocessing techniques were applied before analysis:

- Removed missing values
- Handled duplicate records
- Converted data types
- Created `Total_Price` feature
- Removed invalid transactions
- Converted transaction-level data into customer-level summarized data

The original dataset contained approximately **5 lakh transactional records**, which were transformed into summarized customer-level data consisting of **4372 unique customers**.

---

# 📈 Exploratory Data Analysis (EDA)

Exploratory Data Analysis was performed to understand:
- Customer purchasing patterns
- Revenue distribution
- Country-wise customer behavior
- Transaction frequency trends
- Distribution of RFM variables
- Revenue contribution by customers

The following visualizations were used:
- Histograms
- Scatter plots
- Revenue comparison charts
- Correlation analysis
- Distribution plots
- Elbow Method visualization

---

# 📊 Univariate Analysis

Univariate analysis was performed on:
- Recency
- Frequency
- Monetary

### Key Findings:
- All three variables were heavily right-skewed
- Monetary values contained significant outliers
- Majority of customers generated lower purchase frequency and lower spending
- A small group of customers contributed significantly higher revenue

---

# 📉 Bivariate Analysis

Bivariate analysis was conducted to identify relationships between RFM variables.

### Key Observations:
- Frequency and Monetary showed a strong positive relationship
- Customers purchasing more frequently tended to generate higher revenue
- Recency showed a negative relationship with Frequency and Monetary
- Recently active customers contributed more revenue compared to inactive customers

---

# 🌍 Country-wise Revenue Analysis

Country-level analysis revealed important geographical insights:

### Key Findings:
- The United Kingdom dominated both customer count and total revenue
- Some countries had fewer customers but significantly higher average customer spending
- The dataset showed strong geographical imbalance toward UK customers

This analysis highlighted the importance of studying both:
- Total revenue
- Average customer spending

---

# 🧠 RFM Analysis

The project used the RFM framework:

## 🔹 Recency
Measures how recently a customer made a purchase.

## 🔹 Frequency
Measures how frequently a customer purchases.

## 🔹 Monetary
Measures how much revenue a customer generates.

RFM analysis helped identify:
- Loyal customers
- High-spending customers
- Inactive customers
- Potential churn-risk customers

---

# 🤖 Machine Learning Approach

## K-Means Clustering

K-Means clustering was applied to segment customers based on RFM behavior.

### Steps Performed:
1. Feature Selection
2. Data Scaling using StandardScaler
3. Elbow Method for cluster selection
4. K-Means clustering
5. Cluster interpretation

The customers were segmented into three major groups:
- VIP / High-value customers
- Regular customers
- Low-value / Inactive customers

---

# 📌 Cluster Interpretation

## 🔹 Cluster 0 — Regular Customers
- Moderate recency
- Moderate frequency
- Moderate monetary contribution

These customers contribute consistently but are not high spenders.

---

## 🔹 Cluster 1 — Low-value / Inactive Customers
- High recency
- Low frequency
- Low monetary contribution

These customers are at risk of churn and require re-engagement strategies.

---

## 🔹 Cluster 2 — High-value / VIP Customers
- Very low recency
- Extremely high frequency
- Very high monetary contribution

These customers generate the highest revenue and should be prioritized for retention and personalized marketing.

---

# 📊 Key Insights & Findings

## 💰 Revenue Insights
- Frequency and Monetary value showed a strong positive relationship.
- Customers purchasing more frequently generated significantly higher revenue.

---

## 🌍 Geographical Insights
- The dataset was heavily dominated by customers from the United Kingdom.
- Some countries had lower customer count but higher average spending per customer.

---

## 👥 Customer Segmentation Insights
- Customer behavior varied significantly across clusters.
- A small segment of customers contributed disproportionately high revenue.
- High-value customers showed strong purchasing consistency and recent activity.

---

# 🧠 Multi-Domain Analytical Perspective

## 📊 Data Analyst Perspective
- Performed data cleaning and preprocessing
- Conducted exploratory data analysis
- Built visualizations to identify purchasing trends
- Converted raw transactional data into customer-level insights

---

## 💼 Business Analyst Perspective
- Identified high-value customer segments
- Evaluated customer retention opportunities
- Analyzed country-wise revenue contribution
- Generated actionable business recommendations

---

## 📦 Product Analyst Perspective
- Analyzed customer purchasing engagement
- Studied purchasing frequency behavior
- Evaluated customer interaction trends
- Identified opportunities for personalization strategies

---

## ⚠️ Risk Analyst Perspective
- Identified inactive customers with high recency values
- Detected geographical dependency risk on UK customers
- Highlighted revenue concentration among limited customer groups
- Evaluated potential customer churn behavior

---

# 📉 Challenges Faced During the Project

- Handling missing customer IDs
- Managing highly skewed distributions
- Converting transaction-level data into customer-level summaries
- Scaling data before clustering
- Interpreting customer clusters meaningfully

---

# 🛠️ Tech Stack Used

## Programming Language
- Python 🐍

---

## Libraries & Frameworks
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Machine Learning Techniques
- RFM Analysis
- StandardScaler
- K-Means Clustering

---

## Development Environment
- Google Colab
- Jupyter Notebook
- GitHub

---

# 📊 Analytical Workflow

```text
1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis
4. Univariate Analysis
5. Bivariate Analysis
6. Country-wise Revenue Analysis
7. RFM Feature Engineering
8. Data Scaling
9. Elbow Method
10. K-Means Clustering
11. Cluster Interpretation
12. Business Insights & Recommendations
