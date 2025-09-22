# Customer Segmentation and Recommendation System

This project analyzes UK e-commerce data to understand customer behavior and perform in-depth market research. Using customer purchase patterns, the goal is to segment users and build a recommendation system that delivers personalized product suggestions based on customer preferences and product popularity.

---

## 📌 Objective

The primary goals of this project are:

- To explore and clean the raw transactional data.
- To perform customer segmentation using behavioral patterns.
- To create a product recommendation system.
- To provide business insights for improving customer satisfaction and sales.

---

## 📂 Project Description

This project is based on a publicly available dataset containing all transactions between **01/12/2010 and 09/12/2011** for a **UK-based, non-store online retail** company that sells unique all-occasion gifts. A large number of customers are wholesalers.

The full project is developed using a **Jupyter Notebook** in the **Kaggle environment**, which provides free computational resources and an easy way to follow the steps.

👉 **Explore the full notebook here**: [Customer Recommendation System on Kaggle](https://www.kaggle.com/code/tusharbaweja/customer-recommendation-system)

---

## 📊 Dataset Information

**Source**: [E-Commerce Data on Kaggle](https://www.kaggle.com/datasets/carrie1/ecommerce-data)

The dataset includes over **25,000 transactions** and has the following columns:

| Name        | Role    | Type        | Units    | Description                                                                                   | Missing Values |
|-------------|---------|-------------|----------|-----------------------------------------------------------------------------------------------|----------------|
| InvoiceNo   | ID      | Categorical | —        | A 6-digit integral number uniquely assigned to each transaction. If this code starts with 'C', it indicates a cancellation. | No             |
| StockCode   | ID      | Categorical | —        | A 5-digit integral number uniquely assigned to each distinct product.                         | No             |
| Description | Feature | Categorical | —        | Product name.                                                                                 | No             |
| Quantity    | Feature | Integer     | —        | The quantity of each product (item) per transaction.                                          | No             |
| InvoiceDate | Feature | Date        | —        | The date and time when each transaction was generated.                                        | No             |
| UnitPrice   | Feature | Continuous  | GBP (£)  | Product price per unit.                                                                       | No             |
| CustomerID  | Feature | Categorical | —        | A 5-digit integral number uniquely assigned to each customer.                                 | No             |
| Country     | Feature | Categorical | —        | The name of the country where each customer resides.                                          | No             |


