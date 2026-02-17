# 🛍️ eBay Market Basket Analysis (K-Means Clustering)

## 📌 Project Overview

This project analyzes eBay transactional data using K-Means clustering to segment customers and purchasing behavior patterns. Instead of traditional association rule mining, unsupervised machine learning was applied to identify meaningful clusters based on purchase frequency, quantity, and spending behavior.

The goal was to uncover hidden patterns in customer transactions to support targeted marketing, personalization, and revenue optimization strategies.

## 🎯 Business Objectives

* Segment customers based on purchasing behavior

* Identify high-value and low-value customer groups

* Understand transaction patterns across clusters

* Enable targeted marketing and personalization strategies

## 🗂️ Dataset

The dataset consists of transactional e-commerce records including:

Invoice Number

Product Description

Quantity

Unit Price

Customer ID

Country

Transactions were aggregated at the customer level for behavioral segmentation.

## 🛠️ Tech Stack

Programming: Python
Libraries:
Pandas (Data manipulation)
NumPy (Numerical operations)
Scikit-learn (K-Means Clustering)
Matplotlib & Seaborn (Visualization)

## 🔄 Project Workflow
### 1️⃣ Data Cleaning & Preprocessing

Removed cancelled transactions
Filtered negative quantities and invalid entries
Handled missing Customer IDs
Aggregated transaction-level data into customer-level metrics
Performed feature scaling using StandardScaler

### 2️⃣ Feature Engineering

Created behavioral features such as:
Total purchase quantity
Total spending
Number of transactions
Average purchase value

### 3️⃣ K-Means Clustering

Applied Elbow Method to determine optimal number of clusters
Implemented K-Means algorithm
Segmented customers into distinct behavioral groups

### 4️⃣ Cluster Analysis

Interpreted cluster characteristics
Identified high-spending and frequent buyers
Compared purchasing trends across clusters

## 📊 Key Insights

* Distinct customer segments exist based on spending and purchase frequency

* A small segment contributes disproportionately to total revenue

* Certain clusters exhibit high repeat purchase behavior

* Behavioral segmentation enables more precise marketing strategies

## 💡 Business Impact

* Supports targeted promotions and personalized campaigns

* Helps identify premium customers for loyalty programs

* Enables efficient resource allocation for marketing

* Improves customer retention strategies

## 🚀 Skills Demonstrated

✔ Data Cleaning & Preprocessing
✔ Feature Engineering
✔ Feature Scaling
✔ Unsupervised Machine Learning (K-Means)
✔ Cluster Interpretation
✔ Business Insight Generation
