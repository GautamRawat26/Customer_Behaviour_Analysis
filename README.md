# Customer_Behaviour_Analysis
# 📊 Customer Behaviour Analysis – README

## 📌 Overview

This project presents an end-to-end **Data Analytics pipeline** focused on analyzing customer purchasing behavior.
It covers data processing, exploratory analysis, SQL querying, dashboard creation, and reporting.

The objective is to generate **actionable business insights** such as customer trends, category performance, and revenue distribution.

---

## 📂 Dataset

* Source: Customer transaction dataset (CSV/Excel)
* Domain: Retail / E-commerce
* Data includes:

  * Customer details (ID, Gender, Subscription)
  * Purchase information (Amount, Category)
  * Shipping preferences
  * Ratings and behavior metrics

---

## 🛠️ Tools & Technologies

* **Python** – Pandas, NumPy (data processing & EDA)
* **SQL** – MySQL / SQL Server (data querying)
* **Power BI** – Interactive dashboard & visualization
* **Gamma AI** – Report & PPT generation

---

## ⚙️ Steps Performed

### 1. Data Loading

* Imported dataset using Pandas
* Checked structure using `.head()`, `.info()`, `.describe()`

### 2. Data Cleaning

* Handled missing values
* Removed duplicates
* Standardized formats (dates, categories)
* Ensured consistency in categorical values

### 3. Exploratory Data Analysis (EDA)

* Analyzed customer distribution
* Studied purchase patterns
* Identified top-performing categories
* Used visualizations (bar charts, pie charts, trends)

### 4. Feature Engineering

* Created new features such as:

  * Customer segments
  * Purchase categories
  * Subscription insights
* Improved dataset usability for analysis

### 5. SQL Analysis

* Loaded dataset into database
* Performed:

  * Aggregations (SUM, COUNT, AVG)
  * Grouping & filtering
  * Category-wise analysis
  * Customer segmentation queries

### 6. Dashboard (Power BI)

Built an interactive dashboard to visualize insights.

### Key Highlights (from Dashboard):

* **Total Customers:** 3900
* **Average Rating:** 3.75
* **Average Purchase Amount:** $59.76
* **Total Revenue:** $233K 

### Visual Insights:

* Revenue is highest in **Clothing category**
* Majority customers are **non-subscribers (73%)**
* Clothing has highest sales volume
* Shipping preferences vary across customers

---

## 📊 Dashboard Features

* KPI Cards (Customers, Revenue, Rating)
* Revenue by Category (Bar Chart)
* Sales Count by Category
* Subscription Distribution (Donut Chart)
* Filters:

  * Category
  * Gender
  * Shipping Type
  * Subscription Status

---

## 📈 Results & Insights

* Clothing is the **top-performing category** in both revenue and sales
* Subscription adoption is low → potential growth opportunity
* Average purchase amount indicates mid-range spending behavior
* Customer segmentation helps in targeted marketing strategies

---

## ▶️ How to Run

### Step 1: Python (EDA)

```bash
pip install pandas numpy matplotlib seaborn
```

* Run Jupyter Notebook for data cleaning and analysis

### Step 2: SQL

* Import dataset into MySQL/SQL Server
* Run queries for analysis

### Step 3: Power BI

* Load cleaned dataset
* Create visuals and KPIs
* Apply filters and interactions

### Step 4: Report (Gamma)

* Use insights to generate PPT/report
* Present findings visually

---

## 📌 Conclusion

This project demonstrates a complete **data analytics workflow** from raw data to business insights.
It highlights the importance of combining **Python, SQL, and BI tools** to make data-driven decisions.

---

