# 🛒 Shopper Spectrum: Customer Segmentation & Product Recommendation

An end-to-end Machine Learning project that analyzes customer purchase behavior using **RFM Analysis**, performs **Customer Segmentation** with **K-Means Clustering**, and recommends similar products using **Item-Based Collaborative Filtering**.

Built with **Python, Scikit-learn, Pandas, Streamlit, and Cosine Similarity**.

---

## 📌 Project Overview

E-commerce platforms generate thousands of customer transactions every day. Understanding customer purchasing behavior helps businesses improve marketing strategies, customer retention, inventory management, and product recommendations.

This project focuses on:

- Customer Segmentation using RFM Analysis
- K-Means Clustering
- Product Recommendation using Item-Based Collaborative Filtering
- Interactive Streamlit Web Application

---

## 🚀 Features

### 📊 Customer Segmentation
- RFM (Recency, Frequency, Monetary) Analysis
- Customer behavior clustering using K-Means
- Customer segment prediction
- Cluster visualization

### 🛍 Product Recommendation
- Item-Based Collaborative Filtering
- Cosine Similarity
- Top 5 similar product recommendations
- Case-insensitive product search

### 📈 Exploratory Data Analysis
- Transaction trends
- Country-wise sales
- Top-selling products
- Revenue analysis
- Customer spending distribution

### 🌐 Streamlit Dashboard
- Customer Segmentation Module
- Product Recommendation Module
- Interactive user interface
- Real-time predictions

---

## 📂 Project Structure

```
Shopper-Spectrum/
│
├── EDA.ipynb
├── Customer_Segmentation.ipynb
├── Recommendation_System.ipynb
├── app.py
│
├── online_retail.csv
│
├── kmeans.pkl
├── scaler.pkl
├── similarity.pkl
├── cluster_names.pkl
│
├── requirements.txt
└── README.md
```

---

## 📚 Dataset

The dataset contains e-commerce transaction records.

### Features

| Column | Description |
|---------|-------------|
| InvoiceNo | Transaction ID |
| StockCode | Product Code |
| Description | Product Name |
| Quantity | Quantity Purchased |
| InvoiceDate | Purchase Date |
| UnitPrice | Price per Item |
| CustomerID | Customer Identifier |
| Country | Customer Country |

---

## ⚙️ Data Preprocessing

- Removed missing Customer IDs
- Removed cancelled invoices
- Removed invalid quantities and prices
- Converted InvoiceDate to datetime
- Created TotalAmount feature

---

## 📊 Exploratory Data Analysis

Performed:

- Missing Value Analysis
- Duplicate Removal
- Country-wise Transaction Analysis
- Top Selling Products
- Monthly Sales Trend
- Revenue Distribution
- RFM Distribution
- Elbow Method
- Silhouette Score
- Customer Cluster Visualization

---

## 👥 Customer Segmentation

RFM Metrics:

- **Recency** – Days since the customer's last purchase
- **Frequency** – Number of purchases
- **Monetary** – Total amount spent

Workflow:

```
Raw Data
      ↓
Data Cleaning
      ↓
Feature Engineering
      ↓
RFM Analysis
      ↓
StandardScaler
      ↓
K-Means Clustering
      ↓
Customer Segments
```

---

## 🛒 Product Recommendation System

The recommendation engine uses:

- Item-Based Collaborative Filtering
- Customer–Product Purchase Matrix
- Cosine Similarity

Output:

- Top 5 similar products for a selected product

---

## 💻 Streamlit Application

The application contains two modules.

### 1️⃣ Customer Segmentation

User inputs:

- Recency
- Frequency
- Monetary

Output:

- Predicted Customer Segment

---

### 2️⃣ Product Recommendation

User inputs:

- Product Name

Output:

- Top 5 Recommended Products

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Streamlit
- Joblib

---

## 📦 Machine Learning Techniques

- Feature Engineering
- RFM Analysis
- StandardScaler
- K-Means Clustering
- Elbow Method
- Silhouette Score
- Item-Based Collaborative Filtering
- Cosine Similarity

---

## ▶️ Installation

Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Shopper-Spectrum.git
```

Move into the project folder

```bash
cd Shopper-Spectrum
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the Streamlit app

```bash
streamlit run app.py
```

---

## 📸 Application Preview

### Customer Segmentation

- Input Recency, Frequency and Monetary values
- Predict Customer Segment

### Product Recommendation

- Enter a product name
- Receive Top 5 Similar Products

---

## 📈 Business Applications

- Personalized Product Recommendation
- Customer Segmentation
- Targeted Marketing
- Customer Retention
- Inventory Planning
- Sales Analysis
- Customer Lifetime Value Analysis

---

## 📌 Future Improvements

- Deep Learning Recommendation Models
- Content-Based Recommendation
- Hybrid Recommendation System
- Interactive Plotly Dashboards
- Customer Churn Prediction
- Sales Forecasting
- Cloud Deployment

---

## 👩‍💻 Author

**Shaik Azra Nigar**

GitHub: https://github.com/YOUR_USERNAME

LinkedIn: https://www.linkedin.com/in/YOUR_LINKEDIN/

---

## ⭐ If you found this project useful, consider giving it a star!
