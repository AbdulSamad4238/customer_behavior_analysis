# 📊 Customer Shopping Behavior Analysis

## Overview

This repository presents an end-to-end data analytics project focused on uncovering actionable insights from retail transactional data. The project analyzes **3,900 customer purchases across 18 features** to understand spending patterns, customer segments, product performance, and business drivers. The workflow combines Python-based data preprocessing, SQL-driven analysis, and Power BI visualization to support data-backed decision-making.

---

## 🎯 Objectives

* Identify key spending patterns across demographics and customer segments
* Analyze the impact of discounts, subscriptions, and shipping types
* Determine top-performing products by rating and category
* Provide actionable business recommendations to improve revenue, retention, and operations

---

## 📁 Project Structure

```
Customer-Shopping-Behavior-Analysis/
│
├── data/
│   ├── raw/                # Original dataset
│   └── processed/         # Cleaned and feature-engineered data
│
├── notebooks/
│   └── eda_preprocessing.ipynb   # Python EDA, cleaning, and feature engineering
│
├── sql/
│   ├── schema.sql         # Table creation
│   └── analysis_queries.sql # Business analysis queries
│
├── dashboards/
│   └── powerbi_dashboard.pbix    # Interactive dashboard
│
├── reports/
│   └── Customer-Shopping-Behavior-Analysis.pdf
│
└── README.md
```

---

## 🔧 Tools & Technologies

* **Python**: pandas, numpy (data cleaning, EDA, feature engineering)
* **MySQL**: structured querying and business analysis
* **Power BI**: interactive dashboard and reporting

---

## 🧹 Data Preprocessing (Python)

Key steps performed:

1. **Data Loading & Exploration** – Inspected structure and summary statistics.
2. **Missing Value Handling** – Imputed missing review ratings using median by category.
3. **Column Standardization** – Renamed columns to `snake_case` for consistency.
4. **Feature Engineering** – Created new variables such as:

   * `age_group`
   * `purchase_frequency_days`
5. **Database Integration** – Exported cleaned data into MySQL for SQL analysis.

---

## 🗄️ SQL Analysis

Business questions answered using structured queries:

### 1️⃣ Revenue by Gender

* Compared total revenue between male and female customers.

### 2️⃣ High-Spending Discount Users

* Identified customers who used discounts but still spent above the average.

### 3️⃣ Top Products by Rating

* Ranked products based on average customer review ratings.

### 4️⃣ Shipping Type Comparison

* Compared average purchase value between **Standard** and **Express** shipping.

### 5️⃣ Subscribers vs Non-Subscribers

* Analyzed spending behavior and customer counts across subscription status.

### 6️⃣ Discount-Dependent Products

* Determined products most frequently purchased with discounts.

### 7️⃣ Customer Segmentation

* Segmented customers into:

  * **New**
  * **Returning**
  * **Loyal**

### 8️⃣ Top Products per Category

* Identified the top 3 products within each product category.

### 9️⃣ Revenue by Age Group

* Compared total revenue across age segments such as young adult, middle-aged, adult, and senior.

---

## 📊 Power BI Dashboard

An interactive dashboard was built to visualize:

* Customer segmentation
* Average purchase amount
* Subscription distribution
* Product performance
* Review ratings

The dashboard enables stakeholders to explore trends and filter insights dynamically.

---

## 📈 Key Insights

* Certain products are highly **discount-dependent**, affecting margins.
* **Subscribers and non-subscribers** show similar average spending, highlighting opportunities for better subscription value.
* A large share of customers fall into the **loyal segment**, indicating strong retention.
* Specific **age groups and product categories** contribute more significantly to revenue.

---

## 💡 Business Recommendations

* **Boost Subscriptions**: Promote exclusive benefits to increase subscriber adoption.
* **Customer Loyalty Programs**: Reward repeat buyers to strengthen long-term engagement.
* **Review Discount Policy**: Balance sales growth with margin control.
* **Targeted Marketing**: Focus campaigns on high-revenue age groups and top product categories.

---

## 🚀 How to Run This Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/Customer-Shopping-Behavior-Analysis.git
cd Customer-Shopping-Behavior-Analysis
```

### 2️⃣ Run Python Preprocessing

```bash
pip install pandas numpy
jupyter notebook notebooks/eda_preprocessing.ipynb
```

### 3️⃣ Load Data into MySQL

* Create tables using `schema.sql`
* Import cleaned data
* Run analysis queries from `analysis_queries.sql`

### 4️⃣ Open Power BI Dashboard

* Open `powerbi_dashboard.pbix` in Power BI Desktop

---

## 📌 Future Enhancements

* Add predictive modeling for customer lifetime value
* Automate ETL pipeline
* Integrate real-time data sources
* Expand dashboard with advanced filters and KPIs

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit a pull request.

---

## 📬 Contact

**Author:** Samad
If you found this project helpful or have feedback, feel free to connect!


