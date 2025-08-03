# Customer-Segmentation-and-Product-Recommendations-in-E-Commerce
Customer Segmentation and Product Recommendations in E-Commerce
# 🛒 Shopper Spectrum

**Customer Segmentation and Product Recommendations in E-Commerce**

## 📌 Project Overview

This project analyzes e-commerce transaction data to identify customer purchasing behavior and build a real-time product recommendation system. It combines **RFM analysis**, **unsupervised clustering**, and **collaborative filtering** to deliver actionable insights for e-commerce businesses.

---

## 🔍 Problem Statement

The global e-commerce industry generates massive amounts of transaction data. By analyzing this data, businesses can:

- Segment customers based on their purchase behavior
- Identify high-value and at-risk customers
- Offer personalized product recommendations

---

## 🧠 Techniques Used

- Data Cleaning & Feature Engineering
- RFM Analysis (Recency, Frequency, Monetary)
- KMeans Clustering
- Item-Based Collaborative Filtering
- Cosine Similarity
- Streamlit Web App for Real-time Predictions

---

## 🗃 Dataset

- **Source:** Public e-commerce dataset (UK-based retail)
- **Duration:** 2022–2023
- **Features:** InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

---

## 🚀 Project Pipeline

### ✅ Phase 1: Dataset Collection & Understanding
- Load dataset and inspect structure
- Identify and handle missing values, duplicates, and anomalies

### ✅ Phase 2: Data Preprocessing
- Remove cancelled invoices, missing customer IDs, and invalid quantity/price values
- Create `TotalPrice` = `Quantity * UnitPrice`

### ✅ Phase 3: Exploratory Data Analysis (EDA)
- Analyze transactions by country, product sales, and purchase trends
- Visualize revenue and distribution of RFM features

### ✅ Phase 4: RFM Analysis & Clustering
- Generate RFM metrics per customer
- Normalize data using StandardScaler
- Use KMeans and Elbow Method to find optimal clusters
- Label clusters (High-Value, Regular, Occasional, At-Risk)

### ✅ Phase 5: Recommendation System
- Create user-item matrix
- Compute cosine similarity between products
- Build function to return top 5 similar products

### ✅ Phase 6: Streamlit App
- 🎯 **Product Recommendation Module**
- 🎯 **Customer Segmentation Module**
- Real-time prediction of customer segment and product recommendations

---

## 📱 Streamlit App Features

### 🔹 Product Recommendation
- Input product name
- Returns 5 similar products based on purchase patterns

### 🔹 Customer Segmentation
- Input Recency, Frequency, and Monetary value
- Returns predicted segment: High-Value, Regular, At-Risk, etc.

---

## 📦 Tech Stack

- Python (pandas, numpy, matplotlib, seaborn)
- Scikit-learn
- Streamlit
- Cosine Similarity
- KMeans Clustering

---

## 💡 Real-World Use Cases

- 🎯 Targeted marketing via customer segmentation
- 🛒 Personalized product recommendations
- 📉 Identify and retain at-risk customers
- 📦 Inventory and pricing strategy

---




