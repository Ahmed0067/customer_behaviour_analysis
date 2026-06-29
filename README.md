# customer_behaviour_analysis
# Customer Purchase Behaviour Analysis using Python, PostgreSQL & Power BI

## Overview

This major project focuses on analyzing customer purchase behaviour using data analytics techniques. The project demonstrates the complete data analysis workflow, starting from loading the dataset in Python, performing data cleaning and exploratory data analysis (EDA), storing and querying data using PostgreSQL, creating interactive dashboards in Power BI, and presenting the findings through a report and presentation.

---

## Project Objectives

* Load and explore customer purchase data.
* Clean and preprocess the dataset.
* Perform Exploratory Data Analysis (EDA).
* Store the cleaned data in PostgreSQL.
* Execute SQL queries to extract business insights.
* Build an interactive Power BI dashboard.
* Prepare a project report and presentation.

---

## Dataset

The dataset contains customer purchase information, including customer details, products, sales, and transaction-related data.

**Dataset Features:**

* Customer ID
* Gender
* Age
* Product Category
* Purchase Amount
* Quantity
* Payment Method
* Purchase Date
* Location

---

## Tools & Technologies

| Tool                 | Purpose                      |
| -------------------- | ---------------------------- |
| Python               | Data Loading, Cleaning & EDA |
| Pandas               | Data Manipulation            |
| NumPy                | Numerical Operations         |
| Matplotlib & Seaborn | Data Visualization           |
| PostgreSQL           | Database Management          |
| SQL                  | Data Querying                |
| Power BI             | Dashboard Creation           |
| Microsoft PowerPoint | Project Presentation         |
| Microsoft Word       | Project Report               |

---

## Project Workflow

### Step 1: Load Dataset

* Import the dataset into Python.
* Verify data structure and data types.

### Step 2: Data Cleaning

* Remove duplicate records.
* Handle missing values.
* Correct inconsistent data.
* Convert data types where necessary.

### Step 3: Exploratory Data Analysis (EDA)

* Analyze customer demographics.
* Study purchasing behaviour.
* Visualize sales trends.
* Identify top-selling products.
* Generate statistical summaries.

### Step 4: PostgreSQL Database

* Create database and tables.
* Import cleaned data.
* Execute SQL queries for business analysis.

### Step 5: Power BI Dashboard

Create an interactive dashboard containing:

* Total Sales
* Total Customers
* Product Category Analysis
* Monthly Sales Trend
* Payment Method Distribution
* Customer Age Distribution
* Regional Sales Analysis
* Filters and Slicers

### Step 6: Documentation

* Prepare project report.
* Create PowerPoint presentation.
* Summarize findings and conclusions.

---

## Dashboard Features

The Power BI dashboard includes:

* Sales Overview
* Customer Insights
* Product Performance
* Monthly Sales Trend
* Category-wise Sales
* Payment Method Analysis
* Interactive Filters

---

## Results

The project successfully demonstrates how data analytics can help understand customer purchasing behaviour.

Key outcomes include:

* Improved data quality through cleaning.
* Meaningful insights from EDA.
* Efficient data storage and querying using PostgreSQL.
* Interactive business dashboard using Power BI.
* Clear visualization of customer trends and sales performance.

---

## Project Structure

```
Customer-Purchase-Behaviour-Analysis/
│
├── Dataset/
│   └── customer_purchase.csv
│
├── Python/
│   ├── data_cleaning.py
│   ├── eda_analysis.py
│   └── requirements.txt
│
├── SQL/
│   ├── create_table.sql
│   ├── insert_data.sql
│   └── queries.sql
│
├── PowerBI/
│   └── Customer_Purchase_Dashboard.pbix
│
├── Report/
│   └── Major_Project_Report.pdf
│
├── Presentation/
│   └── Major_Project_Presentation.pptx
│
└── README.md
```

---

## How to Run the Project

### Python

1. Install Python 3.x.
2. Install required libraries:

   ```
   pip install pandas numpy matplotlib seaborn psycopg2
   ```
3. Run the Python scripts:

   ```
   python data_cleaning.py
   python eda_analysis.py
   ```

### PostgreSQL

1. Create a PostgreSQL database.
2. Execute the table creation script.
3. Import the cleaned dataset.
4. Run the SQL queries.

### Power BI

1. Open the `.pbix` file in Power BI Desktop.
2. Refresh the dataset connection if required.
3. Explore the dashboard using filters and visuals.

---

## Skills Demonstrated

* Python Programming
* Data Cleaning
* Exploratory Data Analysis (EDA)
* SQL Query Writing
* PostgreSQL Database Management
* Data Visualization
* Power BI Dashboard Development
* Business Insight Generation
* Technical Documentation

---

## Future Improvements

* Predict customer purchasing behaviour using Machine Learning.
* Build an automated ETL pipeline.
* Connect Power BI directly to PostgreSQL.
* Deploy the dashboard online for real-time reporting.

---

## Conclusion

This project demonstrates an end-to-end data analytics workflow using Python, PostgreSQL, SQL, and Power BI. It highlights how raw customer purchase data can be transformed into meaningful business insights through data cleaning, analysis, visualization, and reporting.

---

**Developed as a Major Project for MCA (Master of Computer Applications).**
