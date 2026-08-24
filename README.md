# Super Store Sales Analysis

## Project Overview

This project presents an interactive **Super Store Sales Analysis Dashboard** developed in **Tableau** to analyze sales, profit, order quantity, regional performance, and customer segment behavior.

The project started with **data cleaning and preparation in Microsoft Excel**, followed by data visualization and analysis in **Tableau**. New calculated fields were also created in Tableau to derive meaningful categories and analytical metrics.

The dashboard provides an interactive view of business performance and helps identify regional sales contribution, profitable customer segments, sales-profit relationships, and monthly order trends.

---

## Objectives

- Analyze sales performance across different regions.
- Evaluate profit contribution by region and customer segment.
- Understand sales contribution of each region.
- Analyze the relationship between Sales and Profit.
- Track monthly order quantity trends.
- Create meaningful calculated fields for deeper analysis.
- Build an interactive and user-friendly Tableau dashboard.

---

## Tools & Technologies

- **Microsoft Excel** — Data cleaning and preparation
- **Tableau Desktop** — Data visualization and dashboard development
- **Tableau Calculated Fields** — Creating derived metrics and categories
- **Data Visualization** — Charts, filters, KPIs and interactive analysis

---

## Data Preparation & Cleaning in Excel

Before importing the dataset into Tableau, the data was reviewed and cleaned in **Microsoft Excel** to improve data quality and ensure consistency.

The data preparation process included:

- Reviewing the dataset for missing or inconsistent values.
- Checking column names and data types.
- Removing unnecessary or irrelevant data where required.
- Checking for duplicate or inconsistent records.
- Standardizing categorical values.
- Verifying numerical fields such as Sales, Profit and Order Quantity.
- Ensuring the dataset was properly structured for Tableau analysis.
- Preparing the cleaned dataset for visualization and analysis.

This step helped ensure that the Tableau dashboard was based on clean and reliable data.

---

# Tableau Dashboard

## Dashboard Title

**Super Store Sales Analysis**

The final Tableau dashboard contains multiple interactive visualizations designed to provide an overall view of sales and profitability.

### Main Dashboard Components

1. Profit by Region and Customer Segment
2. Sales and % Sales Contribution by Region
3. Profit V/S Sales
4. Order Quantity by Month
5. Unit Price Group Filter
6. Interactive filtering and dashboard interactions

---

## 1. Profit by Region and Customer Segment

A stacked horizontal bar chart was created to analyze **profit across different regions and customer segments**.

### Regions Analyzed

- Central
- East
- South
- West

### Customer Segments

- Small Business
- Home Office
- Corporate
- Consumer

This visualization makes it possible to compare the contribution of different customer segments within each region.

### Key Insights

- **Central** shows a strong overall profit contribution, with Corporate and Home Office segments making substantial contributions.
- **East** has a strong contribution from the Corporate segment.
- **South** shows particularly strong Corporate and Consumer profitability.
- **West** also demonstrates meaningful profit contribution, particularly from Corporate and Small Business customers.
- Customer segment performance varies considerably between regions, indicating that regional strategies can be optimized based on customer type.

---

## 2. Sales and % Sales Contribution by Region

A pie chart was used to show both **total sales and percentage contribution by region**.

### Regional Sales

| Region | Sales | Sales Contribution |
|---|---:|---:|
| Central | 4,699,167 | 31.51% |
| West | 3,649,748 | 24.47% |
| East | 3,416,466 | 22.91% |
| South | 3,150,219 | 21.12% |

### Key Insights

- **Central is the highest-performing region**, contributing approximately **31.51% of total sales**.
- **West ranks second** with approximately **24.47%**.
- **East contributes 22.91%** of total sales.
- **South has the lowest contribution at 21.12%**.
- Central's sales contribution is significantly higher than the other individual regions, making it an important market for the business.

---

## 3. Profit V/S Sales

A scatter plot was created to examine the relationship between **Sales and Profit**.

### Purpose

This visualization helps identify:

- High-sales transactions
- High-profit transactions
- Low-profit transactions
- Potentially negative-profit transactions
- The overall relationship between sales volume and profitability

### Key Insights

- Most transactions are concentrated within the lower-to-middle sales range.
- Higher sales values generally tend to be associated with higher profit values, although the relationship is not perfectly linear.
- Some transactions with relatively high sales generate comparatively low or negative profit.
- This indicates that **high sales do not always guarantee high profitability**.
- The scatter plot can help identify transactions that may require further investigation because of weak profitability.

---

## 4. Order Quantity by Month

A monthly line chart was created to analyze **order quantity throughout the year**.

### Monthly Order Quantity

