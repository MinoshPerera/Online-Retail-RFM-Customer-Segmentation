# 🛍️ Online Retail Customer Segmentation using RFM and Clustering

This project performs customer segmentation using the **Online Retail dataset** from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/online+retail). We apply **RFM (Recency, Frequency, Monetary)** analysis and **KMeans clustering** to uncover distinct customer segments, enabling personalized marketing strategies and better customer retention.

---

## 📦 Dataset Summary

- **Source**: UCI Machine Learning Repository
- **Title**: Online Retail
- **Published**: November 5, 2015
- **Transactions**: 541,909
- **Time Span**: 01/12/2010 to 09/12/2011
- **Business Type**: UK-based online non-store retailer, mainly selling all-occasion gifts
- **Data Type**: Multivariate, Sequential, Time-Series
- **Associated Tasks**: Classification, Clustering

### ✨ Variables

| Variable       | Type         | Description                                                                 |
|----------------|--------------|-----------------------------------------------------------------------------|
| InvoiceNo      | Categorical  | Unique transaction ID (prefix 'C' = cancellation)                          |
| StockCode      | Categorical  | Unique product/item ID                                                     |
| Description    | Categorical  | Product name                                                               |
| Quantity       | Integer      | Number of items per transaction                                            |
| InvoiceDate    | DateTime     | Timestamp of the transaction                                               |
| UnitPrice      | Float        | Price per product in sterling                                              |
| CustomerID     | Categorical  | Unique customer ID                                                         |
| Country        | Categorical  | Country of residence                                                       |

---

## 🔍 Project Objectives

- Preprocess and clean the transaction data
- Engineer RFM (Recency, Frequency, Monetary) features per customer
- Use **KMeans Clustering** to group customers based on RFM
- Determine optimal number of clusters using the **Elbow Method**
- Visualize clusters to analyze customer behavior patterns
- Extract actionable marketing insights

---

## 🧠 Key Concepts

- **RFM Analysis**: A customer behavior scoring system based on:
  - **Recency**: Time since last purchase
  - **Frequency**: Total number of purchases
  - **Monetary**: Total spending
- **KMeans Clustering**: Partitioned customers into meaningful segments
- **Customer Segments Examples**:
  - High-value loyal customers
  - Recent but infrequent buyers
  - Inactive or churned customers

---

## 📊 Tools & Technologies

- **Python** (Jupyter Notebook)
- **Pandas**, **NumPy** – Data manipulation
- **Matplotlib**, **Seaborn** – Visualizations
- **Scikit-learn** – Clustering models

---

## 📈 Results & Insights

- Segmented over 4,000 customers based on RFM values
- Derived distinct behavioral groups:
  - 💰 **Big Spenders**
  - 🕒 **Frequent Shoppers**
  - 🔄 **At-Risk / Churning**
- These clusters enable:
  - Targeted email campaigns
  - Loyalty rewards programs
  - Win-back strategies for lapsed customers

---

## 🔮 Future Enhancements

- Predict customer lifetime value (CLV)
- Integrate customer journey analysis using Graph ML
- Build a web-based dashboard for marketers
- Extend to multi-channel or product-based segmentation

---

## 🪪 License

This project is released under the [MIT License](LICENSE).

---
