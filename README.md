# Customer Churn Analysis Dashboard

## Project Objective
To design a Power BI dashboard that provides a detailed analysis of customer churn, enabling stakeholders to identify trends and make data-driven decisions to reduce churn and improve customer retention.

---

## Workflow Overview
The dataset was provided by DataCamp in CSV files. The Power BI dashboard consists of four key pages, each offering unique insights into customer churn. Below is the breakdown of each report page.

---

## 1. Overview

**Objective**: Provide a high-level summary of customer churn and key performance indicators (KPIs).

### Visuals:
- **KPIs (Cards)**:
  - Total Customers
  - Total Churned Customers
  - Churn Rate
- **Total Customers vs. Churned Customers**:  
  A clustered bar chart showing the proportion of leading reasons that drive churned customers to leave our product.
- **Churn by Category**:  
  An extension of the clustered bar chart, categorizing reasons into logical groups like competitor, price, dissatisfaction, etc.
- **Churn Rate by State**:  
  A map indicating the extent of the churn rate in each state.

### Insights:
- Competitor offering better services and the bad attitude from our employees (support staff/service staff) seem to be the leading causes.  
- California and Ohio have the highest churn rate among all states.

---

## 2. Demographics

**Objective**: Analyze customer demographics to understand which groups are more likely to churn.

### Visuals:
- **Churn by Gender**:  
  A pie chart illustrating churn rates for male and female customers.
- **Churn by No. of Customers in a Group**:  
  A line and clustered column chart highlighting churn trends with the number of customers in groups.
- **Churn by Age Groups**:  
  A line and column chart showing how customer churn rate behaves in different age groups.
- **Filter by Account Length**:  
  A page-level filter for account length (in months).

### Insights:
- We have the lowest number of customers and the highest churn rate in ages above 60. Offering tailored packages or campaigns for this demographic could help retention.  
- Grouped customers have significantly lower churn rates compared to stand-alone customers. Incentivizing group registrations at the time of onboarding could improve retention.  
- The number of customers and churn rates in both genders are almost identical, indicating balanced service quality across genders.

---

## 3. Payment & Contract

**Objective**: Examine how payment methods and charges impact churn behavior.

### Visuals:
- **KPIs (Cards)**:
  - Average Account Length (months)
  - Average Customer Service Calls
  - Churn Rate
- **Churn by Payment Method**:  
  A pie chart showing churn distribution by payment types (e.g., credit card, electronic check).  
- **Account Length vs. Churn Rate**:  
  A scatter plot visualizing the relationship between account length and churn rates, segmented by payment method.  
- **Churn Rate by Account Length**:  
  A line chart showing the relationship between account length and churn rates.

### Insights:
- Retention drops significantly from 62% to 43% after the first 5 months, highlighting the need for focused customer service during this critical period.  
- Yearly contracts greatly reduce churn, emphasizing their effectiveness in retaining customers.  
- Paper check payments show the lowest churn rate, but the small sample size (371 customers) limits its reliability.  
- Credit card payments combined with yearly contracts yield the highest retention rates, making this combination a key target for retention strategies.

---

## 4. Extra Charges

**Objective**: Investigate additional factors contributing to churn, such as service type and contract terms.

### Visuals:
- **Churn Rate by Consumption and Plan**:  
  A bar chart showing churn rates for grouped consumption, categorized by whether the consumers have an unlimited data plan or not.  
- **Average Extra Data Charges by State**:  
  A map showing the extent of extra data charges for each state.  
- **Average Extra International Charges by State**:  
  A map showing the extent of extra international charges for each state.

### Insights:
- Customers with unlimited data plans but usage below 5GB/month show a high churn rate, indicating a need to notify them of unnecessary services.  
- A significant churn rate (71.19%) is observed among customers without active international services but with an international plan they likely don’t use.  
- Extra data charges are localized to specific states, while extra international charges pose a nationwide challenge, emphasizing the need for more robust and appealing international plans.
