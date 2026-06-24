# Credit Card Financial Analytics Dashboard

## 📌 Project Overview

This project presents an interactive Credit Card Financial Analytics Dashboard built using Power BI, SQL, and DAX. The dashboard provides insights into customer behavior, transaction patterns, revenue generation, card performance, and delinquency trends through two dedicated dashboards:

- Credit Card Transaction Report
- Credit Card Customer Report

---

## 🎯 Project Objective

The objective of this project is to analyze credit card operations and customer data to uncover actionable business insights, monitor key performance indicators, and support data-driven decision-making.

Key goals include:

- Tracking revenue and transaction performance
- Understanding customer demographics and spending behavior
- Identifying high-value customer segments
- Monitoring delinquency and risk indicators
- Evaluating card category performance

---

## 📊 Dataset

### Finance Dataset

The project uses two datasets:

### 1. Customer Data (`cust_detail`)
Contains customer demographic and profile information:

- Client Number
- Age
- Gender
- Income
- Education Level
- Marital Status
- Occupation
- State
- Customer Satisfaction Score
- Dependent Count

### 2. Credit Card Data (`cc_detail`)
Contains transaction and credit card related information:

- Card Category
- Credit Limit
- Revenue
- Transaction Amount
- Transaction Count
- Interest Earned
- Annual Fees
- Delinquency Status
- Utilization Ratio
- Week Start Date

---

## 🛠 Tools & Technologies Used

- Power BI
- MySQL
- DAX
- Power Query
- Excel

---

## ⚙️ Project Workflow

### Step 1: Data Collection
- Imported customer and credit card datasets.
- Loaded data into MySQL database.

### Step 2: Data Cleaning & Transformation
- Removed inconsistencies and validated data.
- Created relationships between customer and transaction tables.

### Step 3: Data Modeling
- Built a star-schema model.
- Established relationships using Client Number.

### Step 4: DAX Calculations
Created custom measures and calculated columns such as:

- Revenue
- Current Week Revenue
- Previous Week Revenue
- Age Group
- Income Group
- Week Number
- WoW Revenue Change

### Step 5: Dashboard Development

#### Transaction Dashboard
- Revenue Analysis
- Transaction Trends
- Revenue by Card Category
- Revenue by Education
- Revenue by Expenditure Type
- Revenue by Job
- Revenue by Use Chip

#### Customer Dashboard
- Revenue by Age Group
- Revenue by Marital Status
- Revenue by State
- Delinquency Analysis
- Revenue by Dependent Count
- Customer Segmentation
- Card Category Distribution

---

## 📈 Key Insights

### Transaction Insights

- Total Revenue generated: **57M**
- Total Transaction Amount: **46M**
- Total Interest Earned: **8M**
- Total Transactions Count: **667K**
- Swipe transactions contribute the highest revenue.
- Blue card category generates the majority of revenue.
- Bills, Entertainment, and Fuel are the top spending categories.
- Businessman and White-Collar customers contribute the highest revenue.

### Customer Insights

- Total Customer Income: **588M**
- Average Customer Satisfaction Score: **3.19**
- Customers aged **40–50 years** generate the highest revenue.
- Married customers contribute more revenue than single customers.
- Texas, New York, and California are the top-performing states.
- Delinquency rates are highest in California and Texas.
- Revenue is distributed relatively evenly among card categories.

---

## 🚀 Business Recommendations / Action Items

### 1. Increase Premium Card Adoption
- Promote Gold and Platinum cards through targeted campaigns.
- Offer exclusive rewards and cashback programs.

### 2. Reduce Delinquency Risk
- Monitor customers with high utilization ratios.
- Implement early-warning alerts and payment reminders.

### 3. Focus on High-Value Segments
- Target customers aged 40–60 years.
- Design personalized offers for business professionals and high-income customers.

### 4. Improve Customer Satisfaction
- Analyze feedback from low-scoring customer groups.
- Enhance customer support and reward programs.

### 5. Optimize Marketing Spend
- Focus acquisition efforts on top-performing states.
- Use demographic segmentation for targeted marketing.


## 👨‍💻 Author

**Jaee Sakharkar**

Aspiring Business Analyst | Data Analyst

LinkedIn: www.linkedin.com/in/jaeesakharkar
