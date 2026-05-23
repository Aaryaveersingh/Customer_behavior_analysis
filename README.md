# Customer Behavior Analysis

## Overview

This project focuses on analyzing customer purchasing behavior using a transactional dataset containing 3,900 customer records. The goal of the analysis was to uncover patterns in customer spending, product preferences, subscription usage, and purchasing trends to support data-driven business decisions.

The project demonstrates a complete **Data Analytics workflow** involving:

* Data preprocessing in Python
* Exploratory Data Analysis (EDA)
* Data cleaning and feature engineering
* SQL analysis using PostgreSQL
* Interactive dashboard creation in Power BI
* Business reporting and presentation creation using Gamma

The project combines technical analysis with business insights to showcase practical data analytics skills. 

---

# Dataset

### Dataset Details

* **Total Records:** 3,900
* **Total Columns:** 18

### Key Features

#### Customer Information

* Age
* Gender
* Location
* Subscription Status

#### Purchase Information

* Item Purchased
* Category
* Purchase Amount
* Season
* Size
* Color

#### Behavioral Attributes

* Discount Applied
* Promo Code Used
* Previous Purchases
* Purchase Frequency
* Review Rating
* Shipping Type

The dataset also contained missing values in the `Review Rating` column, which were handled during preprocessing. 

---

# Tools & Technologies

| Tool / Technology    | Purpose                         |
| -------------------- | ------------------------------- |
| Python               | Data analysis and preprocessing |
| Pandas & NumPy       | Data manipulation               |
| Matplotlib & Seaborn | Data visualization              |
| PostgreSQL           | SQL querying and analysis       |
| Power BI             | Interactive dashboard creation  |
| Gamma                | Presentation creation           |
| Jupyter Notebook     | Development environment         |

---

# Project Workflow

## 1. Data Loading

* Imported the dataset into Python using Pandas
* Checked data structure and data types
* Generated summary statistics

## 2. Exploratory Data Analysis (EDA)

* Analyzed customer demographics and purchase patterns
* Explored spending trends across categories
* Visualized distributions and relationships using charts

## 3. Data Cleaning

* Handled missing values in review ratings
* Standardized column names into `snake_case`
* Removed redundant columns
* Created new features such as:

  * `age_group`
  * `purchase_frequency_days`

## 4. PostgreSQL Analysis

The cleaned dataset was transferred into PostgreSQL for advanced SQL querying.

SQL analysis included:

* Revenue analysis by gender
* Subscription-based customer analysis
* Product performance analysis
* Customer segmentation
* Discount usage trends
* Revenue contribution by age groups



---

# Power BI Dashboard

An interactive Power BI dashboard was created to present key business insights visually.

### Dashboard Highlights

* **3.9K Total Customers**
* **$59.76 Average Purchase Amount**
* **3.75 Average Review Rating**

### Dashboard Visuals

* Revenue by Category
* Sales by Category
* Revenue by Age Group
* Sales by Age Group
* Subscription Distribution
* Customer Segmentation Analysis



---

# Key Results & Insights

### Customer Insights

* Loyal customers formed the majority segment
* Subscribers generated strong overall revenue contribution
* Express shipping customers showed slightly higher average spending

### Product Insights

* Gloves, Sandals, and Boots received the highest ratings
* Clothing and Accessories categories had strong sales performance
* Hats and Sneakers had the highest discount usage

### Business Recommendations

* Improve subscription adoption strategies
* Introduce customer loyalty programs
* Promote top-performing products
* Optimize discount strategies for profitability
* Focus marketing on high-value customer segments



---

# How to Run the Project

## 1. Clone the Repository

```bash
git clone https://github.com/your-username/project-name.git
```

## 2. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn psycopg2
```

## 3. Run the Jupyter Notebook

```bash
jupyter notebook
```

## 4. PostgreSQL Setup

* Create a PostgreSQL database
* Import the cleaned dataset
* Execute SQL queries from the SQL script

## 5. Open Power BI Dashboard

* Open the `.pbix` file in Power BI Desktop
* Refresh the dataset connection if required

---

# Project Deliverables

* Python EDA Notebook
* Cleaned Dataset
* PostgreSQL SQL Queries
* Power BI Dashboard
* Business Report
* Gamma Presentation (PPT)

---

# Conclusion

This project demonstrates practical skills in:

* Data Cleaning
* Exploratory Data Analysis
* SQL Querying
* Data Visualization
* Business Intelligence Reporting

It showcases how raw transactional data can be transformed into meaningful business insights using modern analytics tools and workflows.
