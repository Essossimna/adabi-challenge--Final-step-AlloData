# ADABI Challenge - Final Step by AlloData

## Enhancing Customer Relationships through KPIs

🔗 [View the original LinkedIn post here]  https://tinyurl.com/mtdf477b

 **AlloData** was selected for the second phase of the **ADABI Challenge 2025**, a pan-African data competition where Business Intelligence meets customer strategy.

## Project Objective

To improve **customer relationship management** using data from five West and Central African countries: **Togo, Burkina Faso, Côte d'Ivoire, Cameroon, and Senegal**.


##  Methodology

### A) Dataset Overview

The dataset included four main CSV files:

- `clients.csv` – 1,000 rows, 9 columns  
- `sales.csv` – 1,000 rows, 8 columns  
- `purchases.csv` – 1,000 rows, 9 columns  
- `stock.csv` – 600 rows, 5 columns  

Stores were distributed across 5 countries with **12 unique retail locations**.

### B) Data Cleaning and Preprocessing

- **Date formatting** was standardized to `DD/MM/YYYY`, handling multiple formats like `YYYY-MM-DD`, `1 janvier 2024`, etc.
- **Missing values**:
  - For dates: used the mode (most frequent value) per store
  - For numeric values: used the median

### C) Feature Engineering

Several new features were created to better understand customer behavior:

- **Recency, Frequency, Monetary (RFM)** indicators  
- **Customer status**: active/inactive  
- Derived features like **customer tenure**, **average delay between purchases**


##  Key Insights

- **55.9% of customers** are inactive  
- Strong **correlation between number of clients and revenue**, but **average basket size** drives profitability
- Clear **regional disparities** in performance
- **Three distinct customer segments** emerged based on behavior

##  Country-Specific Findings

### Burkina Faso
- **Store 11** drives strong sales due to high client volume.
- Stores 10 and 12 underperform despite selling more — due to low product pricing.

**Actions:**
- Adjust product mix to increase average basket size
- Promote premium bundles; train staff for upselling


### Côte d'Ivoire
- **Store 2** outperforms Store 1 on all KPIs

**Actions:**
- Focus marketing and stock resources on Store 2


### Togo
- **Store 5** dropped from leader in 2024 to lowest in 2025

**Actions:**
- Conduct customer satisfaction surveys
- Reassess local pricing/offers
- Launch targeted win-back campaigns


### Cameroon
- Store 7 was top in 2024, but Store 6 caught up in 2025 with fewer clients but a higher basket size

**Actions:**
- Strengthen premium offering in Store 6
- Train staff on consultative selling


### Senegal
- **Stores 8 & 9** balanced in 2025, after Store 9 led before

**Actions:**
- Launch joint marketing campaigns
- Share Store 9’s best practices across teams


##  Strategic Recommendations

### Cross-Country Actions

- **Reactivation email campaigns**: for inactive clients, promotions, and loyalty gifts  
- **Onboarding bonuses** in low-activity areas  
- **A/B testing** offers by region and customer type  
- **Optimize product mix** per store  
- **Local satisfaction surveys** where sales dropped  
- **Proactive stock monitoring** to prevent lost sales and customer churn  

##  Team

**Project:** AlloData  
**Analyst:** Essossimna BESSEPOU


##  Let's Call Data to Action!

With AlloData, we believe insight must lead to **real, local impact**.  
This project demonstrates how KPIs can drive meaningful customer strategies across African markets.

Feel free to explore the dashboards, reuse the methodology, or open an issue for collaboration!
