# Car Repair Service Company Data Analysis

This repository contains an in-depth analysis of a car repair service company, with a special focus on supplier performance, customer satisfaction, and overall sales growth. The analysis is driven by data visualizations and insights generated through **Power BI** dashboards.

---

## 1. Background and Overview

The dataset belongs to a company in the automotive maintenance industry. The business model involves collecting vehicles from customers, outsourcing the repairs to third-party suppliers, and delivering the repaired vehicles back. The company operates in multiple regions and has been active for over six years. This analysis aims to uncover insights to optimize business performance, focusing on the following areas:

- **Sales Growth**: Analyze yearly and monthly sales patterns to identify trends.
- **Supplier Comparison**: Compare the performance of suppliers based on revenue, customer satisfaction, and job delivery times.
- **Product and Service Analysis**: Analyze which car models and job types drive the most revenue and customer satisfaction.

---

## 2. Executive Summary

This data analysis provides insights into the car repair company’s performance across multiple metrics such as sales growth, supplier efficiency, and customer satisfaction. 

### Key Findings:

1. **Supplier Performance**: Supplier SP004 generates the highest revenue, even though he does not maintains the fastest job completion time, but has above average customer satisfaction. Supplier SP009 Has the highest average customer rating and slightly better job completion time but generated less revenue due to the number of jobs and amount per jobs.
2. **Sales Trends**: Significant increases in sales were observed in August and September, coinciding with seasonal factors such as the rainy season.
3. **Product and Service Trends**: The **Toyota Camry** was the most serviced car model, and specific job types were linked to higher customer satisfaction.

### Recommendations:

1. **Optimize Supplier Performance**: Prioritize assigning jobs to **Supplier SP009**, who performs the best in terms of job completion time and customer satisfaction.
2. **Targeted Marketing**: Capitalize on the increased demand during the rainy season (August and September) with targeted campaigns.
3. **Improve Service for Lower-Rated Suppliers**: Address areas of improvement for suppliers with lower performance, such as **Supplier SP004 & SP005**.

---

## 3. Data Structure and Initial Checks

### Entity-Relationship Diagram (ERD)

