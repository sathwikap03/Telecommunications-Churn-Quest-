#  Telecom Customer Churn Analysis  
###  Understanding customer behavior to reduce churn and improve retention  

##  Project Overview  
This project analyzes customer churn data from a telecom company to uncover key factors influencing customer turnover.  
The interactive Excel dashboard summarizes usage patterns, plan preferences, and churn behavior to help design data-driven retention strategies.  

##  Dataset  
**File:** "Telecom_ChurnQest_Analysis.xlsx"  
**Source:** Simulated telecom customer dataset  

**Description:**  
The dataset includes customer-level details such as:  
- Demographics: 'State', 'Area Code'  
- Account Info: 'Account Lengt', 'Customer Service Calls'  
- Plan Subscriptions: 'International Plan', 'Voice Mail Plan'  
- Usage Metrics: 'Day', 'Evening', 'Night', 'International' minutes, calls, and charges  
- Target Variable: 'Churn (Yes/No)'  

##  Tools & Techniques Used  
- **Microsoft Excel**  
- **PivotTables & PivotCharts**  
- **Formulas:** 'COUNTIF', 'AVERAGEIF', 'CORREL', 'GETPIVOTDATA'  
- **KPI Cards Design**  
- **Interactive Slicers** for filtering  
- **Conditional Formatting**  

##  Project Workflow  

### 1️ Data Cleaning & Preparation  
- Verified and formatted categorical fields like *Churn*, *International Plan*, *Voice Mail Plan*   
- Created calculated fields for churn metrics and customer usage  

Analyzed:  
- Churn count and churn percentage  
- Average account length (Churned vs. Retained)  
- Effect of *International* and *Voice Mail* plans on churn  
- Relationship between *Customer Service Calls* and churn  
- Usage vs. Churn patterns (Day, Evening, Night, Intl)  

- **Area Code–wise Churn Segmentation**  
- **Service Call Thresholds (>3 calls)** vs Churn  
- **Correlation** between Account Length and Churn  
- **International Charges** impact on Plan Subscribers  
- **Evening Usage Patterns** and Churn behavior  
- **Voice Mail Usage** interaction analysis  

##  Dashboard Features  

###  KPI Cards  
-  Total Customers  
-  Churned Customers  
-  Churn Rate (%)  
-  Average Account Length (Churned vs. Retained)  

###  Charts    
- Percentage of Churned and Non-Churned Customers — *Donut Chart*  
- International Plan vs Churn — *Clustered Column Chart*
- Churn Rate by Area Code — *Clustered Bar Chart*
- Average customer service calls vs Churn — *pie chart*
- Average Account length vs Churn — *Clustered Column Chart*
- Day Minutes vs Churn
  
###  Interactive Filters  
- State  
- Area Code  
- International Plan  
- Voice Mail Plan  

##  Key Insights  
- Customers with **International Plans** show significantly higher churn rates.  
- **Frequent Customer Service Callers** (-3 calls) are more likely to churn.  
- **New customers** (shorter account length) have a higher churn risk.    
- **Evening usage patterns** vary but show no direct churn trigger.  

##  How to Use  
1. Download the Excel file **`Telecom_Churn_Analysis.xlsx`**  
2. Open the **Dashboard** sheet  
3. Use **Slicers** to filter by 'State', 'Area Code', or 'Plan Type'  
4. Hover over **KPI Cards** for detailed values  
5. Explore **PivotTables** in the Data Analysis sheet for deeper insights  

##  Future Improvements  
- Automate data refresh using **Power Query**  
- Build a **Power BI version** for deeper interactivity  
- Integrate **Predictive Modeling** in Python or Excel  
- Add **Real-Time Data Updates** from telecom APIs  

##  Results Summary  
The project revealed valuable insights into churn behavior — helping identify high-risk customer segments and retention opportunities.  
By improving support experiences, pricing strategies, and engagement for new users, telecom providers can significantly reduce churn and boost loyalty.  

---

##  Author  
**Pudota Sathwika**  
 [GitHub Profile](https://github.com/sathwikap03)  
 Email: [sathwikap03@gmail.com]  

