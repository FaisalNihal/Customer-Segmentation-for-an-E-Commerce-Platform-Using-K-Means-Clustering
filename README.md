
# 🛍️ E-Commerce Customer Segmentation Using K-Means Clustering

## 📘 Introduction

Customer segmentation is a critical strategy in the modern e-commerce industry. One of the most effective techniques for segmentation is **K-Means Clustering**, an unsupervised machine learning algorithm that automatically groups similar data points based on defined characteristics.

In this project, K-Means Clustering was applied to segment e-commerce customers based on their purchasing behavior. The goal is to help businesses better understand their customer base, develop targeted marketing campaigns, and improve customer retention by catering to the specific needs of each segment.

---

## ✅ Project Overview

The project is structured into six key steps:

---

### 🔹 Step 1: Scope of the Project

The purpose of this project is to classify customers into distinct groups based on their annual income and spending habits. By analyzing this segmentation, businesses can:

- Understand different customer profiles.
- Identify high-value and at-risk customers.
- Develop strategies to retain valuable customers and engage low-activity ones.
- Offer personalized promotions based on customer behavior.

This segmentation helps in making data-driven decisions that align marketing, product recommendations, and service strategies with customer needs.

---

### 🔹 Step 2: Gather the Data

The dataset used for this project contains demographic and transactional data from an e-commerce platform. The data includes customer attributes such as age, gender, annual income, and spending score. The dataset was imported from a CSV file and loaded into the Python environment for analysis.

Having structured and relevant data is essential as it forms the foundation for building meaningful clusters.

---

### 🔹 Step 3: Clean the Data

Before performing clustering, the data was thoroughly cleaned to ensure accuracy and consistency:

- Missing or null values were identified and removed to avoid errors in analysis.
- Data types of numerical and categorical features were corrected where needed.
- Inconsistent or unwanted values, such as typos or extra spaces, were handled.
- The dataset was filtered to remove outliers that could skew the clustering results.

Proper data cleaning improves model performance and ensures that the clustering output is reliable and interpretable.

---

### 🔹 Step 4: Explore the Data (EDA)

Exploratory Data Analysis (EDA) was conducted to understand the underlying patterns in the dataset:

- Summary statistics were reviewed to understand the distribution of variables like quantity and order amount.
- Charts and graphs were used to visualize the relationships between different features like order quantity and price and
  customer distribution in different customer_type (free, trial, premium, lifetime)
- Trends such as the correlation between customer rating and order amount were explored.
- Key insights about customer  purchase behavior were identified, guiding the feature selection for clustering.

This step helps in selecting the right variables that contribute the most to distinguishing between customer segments.

![bar](https://github.com/user-attachments/assets/1703d411-d963-4d2d-a816-f28881ca8956) 

![Scatter (1)](https://github.com/user-attachments/assets/ca06373a-4aaa-41c2-a5ed-89dd6dfefc67)  ![scatter2](https://github.com/user-attachments/assets/89825254-4270-43f1-a907-52fef8e8a7e7)




---

### 🔹 Step 5: Data Modeling (K-Means Clustering)

K-Means Clustering was selected as the modeling technique due to its efficiency and simplicity. The key steps in the modeling phase included:

- Selecting the most relevant features (e.g., price,rating,order_amount,order_quantity) for segmentation.
- Scaling the features to ensure that all variables contribute equally to distance calculations.
- Using the Elbow Method to determine the optimal number of customer segments.
- Applying the K-Means algorithm to form clusters of customers with similar purchase behaviors.

After the model was fitted, each customer was assigned a cluster label indicating their segment.

![Inertia](https://github.com/user-attachments/assets/64ae80b0-bfbe-4e4a-9580-1b098f381eb6)

![Heatmap2 (6)](https://github.com/user-attachments/assets/2099e6e6-6c23-48ac-ab31-1350d8872681)

---

### 🔹 Step 6: Insights

The clustering process revealed **five distinct customer groups**, each representing a different pattern of purchasing behavior:
Customer group

**0**.Highest Performing group with highest quantity purchased per transaction value and average_order amount. A good number of **free** customer.

**1**.customers with low quantity purchased per transaction value and average_order amount .Most of them are **free** customer

**2**.Most of the customers are **Premium** and their average_quantity and average_amount is high

**3**.Lowest performing group with low average_quantity and average_amount per transaction value.Most of them are **trial** customers.

**4**.almost all of them are **lifetime** high price customers with lowest rating and low average_quantity value

These insights enable targeted marketing, personalized recommendations, and focused retention strategies — ultimately driving revenue and customer satisfaction.
![pie](https://github.com/user-attachments/assets/dfd753ae-e95a-42cb-819f-1908b35c2bce)
![bar2 (1)](https://github.com/user-attachments/assets/80623ffe-df60-49ff-aaaa-6070cd66ac18)
![bar2](https://github.com/user-attachments/assets/93c03b85-a5e9-4576-8cea-f54eb3997a97)




---

## 📌 Conclusion

This project demonstrates how K-Means clustering can be applied to customer data to uncover valuable insights. By segmenting customers based on their income and spending patterns, e-commerce businesses can:

- Improve decision-making through data-driven strategies.
- Create personalized customer experiences.
- Strengthen customer relationships and maximize value.

Customer segmentation is a foundational step in building intelligent, customer-focused business practices.

---

