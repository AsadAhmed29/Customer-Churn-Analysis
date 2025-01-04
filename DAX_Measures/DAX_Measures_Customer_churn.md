# Power BI Measures for Churn Analysis Dashboard

### General Measures
- **Number of Customers**  
  `count('Databel - Data'[Customer ID])`

- **Number of Churned Customers**  
  `sum('Databel - Data'[Churned])`

- **Number of Unique Customers**  
  `DISTINCTCOUNT('Databel - Data'[Customer ID])`

- **Churned**  
  `if('Databel - Data'[Churn Label]="Yes",1,0)`

---

### Averages
- **Avg Extra Data Charges**  
  `AVERAGE('Databel - Data'[Extra Data Charges])`

- **Avg Extra Intl Charges**  
  `AVERAGE('Databel - Data'[Extra International Charges])`

- **Avg_CS_call**  
  `AVERAGE('Databel - Data'[Customer Service Calls])`

---

### Derived Metrics
- **Churn Rate**  
  `[Number of Churned Customers]/[Number of Customers]`

---

### Categorization Measures
- **Contract Category**  
  `SWITCH('Databel - Data'[Contract Type], "One Year", "Yearly", "Two Year", "Yearly", "Monthly")`

- **Demographics**  
  `if('Databel - Data'[Senior]="Yes","Senior",If('Databel - Data'[Under 30]="Yes","Under 30","Other"))`

- **Grouped Consumption**  
  `IF('Databel - Data'[Avg Monthly GB Download]<5,"Less than 5 GB", IF('Databel - Data'[Avg Monthly GB Download]<10,"Between 5 and 10 GB","10 or more GB"))`
