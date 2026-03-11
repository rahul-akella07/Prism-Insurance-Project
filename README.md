

# 📊 Insurance Analytics Dashboard (Power BI + SQL)

## Dashboard Link
https://app.powerbi.com/groups/me/reports/7cab8c8b-05ee-49dd-9ba5-2421ee7fc091/282afb5cb75d109896d4?experience=power-bi

A **complete end-to-end data analytics project** built using **SQL, Power BI, and data modeling techniques** to analyze insurance customer data, policy performance, and premium trends.

This project demonstrates how raw insurance data can be transformed into **interactive business intelligence dashboards for decision making**.

---

# 🚀 Project Overview

The goal of this project is to simulate a **real-world insurance analytics environment** where data analysts must:

* Clean raw policy data
* Model data relationships
* Create meaningful KPIs
* Build interactive dashboards

The final output is a **Power BI dashboard** that provides insights into:

* Policy distribution
* Customer demographics
* Premium revenue
* Policy lifecycle trends



# 🏗️ Project Architecture

```
Raw Data
   ↓
Data Cleaning
   ↓
SQL / Data Transformation
   ↓
Power BI Semantic Model
   ↓
Data Modeling
   ↓
DAX Measures
   ↓
Interactive Dashboard
```



# 📊 Dataset Description

The dataset contains **insurance policy and customer information**.

### Key Columns

| Column          | Description                |
| --------------- | -------------------------- |
| PolicyNumber    | Unique insurance policy ID |
| CustomerID      | Unique customer identifier |
| Gender          | Customer gender            |
| Age             | Customer age               |
| PolicyType      | Type of insurance policy   |
| PolicyStartDate | Policy activation date     |
| PolicyEndDate   | Policy expiry date         |
| PremiumAmount   | Premium paid by customer   |

---

# 🛠️ Tools Used

| Tool                        | Purpose                                |
| --------------------------- | -------------------------------------- |
| **SQL**                     | Data generation and transformation     |
| **Power BI**                | Data visualization                     |
| **DAX**                     | KPI calculations                       |
| **Power BI Semantic Model** | Data relationships & modeling          |
| **GitHub**                  | Version control and portfolio showcase |

---

# 🔄 Data Processing Steps

### 1️⃣ Data Collection

Insurance data was collected and structured into tabular format including:

* Policy details
* Customer demographics
* Premium values
* Policy timelines

---

### 2️⃣ Data Cleaning

Performed preprocessing to ensure consistency:

* Removed duplicate policy numbers
* Standardized policy types
* Handled missing values
* Verified date formats

---

### 3️⃣ Data Modeling

A **Power BI semantic model** was created to define relationships and enable efficient analytics.

The model includes:

* Fact table: **InsuranceData**
* Date tables for time analysis
* Policy lifecycle tracking

---

### 4️⃣ Relationship Management

Relationships were defined between:

* Policy start dates
* Policy end dates
* Date dimension tables

This allows proper **time-based analytics**.

---

### 5️⃣ DAX Measures Created

Examples of calculated measures:

```DAX
Total Premium = SUM(InsuranceData[PremiumAmount])

Average Customer Age = AVERAGE(InsuranceData[Age])

Total Policies = COUNT(InsuranceData[PolicyNumber])
```

These metrics power the visualizations in the dashboard.

---

# 📈 Dashboard Features

The dashboard provides insights such as:

### Policy Analysis

* Total policies issued
* Policies by type
* Policy lifecycle trends

### Customer Demographics

* Age distribution
* Gender segmentation
* Policy adoption patterns

### Financial Insights

* Total premium revenue
* Premium trends over time
* Revenue by policy type

---

# 📷 Dashboard Snapshot

https://github.com/user-attachments/assets/e7b0c30d-0274-4f6b-a88a-2641c1416b65

https://github.com/user-attachments/assets/b9800a8d-de2c-4bb4-85b9-10d42b1f01db


# 🎯 Key Insights

Some insights generated from the dashboard include:

* Certain policy types generate the **highest premium revenue**
* Specific **age groups dominate policy purchases**
* Premium collections follow **clear time-based trends**
* Gender distribution shows differences in policy adoption

---

# 💡 Skills Demonstrated

This project demonstrates strong skills in:

* Data Modeling
* Power BI Development
* SQL Data Handling
* DAX Calculations
* Business Intelligence
* Dashboard Design








