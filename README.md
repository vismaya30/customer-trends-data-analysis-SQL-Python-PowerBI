# customer-trends-data-analysis-SQL-Python-PowerBI
Data analysis project to representing customer behavior  analysis using python, sql and power BI
Below is a **professional, recruiter-friendly README template** based on your project workflow.
You can copy-paste directly into GitHub — formatting is Markdown-compatible.

---

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
| Presentation          | Gamma                                      |
| Documentation         | Markdown, PDF Report                       |

---

## **Project Steps**

### **1️⃣ Data Loading & Exploration (Python)**

* Import dataset using `pandas`
* Check structure: `df.info()` and `df.describe()`
* Initial visualizations to understand distributions and patterns

### **2️⃣ Data Cleaning & Preparation**

* Rename columns to snake_case for consistency
* Handle missing values (median/mode imputation)
* Remove redundant features
* Create new features (e.g., age groups, purchase frequency)

### **3️⃣ SQL Database Integration**

* Load cleaned data into PostgreSQL/MySQL/SQL Server
* Run analytical and business-focused SQL queries, such as:

  * Revenue by customer demographics
  * Top products by purchase amount and ratings
  * Subscription behavior vs. spending
  * Customer segmentation & repeat purchases

### **4️⃣ Interactive Dashboard (Power BI)**

* Build visual dashboards to display KPIs and trends
* Filters added for customer segments, seasons, and categories
* Visuals include: revenue breakdowns, top products, subscriptions, loyalty metrics

### **5️⃣ Insights & Reporting**

* Develop a PDF report summarizing the findings
* Highlight actionable business recommendations
* Present the story using **Gamma slides**

---

## **Dashboard Preview**

> Add a screenshot of your Power BI dashboard here
> *(Drag an image here in GitHub or paste a link to report)*

---

## **Results & Key Insights**

* Subscription customers generate higher revenue and purchase more frequently
* Top-rated products do not always correlate with highest sales — pricing and seasonality matter
* Discounts drive initial purchases but reduce long-term margins
* Express shipping users tend to be higher-paying customers
* Most revenue comes from the 25–40 age segment, suggesting targeted marketing opportunities





Would you like a **shorter version** for job applications or LinkedIn?
