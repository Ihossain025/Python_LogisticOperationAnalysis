# 🚚 Logistics Data Analysis

## Project Overview

This project was completed as the final course project of a Data Analytics Weiterbildung Program at Alfatraining GmbH.

A fictional logistics company wanted to analyze its logistics operational data to identify opportunities for improving profitability and fleet performance.

The analysis focused on:

- Route Profitability Analysis
- Fleet Efficiency Analysis

The project covers the complete Data Analytics workflow:

✔ Data Loading  
✔ Data Cleaning  
✔ Exploratory Data Analysis (EDA)  
✔ Data Aggregation & Table Integration  
✔ Data Visualization  
✔ Business Insights & Recommendations

---

## Business Objective

The goal was to analyze logistics operations and answer key business questions such as:

### Route Profitability

- Which routes are the most profitable?
- Which routes generate the highest costs?
- Which routes provide the highest profit per mile?

### Fleet Efficiency

- How does truck age impact maintenance costs?
- Which manufacturers achieve the best fuel efficiency?
- Which terminals have the highest idle time?
- Which trucks have the highest operational costs?
- Which trucks are most and least utilized?

---

## Dataset

The dataset represents a realistic logistics operation spanning three years.

### Dataset Highlights

- 85,000+ records
- 14 interconnected tables
- 57,000+ loads and trips
- 131,000+ fuel purchase records
- 6,500+ maintenance records

### Main Tables

- Drivers
- Trucks
- Trailers
- Customers
- Routes
- Loads
- Trips
- Fuel Purchases
- Maintenance Records
- Delivery Events

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- PlotlyExpress
- Jupyter Notebook

---

## Project Structure

```text
Logistics-Data-Analysis/
│ Scripts
├── Data_LoadCleanAndEDA.py
├── Fleet_Efficiency_Analysis.py
├── Route_Profitability_Analysis.py
│
├── Dataset/
├── Dataset_after_Cleaned/
├── Images/
└── README.md
```

---

## Analysis Workflow

### 1. Data Preparation

- Loaded and explored datasets
- Handled missing values
- Removed duplicates
- Corrected data types

### 2. Data Modeling

- Aggregated operational data
- Joined multiple relational tables
- Created business KPIs

### 3. Analysis & Visualization

- Route profitability analysis
- Fleet efficiency analysis
- Cost and utilization analysis
- Business-focused visualizations

---

## Key Findings

- 65% of routes achieved positive profit margins.
- Route  *Phoenix to Philadephia* generated the highest Net Profit followed by *Columbus to Los Angles* and then *Columbus to Portland*
- Route *New York to Philadelphia* had the highest operational cost followed by *Portland to Seatle*.
- Manufacturer *Mack* achieved the best average fuel efficiency.
- Fleet Maintenance cost varies significantly with respect to Fleet age. It does not strongly co-relate with fleet age.
- Terminal *Nashville* recorded the highest idle Hours followed by *Philadelphia* and *Columnbus*.
- Truck *TRK00014* had the highest Total Cost of Ownership (TCO) per mile followed by *TRK00038* and *TRK00026*.

---

## Visualizations

### Route Profitability Analysis

#### Which routes are most/least profitable?
![Route Profitability](Images/Route_Profitability.jpg)

#### Which routes cost the most to run, and why?
![Route Cost](Images/Route_Cost.jpg)

#### Which routes give us the best financial buffer per mile?
![Route Profitability Buffer](Images/Route_Revenue_vs_Cost.jpg)


### Fleet Efficiency Analysis

#### Which Fleet Manufacturer has highest Fuel Efficiency?
![Fuel Efficiency by Manufacturer](Images/Fuel_Efficiency_by_Manufacturer.jpg)

#### Which Home Terminals have high idle time?
![Average Idle Time by Home Terminal](Images/Idle_Time_by_Home_Terminal.jpg).

#### Does Maintenance Cost increase as Fleet ages?
![Fleet Maintenance Cost vs Fleet Age](Images/Maintenance_Cost_vs_Truck_Age.jpg).

---

## How to Run the Project

### Clone the Repository

```bash
git clone https://github.com/Ihossain025/logistics-data-analysis.git
```

### Navigate to Project Folder

```bash
cd logistics-data-analysis
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Scripts

```bash
python Data_LoadCleanAndEDA.py

python Fleet_Efficiency_Analysis.py

python Route_Profitability_Analysis.py
```

---

## Requirements

Example `requirements.txt`

```text
Python
pandas
numpy
matplotlib
seaborn
plotlyexpress
jupyterlab
```

---

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Wrangling
- Data Aggregation
- Relational Data Analysis
- Business Analysis
- Data Visualization
- Data Storytelling
- Insight Generation

---

## About Me

I am an aspiring Data Analytics Professional with a background in Business, Engineering, and IT. I am currently building my portfolio through hands-on projects involving Python, SQL, Power BI, and Business Analytics.

**LinkedIn:** https://www.linkedin.com/in/md-iqbal-hossain-9a2a2312b/