![ERD](https://github.com/user-attachments/assets/8e0bcb81-2827-450a-8474-2dbf71e4f7db)

The data structure consists of the following tables:

- **Customers**: Contains customer demographics and details.
- **Cars**: Includes car model information.
- **Jobs**: Lists job types and repair details.
- **Suppliers**: Supplier details such as job completion time, revenue per job, and ratings.
- **Sales**: Revenue, job completion times, and other sales metrics.

---

## 4. Analysis Insights

### 4.1 Yearly Growth and Sales Analysis

**Objective**: Analyze overall sales growth over the years and identify key months of high sales activity.

**Key Insight**:
- Sales tend to increase in August and September, coinciding with the rainy season, which typically leads to more vehicle repairs.

#### Visualization:
![Month Revenue](https://github.com/user-attachments/assets/8fb433dd-0942-457c-86e5-67a968881f20)

---

### 4.2 Regional Analysis

**Objective**: Analyze sales and job distribution across different regions.

**Key Insight**:
- The **Omdurman** region has the highest demand for car repair services, followed by **Khartoum**.

#### Visualization:
![Location](https://github.com/user-attachments/assets/af3288e6-9b58-42c6-8ac2-1f567a3e2c60)

---

### 4.3 Product and Service Analysis

**Objective**: Analyze the car models and types of repairs that contribute the most to revenue.

**Key Insight**:
- The **Toyota Camry** is the most serviced car model, contributing significantly to total revenue.
- **Engine repairs** and **bodywork** jobs are associated with higher customer satisfaction compared to other job types.

#### Visualization:
![Revenue Car](https://github.com/user-attachments/assets/27b07068-65ba-4522-8f12-69add901f6cd)

---

### 4.4 Supplier Analysis

**Objective**: Compare the performance of suppliers based on total revenue generated, average job completion time, and customer satisfaction ratings.

#### Supplier Performance Overview

- **Supplier SP003**: 
  - **Total Revenue**: 1.6 M (Highest Revenue).
  - **Customer Rating**: 2.88/5 (lowest rating).
  - **Average Job Time**: 31.8 days (moderate completion time).
  
- **Supplier SP009**:
  - **Total Revenue**:  1.48 M (Moderate revenue generation).
  - **Customer Rating**: 3.09/5 (highest rating).
  - **Average Job Time**: 31.24 days (better than average completion time)
  
- **Supplier SP001**:
  - **Total Revenue**: 1.47 M (Slightly Below average).
  - **Customer Rating**: 3/5 (moderate rating).
  - **Average Job Time**: 32 days (longest completion time).

#### Visualization:
![Supplier revenue](https://github.com/user-attachments/assets/6e08ac26-8807-4dba-b5ba-736a1f75c2d4)
![Supplier vs amount per job vs customer rating](https://github.com/user-attachments/assets/653e5484-b319-4c8a-9efb-c04f52825234)

---

### 4.5 Customer Satisfaction by Car Model and Supplier

**Objective**: Analyze customer satisfaction ratings based on the car models serviced and the suppliers used.

**Key Insight**:
- Customers tend to give higher satisfaction ratings for repairs on **Kia and Toyota**.
- There is a clear trend showing that as the average job time increases, customer satisfaction ratings decrease.

#### Visualization:
![Job duration vs Cus rating](https://github.com/user-attachments/assets/959e3547-b98b-4b99-9428-164c446cf4a0)
![Revenue car model vs vs](https://github.com/user-attachments/assets/6aaf2166-f59a-41f5-baa1-d4221b399ac3)

---

## 5. Recommendations

1. **Optimize Supplier Performance**:
   - Focus more jobs towards **Supplier SP009**, as they have the best performance in terms of customer ratings and good job time to increase the revenue from it.
   - Consider improving **Supplier SP004** through additional training to reduce job time and enhance customer service.

2. **Target Marketing During Rainy Season**:
   - Invest in targeted marketing campaigns in August and September to take advantage of increased demand during the rainy season.

3. **Improve Service for Low-Rating Suppliers**:
   - Address the issues with suppliers who are receiving lower customer satisfaction ratings, particularly **SP001**.

---

## 6. Assumptions and Caveats

1. **Assumption 1**: Data is generated using Python to mimick real world data.
2. **Assumption 2**: Outlier data points were excluded unless patterns were consistently observed.

---

## Power BI Dashboards

- Download or explore the [Power BI dashboard Power BI Service Link](https://app.powerbi.com/links/0oPqE54S2z?ctid=d40fd338-1985-4ffd-966b-44cf9651f207&pbi_source=linkShare&bookmarkGuid=d82536ea-10f5-411a-842b-8a9f99d74813) containing:
    1. Main Dashboard - Sales Overview.
    2. Supplier Analysis Dashboard.
    3. Car Model Analysis Dashboard.
       
*Below are snaps from the dashboards*
![Dashboard P1](https://github.com/user-attachments/assets/af8b4e0b-079e-4929-87bc-d3425fc688d8)
![Dashboard P2](https://github.com/user-attachments/assets/1cb6aadb-2b59-40dc-8669-10d86e45aeb1)
![Dashboard P3](https://github.com/user-attachments/assets/f3fce59f-0c17-4076-9d51-7943fa40ebc4)


---

## Repository Contents

- **/Updated_carReapairCompanyData(1)**: [Contains sample datasets used for the analysis.](https://github.com/Goutbi/Car-Maintenance-Analysis/blob/main/Updated_CarRepairCompanyData%20(1).xlsx)
- **/Car Maintenance Project Preview**: [Power BI dashboard files for Power BI Desktop.](https://github.com/Goutbi/Car-Maintenance-Analysis/blob/main/Car%20Maintenance%20Project%20Preview.pbit)

## Getting Started

- Download the dataset from the repository or open the [Power BI link](https://app.powerbi.com/links/0oPqE54S2z?ctid=d40fd338-1985-4ffd-966b-44cf9651f207&pbi_source=linkShare&bookmarkGuid=551e3647-2c54-4acd-bab6-ed339ebbf8b1) in Power BI Service.
- Open the **.pbit** files in **Power BI Desktop** to explore the interactive dashboards.

---

