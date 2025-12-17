# Customer Churn Analysis Dashboard - Databel Telecom (Power BI Case Study)

A comprehensive Power BI project analyzing customer churn for Databel, a fictitious telecom company. This case study demonstrates end-to-end churn analysis including exploratory data analysis, DAX measures, advanced visualizations, and actionable insights to reduce customer attrition in a subscription-based business.

---

## 📋 Problem Statement

Databel, a telecom company, is experiencing customer churn and needs to understand why customers are leaving. As a Data Analyst, the goal is to:

- Calculate and understand the current churn rate
- Identify key reasons why customers are churning
- Analyze churn patterns across different customer segments (demographics, geography, contract types, services)
- Investigate which factors have the strongest impact on churn
- Provide data-driven recommendations to reduce churn and improve customer retention

---

## 🎯 Business Questions Addressed

1. What is Databel's current customer churn rate?
2. Why are customers churning at the rate they are?
3. How can Databel reduce customer churn?
4. Which customer demographics are most likely to churn (age, gender, group membership)?
5. Are there geographic patterns in customer churn?
6. How do different contract types (monthly, yearly, two-year) impact churn?
7. Which payment methods correlate with higher/lower churn rates?
8. Do international calling plans affect churn?
9. What is the relationship between data plan usage and churn?

---

## 📊 Dataset Overview

**Source:** Databel telecom customer data (fictitious company)  
**Format:** CSV files  
**Grain:** Individual customer records  

**Key Fields:**
- Customer ID, Account Length
- Churn Status (Yes/No)
- Churn Reason Category
- Demographics: Age, Gender, Senior Citizen Status
- Geographic: State, International Plan
- Contract Information: Contract Type, Payment Method
- Service Details: Data Plan, Unlimited Plan, International Calls
- Usage Metrics: Monthly Charges, Customer Service Calls

---
## Snapshots from Power BI  

<p  align="center"><img width="80%" src="https://github.com/SatyamSingh1299/Customer_Churn_PowerBI/blob/main/images/img1.png" /></a></p>  

<p  align="center"><img width="80%" src="https://github.com/SatyamSingh1299/Customer_Churn_PowerBI/blob/main/images/img2.png" /></a></p>  

<p  align="center"><img width="80%" src="https://github.com/SatyamSingh1299/Customer_Churn_PowerBI/blob/main/images/img3.png" /></a></p>  

<p  align="center"><img width="80%" src="https://github.com/SatyamSingh1299/Customer_Churn_PowerBI/blob/main/images/img4.png" /></a></p>  

<p  align="center"><img width="80%" src="https://github.com/SatyamSingh1299/Customer_Churn_PowerBI/blob/main/images/img5.png" /></a></p>  
 
<p  align="center"><img width="80%" src="https://github.com/SatyamSingh1299/Customer_Churn_PowerBI/blob/main/images/img6.png" /></a></p>  

<p  align="center"><img width="80%" src="https://github.com/SatyamSingh1299/Customer_Churn_PowerBI/blob/main/images/img7.png" /></a></p>  

<p  align="center"><img width="80%" src="https://github.com/SatyamSingh1299/Customer_Churn_PowerBI/blob/main/images/img8.png" /></a></p>  

<p  align="center"><img width="80%" src="https://github.com/SatyamSingh1299/Customer_Churn_PowerBI/blob/main/images/img9.png" /></a></p>  

<p  align="center"><img width="80%" src="https://github.com/SatyamSingh1299/Customer_Churn_PowerBI/blob/main/images/img10.png" /></a></p>


  
## 🛠️ Technical Skills & Techniques Demonstrated

### Data Preparation & Exploration
- **Power Query Transformations:**
  - Loading and cleaning CSV data
  - Data quality checks and validation
  - Column profiling and data type management
  
- **Exploratory Data Analysis:**
  - Initial dataset exploration
  - Identifying data patterns and anomalies
  - Understanding data distributions

### DAX (Data Analysis Expressions)

#### Calculated Columns:
- Age group categorization (binning customers by age brackets)
- Tenure categories
- Churn reason groupings
- Customer segmentation fields

#### Measures:
- **Churn Rate Calculation:** `Churned Customers / Total Customers`
- **Customer Count:** Total active and churned customers
- **Churn Reason Analysis:** Breakdown by primary churn categories
- **Demographic Metrics:** Churn rates by age group, gender, group membership
- **Geographic Analysis:** State-level and international churn patterns
- **Contract Analysis:** Churn rates by contract type
- **Service Analysis:** Impact of unlimited plans, international calls, data plans on churn

#### Advanced DAX Techniques:
- CALCULATE function for filtered measures
- DIVIDE function for safe percentage calculations
- ALL/ALLEXCEPT for removing/preserving filters
- Conditional logic with IF/SWITCH statements
- Multiple field aggregations

### Data Visualization & Dashboard Design

#### Custom Visuals:
- **Churn Overview KPI Cards:** Total churn rate, churned vs. retained customers
- **Churn Reason Breakdown:** Bar/column charts showing top churn drivers
- **Demographic Analysis:** Age group and gender churn comparisons
- **Geographic Maps:** State-level churn visualization
- **Contract Type Analysis:** Churn by monthly/yearly/two-year contracts
- **Payment Method Insights:** Churn patterns by payment type
- **Service Adoption Impact:** Unlimited plan, international plan correlations

---

## 📈 Report Pages & Structure

### 1. Exploratory Analysis  
- Analyzing customer churn in Power BI
- Understanding the analysis process
- Data quality checks and validation
- Understanding churn metrics
- Calculating churn rate
- Investigating initial churn reasons
- Digging deeper into churn categories
- Using maps for geographic analysis

### 2. Investigating Churn Patterns  
- Zooming out for broader patterns
- Analyzing demographics (age, gender)
- Age group segmentation
- Inspecting customer groups
- Multiple field investigations
- Unlimited plan analysis
- International calling patterns
- Contract type impact on churn

### 3. Visualizing Your Analysis  
- Creating a cohesive story
- Dashboard design best practices
- Building the overview page
- Age brackets and groups visualization
- Payment method and contract category analysis
- International and data plan insights
- Additional insights and findings
- Final wrap-up and recommendations

---

## 🔑 Key Insights & Recommendations

**Insights:**
- Overall churn rate: **26.5%**
- Top churn reason: **Competitor offerings** (better pricing, devices, services)
- Month-to-month contracts show **3x higher churn** than annual contracts
- Customers with international plans but not making international calls have higher churn
- Senior citizens (65+) represent a high-risk churn segment
- California shows the highest state-level churn rate

**Recommended Actions:**
1. **Contract Incentives:** Encourage migration from monthly to annual contracts with discounts
2. **Competitive Analysis:** Review competitor pricing and adjust value propositions
3. **Targeted Retention:** Develop retention campaigns for high-risk segments (seniors, monthly contracts)
4. **Service Optimization:** Right-size international plans based on actual usage
5. **Customer Service:** Improve response times and service quality to reduce service-related churn
6. **Geographic Focus:** Investigate California market dynamics and implement region-specific strategies

---


