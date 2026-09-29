# Customer Shopping Behavior Analysis

An end-to-end data analytics project focused on understanding customer shopping behavior and identifying actionable business insights using **Python, PostgreSQL, SQL, and Power BI**.

## Overview

This project analyzes customer shopping data to understand purchasing patterns across customer demographics, product categories, subscriptions, discounts, shipping methods, and customer segments.

The project follows a complete data analytics workflow — from **data cleaning and exploratory analysis to SQL-based business analysis and Power BI visualization**.

## Dataset

The dataset contains **3,900 customer purchase records** with **18 columns** covering:

* Customer demographics
* Product and category information
* Purchase amounts
* Discounts and promotions
* Subscription status
* Customer ratings
* Shipping preferences
* Previous purchase history
* Purchase frequency
* Seasonality

The dataset was explored and prepared using Python before being loaded into PostgreSQL for further analysis.

## Tools & Technologies

* **Python** — Data loading, cleaning, EDA, and feature engineering
* **Pandas** — Data manipulation and analysis
* **PostgreSQL** — Database storage and SQL analysis
* **SQL** — Business-focused data analysis
* **Power BI** — Dashboard and data visualization
* **Jupyter Notebook** — Data analysis workflow

## Project Steps

### 1. Data Loading & Exploratory Data Analysis

The dataset was imported into Python using Pandas and explored to understand:

* Dataset structure
* Data types
* Missing values
* Statistical summaries
* Customer and purchase patterns

### 2. Data Cleaning & Preparation

The data was prepared for analysis by:

* Handling missing values
* Standardizing column names
* Creating additional features
* Checking redundant columns
* Preparing the final dataset for database analysis

Missing review ratings were handled using category-level median values.

### 3. PostgreSQL Database Integration

The cleaned dataset was loaded into **PostgreSQL** for structured analysis using SQL.

SQL queries were then used to answer business-focused questions related to customers, products, revenue, discounts, subscriptions, and purchasing behavior.

### 4. SQL Business Analysis

The analysis explored questions such as:

* How does revenue vary by gender?
* Do customers using discounts have higher or lower purchase values?
* Which products have the highest ratings?
* How does shipping type relate to purchase amount?
* How do subscribed and non-subscribed customers compare?
* Which products have the highest discount rates?
* How can customers be segmented based on purchase history?
* What are the top-performing products within each category?
* What is the relationship between repeat purchases and subscriptions?
* How does revenue vary across age groups?

### 5. Power BI Dashboard

The analyzed data was used to create an interactive **Power BI dashboard** to present key findings through visualizations and business metrics.

The dashboard focuses on areas such as:

* Customer demographics
* Revenue and purchasing behavior
* Product performance
* Subscription behavior
* Customer segmentation
* Discounts and shipping

## Results

The analysis identified several useful patterns in customer purchasing behavior, including:

* Differences in revenue contribution across customer groups
* High-value customers associated with discount usage
* Highly rated products
* Differences in purchase amounts between shipping methods
* Differences between subscribed and non-subscribed customers
* Customer segments based on previous purchase behavior
* Product performance across categories
* Revenue distribution across different age groups

These findings were used to support business recommendations around **subscriptions, customer loyalty, marketing, discounts, and product positioning**.

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/FenilViradiya/customer-behavior-data-analysis.git
cd Customer-Behavior-Analysis
```

### 2. Install Python dependencies

```bash
pip install pandas sqlalchemy psycopg2-binary jupyter
```

### 3. Run the Jupyter Notebook

Open the project notebook:

```bash
jupyter notebook
```

Run the notebook to perform the data loading, cleaning, EDA, and feature engineering steps.

### 4. Set Up PostgreSQL

Create a PostgreSQL database and update the database connection details in the notebook.

Load the cleaned dataset into PostgreSQL and execute the SQL queries provided in the `SQL` folder.

### 5. Open the Power BI Dashboard

Open the Power BI file to explore the interactive dashboard.

## Deliverables

* Python/Jupyter Notebook
* Cleaned dataset
* PostgreSQL SQL analysis
* Power BI dashboard
* Project report
* Project presentation

## Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis
* Feature Engineering
* Python & Pandas
* SQL
* PostgreSQL
* Data Visualization
* Power BI
* Business Analysis
* Data Storytelling

## Conclusion

This project demonstrates a complete data analytics workflow, starting with raw customer shopping data and transforming it into structured analysis, visualizations, and business insights using **Python, SQL, PostgreSQL, and Power BI**.
