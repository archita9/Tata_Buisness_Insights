# Tata_Buisness_Insights[ Retail Sales Analytics Dashboard (Power BI)]

## Overview

This project was completed as part of the **Tata Data Visualisation: Empowering Business with Effective Insights** Job Simulation on Forage.

The objective was to analyze an online retail dataset, clean the data, build interactive Power BI dashboards, and provide business insights to support executive decision-making.

---

## Business Problem

The CEO and CMO wanted to understand:

- Monthly revenue trends
- Top-performing countries
- High-value customers
- Product demand across countries

The analysis was used to identify growth opportunities and support future business expansion.

---

## Tools & Technologies

- Power BI
- Power Query
- DAX
- Microsoft Excel

---

## Data Cleaning

Before building the dashboard, the dataset was cleaned using Power Query.

The following steps were performed:

- Removed invalid records with zero or negative Unit Price
- Fixed Invoice Date data type and formatting issues
- Removed error values
- Filtered unnecessary records
- Verified data quality before visualization

---

## DAX Measures

### Total Revenue

```DAX
Total Revenue =
SUMX(
    'Online Retail Data Set',
    'Online Retail Data Set'[Quantity] *
    'Online Retail Data Set'[UnitPrice]
)
```

### Total Quantity

```DAX
Total Quantity =
SUM('Online Retail Data Set'[Quantity])
```

---

## Dashboard Visualizations

### 1. Monthly Revenue Trend (2011)

**Objective**

Analyze monthly revenue performance during 2011 to identify seasonal trends.

**Insights**

- Revenue fluctuated across the year.
- Peak months indicate periods of higher customer demand.
- Useful for inventory and sales planning.
  <img width="1140" height="617" alt="image" src="https://github.com/user-attachments/assets/37ff529b-bc9e-46b8-be9f-06291a669a92" />


---

### 2. Top 10 Countries by Revenue (Excluding United Kingdom)

**Objective**

Identify the highest revenue-generating countries outside the UK.

**Insights**

- Excluding the UK prevents one country from dominating the analysis.
- Helps identify international markets with strong business potential.
<img width="1170" height="626" alt="image" src="https://github.com/user-attachments/assets/68d6812d-c32d-4586-b8a6-0e4f4c7c8d74" />

---

### 3. Top 10 Customers by Revenue

**Objective**

Identify customers contributing the highest revenue.

**Insights**

- Highlights high-value customers.
- Supports customer retention and loyalty strategies.
<img width="1128" height="647" alt="image" src="https://github.com/user-attachments/assets/a93c6769-0d1b-4d81-bd60-36008631bce4" />

---

### 4. Demand by Country

**Objective**

Visualize product demand using Total Quantity sold by country.

**Insights**

- Shows countries with the highest purchasing demand.
- Supports inventory planning and expansion decisions.

---

## Business Recommendations

- Focus marketing efforts on high-performing international markets.
- Strengthen relationships with top customers through loyalty programs.
- Optimize inventory based on demand by country.
- Plan promotions around high-revenue periods.


## Project Outcomes

- Performed end-to-end data cleaning using Power Query.
- Built DAX measures for business KPIs.
- Developed interactive executive dashboards.
- Delivered business insights using Power BI visualizations.

---

## Acknowledgement

This project was developed as part of the **Tata Data Visualisation: Empowering Business with Effective Insights** Job Simulation offered by **Forage**.

The dashboard, analysis, and implementation were completed using Power BI based on the simulation requirements.



Skills:
- Power BI
- Power Query
- DAX
- Excel
- SQL
- Data Visualization
