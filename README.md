# K-Means Clustering for Customer Segmentation

This project applies **K-Means Clustering**, an unsupervised machine learning algorithm, to segment customers based on their purchasing behavior. The primary objective is to extract actionable insights to support **targeted marketing strategies** and **enhance customer engagement**.

## Project Objective

The main goal is to segment customers based on the **RFM model**:

- **Recency** – How recently a customer made a purchase  
- **Frequency** – How often they purchase  
- **Monetary Value** – How much they spend  

These segments help businesses to:

- Deliver **personalized promotions**
- **Increase sales** through targeted offerings
- Build **long-term customer loyalty**

---

## 📊 Overview of K-Means Clustering

**K-Means** is an iterative algorithm that partitions data into *K* distinct, non-overlapping clusters based on feature similarity. The general steps include:

1. Select the number of clusters (**K**)
2. Initialize **centroids** randomly
3. Assign each data point to the nearest centroid
4. Recalculate centroids based on current cluster members
5. Repeat steps 3–4 until convergence is reached (i.e., centroids do not change significantly)

---

## 🧾 Dataset Description

The dataset includes transactional data with the following attributes:

| Column       | Description                                         |
|--------------|-----------------------------------------------------|
| InvoiceNo    | Unique invoice number (cancellations start with ‘C’)|
| StockCode    | Product/item code                                   |
| Description  | Product name                                        |
| Quantity     | Number of items purchased                           |
| InvoiceDate  | Date of transaction                                 |
| UnitPrice    | Price per item (£)                                  |
| CustomerID   | Unique identifier for each customer                 |
| Country      | Country where the transaction was made              |

---

## Analysis and Insights

By applying K-Means to the processed RFM features, we identified **distinct customer segments**, such as:

- **High spenders** with low purchase frequency  
- **Frequent buyers** with lower spending  
- **Loyal and consistent** customers  

These clusters help businesses to:

- Target the right customers with the right promotions  
- Increase ROI through focused marketing efforts  
- Develop customer-centric strategies that foster loyalty  

---


---
