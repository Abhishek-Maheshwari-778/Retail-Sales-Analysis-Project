# 🛍️ Retail Sales Analysis Project

## 📘 Academic Information

**Course:** Industrial Internet of Things (IIoT)  
**Semester:** 3rd Semester  
**University:** Invertis University, Bareilly  
**Student:** Abhishek Maheshwari  
**Role:** Exploratory Data Analysis (EDA) & Documentation

---

## 📊 Project Overview

The **Retail Sales Analysis Project** is a comprehensive data-driven approach to understand the performance of a retail business through its transactional data. In today’s competitive retail environment, it is essential to monitor sales trends, customer satisfaction, product preferences, and regional performance.

This project utilizes real-world retail sales data to explore various business metrics, conduct exploratory data analysis (EDA), and build a predictive model to estimate customer ratings. Visualizations are used to discover trends, patterns, and anomalies that help in making informed business decisions. The project is designed to simulate how data analytics can be used in real retail scenarios such as seasonal demand planning, identifying best-selling products, and tailoring services to specific customer demographics.

---

## 🎯 Objectives

The main objectives of the project are:

- 🔍 **Trend Analysis:** Identify how sales evolve over time (hourly, daily, monthly) and across different branches and cities.
- 👤 **Customer Behavior Analysis:** Analyze customer types (Member vs Normal), gender-based patterns, and preferred payment methods.
- 📦 **Product Performance:** Evaluate how different product lines perform in terms of quantity sold, revenue generated, and average rating.
- 🌐 **Regional Comparison:** Understand which cities and branches generate the highest revenue and customer satisfaction.
- 📈 **Predictive Modeling:** Build a machine learning model to predict customer satisfaction (ratings) based on other variables like quantity, total sales, and time.

---

## 🧾 Dataset Overview

The project uses a structured dataset named `retailsales.csv` which contains detailed information on retail transactions. Each row represents a transaction, and the dataset combines both categorical and numerical data. Key fields include:

- **Invoice ID:** Unique identifier for each transaction.
- **Product Line:** The category of the product sold (e.g., Health and Beauty, Food and Beverages).
- **Quantity:** Number of items sold in a transaction.
- **Unit Price:** Price per unit of the product.
- **Total:** Final amount for the transaction (Quantity × Unit Price).
- **Customer Type:** Indicates whether the customer is a Member or Normal.
- **Gender:** Gender of the customer.
- **Payment Method:** Mode of payment used (Cash, Credit Card, E-Wallet).
- **Rating:** Customer satisfaction rating (scale of 1–10).
- **Date & Time:** When the transaction took place.
- **City & Branch:** Geographical location of the transaction.

The richness of this dataset enables deep dives into product-level insights, customer segmentation, and time-based sales trends.

---


---

## 👥 Team Members

This project was collaboratively developed by a group of dedicated students as part of the **3rd Semester IIoT course** at Invertis University. Each member contributed to data analysis, visualization, documentation, or presentation.

### 🔹 Team Members:

- **Abhishek Kumar**  *(Leader)*
- **Abhishek Maheshwari** *(EDA & Documentation)*  
- **Anubhav Gangwar**  
- **Ridhima Maheshwari**  
- **Vansh Gupta**  
- **Samina Nooreen**  
- **Soni**  
- **Mohd Sheeban Khan**  
- **Ankit Kumar**  
- **Sanjay Mishra**  
- **Arpit Gupta**  
- **Aryan Srivastava**  
- **Vaishnavi Gupta**

> 🙌 Each member played a vital role in researching, cleaning, analyzing, and presenting data. Special focus was given to teamwork, communication, and practical application of Industrial IoT and data analytics concepts.

---

## 📌 Note

- This project was submitted as part of the **3rd Semester Project** under the subject **Industrial Internet of Things (IIoT)**.
- All datasets, visualizations, and machine learning models are included in the Jupyter Notebook and PDF reports.
- To view visual outputs, please see the `/images/` directory in this repository.

---



## 🧰 Tools & Libraries Used

The analysis is performed using Python, one of the most popular programming languages for data science. The following libraries were used to manipulate data, create visualizations, and build the regression model:

```python
import numpy as np                  # For numerical operations
import pandas as pd                # For data manipulation and analysis
import matplotlib.pyplot as plt    # For creating static visualizations
import seaborn as sns              # For statistical data visualization

from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.preprocessing import LabelEncoder
from category_encoders import BinaryEncoder

import datetime as dt              # For handling date and time
import warnings                    # To ignore warnings for cleaner outputs
warnings.filterwarnings("ignore")

