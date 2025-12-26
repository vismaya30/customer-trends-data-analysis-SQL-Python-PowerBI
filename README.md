# **Customer Shopping Behavior Analysis — Data Analytics Project**

## **Overview**

This project analyzes customer shopping behavior to uncover insights that support data-driven business decisions.
The workflow covers the full data analytics pipeline — from loading raw data and cleaning it in Python, to running SQL queries on relational databases, and building an interactive Power BI dashboard.
A final business report and presentation summarize the key findings and recommendations.

---

## **Dataset**

* **Source:** Customer transactional data (3,900 purchase records)
* **Size:** ~18 columns, including demographics, purchase details, and behavior indicators
* **Key Features:** Age, Gender, Subscription Status, Item Purchased, Purchase Amount, Category, Review Rating, Shipping Type
* **Missing data:** Mostly in `review_rating` column, imputed during preprocessing

> *Note:* Replace this section with a link to your dataset if publicly available.

---

## **Tools & Technologies**

| Category              | Tools                                      |
| --------------------- | ------------------------------------------ |
| Programming           | Python (Pandas, NumPy, Matplotlib/Seaborn) |
| Databases             | PostgreSQL / MySQL / SQL Server            |
| Business Intelligence | Power BI                                   |


---

## **Project Steps**

### **1️⃣ Data Loading & Exploration (Python)**

* Imported dataset using `pandas`
* Checked structure: `df.info()` and `df.describe()`
* Generated visualizations to understand distributions and patterns

### **2️⃣ Data Cleaning & Preparation**

* Renamed columns to snake_case for consistency
* Handled missing values
* Removed redundant features
* Created new features (e.g- age groups, purchase frequency)

### **3️⃣ SQL Database Integration**

* Loaded cleaned data into MySQL Server
* Ran analytical and business-focused SQL queries, such as:

  * Revenue by customer demographics
  * Top products by purchase amount and ratings
  * Subscription behavior vs. spending
  * Customer segmentation & repeat purchases

### **4️⃣ Interactive Dashboard (Power BI)**

* Built visual dashboards to display KPIs and trends
* Filters added for customer segments, seasons, and categories
* Visuals include: revenue breakdowns, top products, subscriptions, loyalty metrics


## **Results & Key Insights**

* Subscription customers generate higher revenue and purchase more frequently
* Top-rated products do not always correlate with highest sales — pricing and seasonality matter
* Discounts drive initial purchases but reduce long-term margins
* Express shipping users tend to be higher-paying customers
* Most revenue comes from the 25–40 age segment, suggesting targeted marketing opportunities


