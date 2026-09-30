# 🛒 Google E-commerce Analytics

An end-to-end e-commerce analytics project using **Python, SQL, data cleaning, funnel analysis, and interactive dashboards** to analyze customer behavior, sales performance, and conversion trends.

---

## 📌 Project Overview

This project focuses on analyzing an e-commerce dataset to understand how users move through different stages of the customer journey.

The main goal is to transform raw data into meaningful business insights by:

- 🧹 Cleaning and preparing raw datasets
- 🐍 Performing exploratory analysis using Python
- 🗄️ Using SQL for business-focused analysis
- 📉 Measuring customer funnel performance
- 🔍 Identifying conversion and drop-off patterns
- 📊 Preparing cleaned datasets for dashboard visualization

---

## 🛠️ Tech Stack

- 🐍 **Python**
- 🐼 **Pandas**
- 🔢 **NumPy**
- 📓 **Jupyter Notebook**
- 🗄️ **SQL**
- 🧱 **SQLite**
- 📊 **Power BI**
- 🌿 **Git**
- 🐙 **GitHub**

---

## 📁 Project Structure

```text
google-ecommerce-analytics/
│
├── data/
│   ├── raw/
│   │   ├── customer_summary.csv
│   │   ├── funnel_events.csv
│   │   ├── order_items.csv
│   │   └── orders.csv
│   │
│   └── cleaned/
│       ├── customer_summary_clean.csv
│       ├── funnel_events_clean.csv
│       ├── funnel_summary_clean.csv
│       ├── order_items_clean.csv
│       └── orders_clean.csv
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   └── 02_sql_analysis.ipynb
│
├── sql/
│   └── google_ecommerce.db
│
├── funnel_summary.csv
│
└── README.md
```

---

## 🧹 Data Cleaning

The raw datasets were cleaned and transformed using Python and Pandas.

Major cleaning tasks included:

- ✅ Handling missing values
- ✅ Removing duplicate records
- ✅ Standardizing column names
- ✅ Correcting data types
- ✅ Cleaning date and time fields
- ✅ Checking inconsistent values
- ✅ Preparing analysis-ready datasets
- ✅ Creating cleaned versions of raw CSV files

The cleaned datasets are stored inside:

```text
data/cleaned/
```

---

## 🗄️ SQL Analysis

The cleaned data was loaded into a SQLite database for further analysis.

SQL was used to explore important business questions related to:

- 🛍️ Orders
- 👥 Customers
- 📦 Products
- 💰 Sales
- 🔄 Funnel events
- 📈 Conversion behavior
- 🧑‍💻 Customer activity

The SQL database is available at:

```text
sql/google_ecommerce.db
```

---

## 🔄 Funnel Analysis

One of the main parts of this project is the analysis of the customer conversion funnel.

The funnel helps measure how users move from initial interaction to final purchase.

```text
👀 Visit
   ↓
🔎 Product View
   ↓
🛒 Add to Cart
   ↓
💳 Checkout
   ↓
✅ Purchase
```

The analysis focuses on:

- 👥 Number of users at each stage
- 📊 Conversion rate between stages
- 🎯 Overall purchase conversion
- 📉 Customer drop-off points
- ⚙️ Funnel efficiency

This helps identify where potential customers are leaving the purchasing journey.

---

## ❓ Business Questions

The project is designed to answer questions such as:

- 👥 How many customers are generating orders?
- 📉 Which stages of the funnel experience the highest drop-off?
- 🎯 What percentage of users complete a purchase?
- 📦 Which product categories generate the most orders?
- 📆 How does sales performance change over time?
- 💰 Which customer segments contribute the most to revenue?
- 🚀 Where can the conversion process be improved?

---

## 📊 Dashboard

The final analysis is visualized through an interactive **Power BI dashboard**.

The dashboard includes visualizations such as:

- 💰 Total Revenue
- 🛍️ Total Orders
- 👥 Total Customers
- 🧾 Average Order Value
- 📦 Orders by Category
- 🔄 Customer Funnel
- 📈 Funnel Conversion Rate
- 🌍 Geographic Order Distribution
- 📅 Sales Trends
- 🎛️ Interactive Filters and Slicers

---

## 💡 Key Insights

The project enables identification of:

- 📉 Important customer drop-off stages
- 💰 Revenue-generating product categories
- 🧑‍💻 Customer purchase behavior
- 📈 Sales performance patterns
- 🔄 Funnel conversion opportunities
- 🌍 Geographic distribution of orders

These insights can help businesses improve customer experience and make more data-driven decisions.

---

## 🔄 Project Workflow

```text
📂 Raw Data
   ↓
🐍 Python Data Cleaning
   ↓
🧹 Cleaned Data
   ↓
🗄️ SQLite Database
   ↓
🔎 SQL Analysis
   ↓
🔄 Funnel Analysis
   ↓
📊 Power BI Dashboard
   ↓
💡 Business Insights
```

---

## ▶️ How to Run the Project

### 1️⃣ Clone the repository

```bash
git clone https://github.com/Vivek-afk-oss/google-ecommerce-analytics.git
```

### 2️⃣ Navigate to the project directory

```bash
cd google-ecommerce-analytics
```

### 3️⃣ Open Jupyter Notebook

```bash
jupyter notebook
```

Then open:

```text
notebooks/01_data_cleaning.ipynb
```

followed by:

```text
notebooks/02_sql_analysis.ipynb
```

---

## 🚀 Future Improvements

Future versions of the project can include:

- 🎯 Customer segmentation using RFM analysis
- 👥 Cohort and retention analysis
- 🤖 Product recommendation analysis
- 💵 Customer lifetime value analysis
- ⚙️ Automated ETL pipeline
- 📈 Advanced sales forecasting
- 🧠 Machine learning-based customer behavior prediction
- 🌐 Deployment of an interactive web dashboard

---

## 🎯 Project Purpose

This project was created as a practical data analytics portfolio project to demonstrate skills in:

- 🧹 Data Cleaning
- 🐍 Python
- 🗄️ SQL
- 📊 Business Analysis
- 🔄 Funnel Analysis
- 📈 Data Visualization
- 📊 Power BI
- 🐙 GitHub Project Documentation

---

## 👨‍💻 Author

**Vivek**

🐙 GitHub: [Vivek-afk-oss](https://github.com/Vivek-afk-oss)