| Month | Order Quantity |
|---|---:|
| January | 17,952 |
| February | 16,602 |
| March | 17,264 |
| April | 17,270 |
| May | 21,273 |
| June | 16,534 |
| July | 17,929 |
| August | 18,067 |
| September | 19,116 |
| October | 18,278 |
| November | 16,251 |
| December | 18,241 |

### Key Insights

- **May records the highest order quantity at 21,273**.
- **November records the lowest order quantity at 16,251**.
- Order quantity shows noticeable fluctuations throughout the year.
- There is a significant increase in orders during May.
- September also demonstrates relatively strong order activity.
- June and November show comparatively lower order quantities.
- The monthly trend can help businesses identify periods of higher and lower demand.

---

# Tableau Calculated Fields

Several **calculated fields** were created in Tableau to enhance the analysis and create meaningful dimensions/metrics.

### Unit Price Group

A calculated grouping was created to categorize records based on **Unit Price**.

The dashboard uses the following groups:

- **A**
- **B**
- **C**

This calculated field was then added as an interactive filter, allowing users to analyze the dashboard based on different unit price categories.

### Sales Contribution

A calculated metric was also used to determine the **percentage contribution of each region to total sales**.

This calculation allows the dashboard to display both:

- Regional Sales
- Percentage of Total Sales

This makes regional performance easier to compare.

### Additional Calculations

Calculated fields were used where required to transform the original dataset into more meaningful analytical dimensions and metrics for visualization.

These calculations reduced the need for manual data manipulation and made the Tableau dashboard more interactive.

---

# Interactive Features

The dashboard includes interactive functionality to allow users to explore the data dynamically.

### Unit Price Group Filter

Users can select:

- All
- A
- B
- C

The filter allows the dashboard visuals to be analyzed for different unit price groups.

### Interactive Dashboard Analysis

The Tableau dashboard also supports interactive exploration through visual selections and filtering, allowing users to investigate specific regions, customer segments and data points.

---

# Key Business Insights

Based on the dashboard analysis, several important insights were identified:

1. **Central is the leading region**, generating approximately **31.51% of total sales**.

2. **West is the second-largest contributor**, accounting for approximately **24.47% of sales**.

3. **South has the lowest regional sales contribution**, at approximately **21.12%**.

4. Profit performance differs across customer segments and regions, showing that customer type plays an important role in regional profitability.

5. **Corporate customers contribute significantly to profitability** across several regions.

6. The Sales vs Profit analysis shows that **higher sales do not always result in proportionally higher profit**.

7. **May has the highest monthly order quantity**, reaching **21,273 orders**.

8. **November has the lowest monthly order quantity**, with **16,251 orders**.

9. Monthly order quantity fluctuates throughout the year, suggesting variations in demand and purchasing activity.

10. The Unit Price Group filter enables deeper analysis of how different price categories affect the overall business performance.

---

# Dashboard Design

The dashboard was designed with a clean and structured layout to make multiple analytical views accessible from a single screen.

### Design Elements

- Interactive filters
- KPI-style numerical labels
- Stacked bar chart
- Pie chart
- Scatter plot
- Monthly line chart
- Consistent dashboard formatting
- Region and customer segment analysis
- Interactive Tableau selections

The dashboard combines multiple visualization types to provide both **high-level business performance** and **detailed transaction-level analysis**.

---

# Project Workflow

```text
Raw Super Store Dataset
          ↓
Data Cleaning & Preparation
       (Microsoft Excel)
          ↓
Cleaned Dataset
          ↓
Data Import into Tableau
          ↓
Calculated Fields Creation
          ↓
Data Analysis
          ↓
Visualizations Development
          ↓
Interactive Dashboard
          ↓
Business Insights
```

---

# Skills Demonstrated

This project demonstrates practical skills in:

- Data Cleaning
- Data Preparation
- Exploratory Data Analysis
- Tableau
- Tableau Calculated Fields
- Data Visualization
- Dashboard Development
- Sales Analysis
- Profit Analysis
- Regional Analysis
- Customer Segment Analysis
- Trend Analysis
- Business Intelligence
- Interactive Data Analysis

---

# Conclusion

The **Super Store Sales Analysis** project demonstrates how raw business data can be transformed into an interactive analytical dashboard using **Excel and Tableau**.

Excel was used to clean and prepare the dataset, while Tableau was used to create calculated fields, develop visualizations and build the final interactive dashboard.

The analysis highlights important differences in regional sales performance, customer segment profitability, sales-profit relationships and monthly order activity. These insights can support better understanding of business performance and help identify areas for further analysis and improvement.

---

## Project Preview

A dashboard walkthrough video is included in this repository to demonstrate the interactive **Super Store Sales Analysis** dashboard and its visualizations.

---

## Tools Used

**Microsoft Excel | Tableau Desktop**

---

## Author

**Syed Bilal Ahmed**

