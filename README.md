# 📊 Customer Shopping Behavior Analysis – Data Analytics Project

## 🔍 Overview

This project analyzes **customer shopping behavior** using transactional data to uncover insights into spending patterns, customer segments, product preferences, and subscription behavior.
It demonstrates an **end-to-end data analytics workflow**, from data preparation and SQL analysis to dashboarding, reporting, and executive presentation.

The insights generated help support **data-driven business decisions** related to marketing strategy, customer retention, and product positioning.

---

## 📁 Dataset

* **Source:** Customer Shopping Behavior Dataset
* **Records:** 3,900 transactions
* **Columns:** 18
* **Data Type:** Structured transactional data

### Key Features

* **Customer Demographics:** Age, Gender, Location, Subscription Status
* **Purchase Details:** Item Purchased, Category, Purchase Amount, Season, Size, Color
* **Shopping Behavior:** Discounts, Purchase Frequency, Review Rating, Shipping Type, Previous Purchases

### Data Quality Notes

* Missing values present in the *Review Rating* column
* Inconsistent column naming handled during preprocessing

---

## 🛠 Tools & Technologies

* **Python:** Pandas, NumPy, Matplotlib, Seaborn
* **SQL Databases:** PostgreSQL (analysis), MySQL / SQL Server compatible
* **Visualization:** Power BI
* **Reporting:** Analytical business report
* **Presentation:** Gamma (PPT)

---

## 🔄 Project Steps

### 1️⃣ Data Loading (Python)

* Imported dataset using Pandas
* Verified structure using `.info()` and `.describe()`

### 2️⃣ Exploratory Data Analysis (EDA)

* Analyzed purchase distributions and customer demographics
* Studied spending behavior across gender, age, and categories
* Identified missing values and anomalies

### 3️⃣ Data Cleaning & Feature Engineering

* Imputed missing *Review Rating* values using median ratings per category
* Renamed columns to snake_case for consistency
* Created new features:

  * **Age Group**
  * **Purchase Frequency (days)**
* Removed redundant columns after validation
* Loaded cleaned data into PostgreSQL

### 4️⃣ SQL Analysis (PostgreSQL)

Executed SQL queries to answer key business questions, including:

* Revenue comparison by gender
* Spending behavior of discount users
* Top-rated products
* Subscriber vs non-subscriber performance
* Customer segmentation (New, Returning, Loyal)
* Revenue contribution by age group
* Product performance by category
* Relationship between repeat purchases and subscriptions

### 5️⃣ Power BI Dashboard

* Built an interactive dashboard for business users
* Included KPIs, trend charts, and segmentation views
* Enabled filtering by category, age group, gender, and subscription status

### 6️⃣ Reporting

* Created a structured analytical report covering:

  * Methodology
  * Key findings
  * Business insights
  * Strategic recommendations

### 7️⃣ Presentation (Gamma)

* Designed a professional PPT summarizing insights
* Focused on clear storytelling for stakeholders
* Highlighted recommendations and business impact

---

## 📈 Power BI Dashboard

The dashboard provides:

* Total revenue and average purchase value
* Customer segmentation insights
* Top-performing products and categories
* Discount and subscription impact analysis
* Interactive slicers for deeper exploration

*(Dashboard screenshots or link can be added here)*

---

## 📌 Key Results & Insights

* Identified high-revenue customer segments and age groups
* Found products highly dependent on discounts
* Observed higher spending trends among subscribers
* Discovered strong correlation between repeat purchases and subscriptions
* Highlighted top-rated and best-selling products

---

## 💡 Business Recommendations

* Strengthen subscription benefits to increase retention
* Introduce loyalty programs for repeat customers
* Optimize discount strategies to protect margins
* Promote top-rated products in marketing campaigns
* Target high-revenue age groups with personalized offers

---

## ▶️ How to Run This Project

### Prerequisites

* Python 3.x
* PostgreSQL / MySQL / SQL Server
* Power BI Desktop

### Steps

1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```
2. Install required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Run Python notebooks/scripts for EDA and cleaning
4. Load cleaned data into the SQL database
5. Execute SQL queries for analysis
6. Open the Power BI file to explore the dashboard
7. Review the report and Gamma presentation for insights

---

## 📬 Contact

For collaboration, feedback, or opportunities:

* **LinkedIn:** https://www.linkedin.com/in/yashns1/

---
